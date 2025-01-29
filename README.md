# if (n**0.5) == int(n**0.5): - проверка на квадрат

# for i in range(1, int(n**0.5)+1): - перебор для делителей, если нетривиальные
# (не 1 и не число), то начинать от 2

# def simple(n):
#     for i in range(2, int(n**0.5)+1):
#         if n%i==0:                           - проверка на простоту
#             return False
#     return True  and n!=1

# from fnmatch import *
# kol = 0
# for i in range(0, 10**9, 4215): # шаг - чему кратно
#     s = str(i)
#     if fnmatch(s, '?4?8*15?5'): # маска
#         print(s, i//4215)
