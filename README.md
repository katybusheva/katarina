# Подключаем модуль случайных чисел 
import random

 
# Заготовка для первого варианта

first = ["Розовые тени","Коричнивые тени","Желтые тени"]

 
second = ["Красная помада,"Розовая помада","Коричневая помада"]


 
third = ["Бронзер","Розовые румяна","Красный"]

 
# выводим вид макияжа

print("1 — Праздничный макияж")

print("2 — Легкий макияж")

print("3 — Яркий макияж")



 
# Спрашиваем у пользователя про его желание

makeup = int(input("{blue}Введите число с номером вида макияжа: {endcolor}".format(blue="\033[96m", endcolor="\033[0m")))

 
# Если число введено верно — выдаём вариант

if 0 < zodiac < 4:

    print(random.choice(first), random.choice(second), random.choice(second_add), random.choice(third))

else:

    print("Вы ошиблись с числом, запустите программу ещё раз")
