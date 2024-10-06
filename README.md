# module_2_2-
задание 2.2
first=int(input('Введите 1-е число:'))
second=int(input('Введите 2-е число:'))
third=int(input('Введите 3-е число:'))
if first == second and second == third and third == first:
        print(3)
elif first == second or second == third or third == first :
         print(2)
elif not first == second or second == third or third == first:
          print(0)
