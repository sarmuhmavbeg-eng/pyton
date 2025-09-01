# pyton
txt = 'MsaatmiazD'
txt [1::2]
txt[::2]
'Matiz'

txt = 'MsaatmiazD'
# Извлекаем правильные символы для "Mazda"
# M + a + z + d + a = Mazda
car_name = txt[0] + txt[3] + txt[8] + txt[9] + txt[7]
print(car_name)  # Вывод: Mazda

txt = "mani ismim Sardor. man Toshkentda yashiman"
# Извлекаем город (последнее слово после "from")
residence = txt.split()[-2]
print(residence)  # Вывод: Toshkentda

txt = "mani ismim Sardor. man Toshkentda yashiman"
# Извлекаем город (последнее слово после "from")
residence = txt.split()[-2]
print(residence)  # Вывод: Toshkentda

txt = "I'm Sardor. I am from Tashkent"
area = txt.split("from ")[1]
print(area)  # Tashkent

text = input("Matn kiriting: ")
print(text[::-1])
namimalhsi nam

user_input = input("Введите строку: ")
reversed_string = user_input[::-1]
print("Перевернутая строка:", reversed_string)
Перевернутая строка: akitsitats

Перевернутая строка: akitsitats


word = input("Введите слово: ")
if word == word[::-1]:
    print(f"'{word}' является палиндромом")
else:
    print(f"'{word}' не является палиндромом")
    word = input("Введите слово: ")
if word == word[::-1]:
  'redivider' является палиндромом

  fruits = ["olma", "banan", "gilos", "shaftoli", "anor"]
print(fruits[3])  # gilos
anor
fruits = ["яблоко", "банан", "апельсин", "киви", "манго"]
print("Третий фрукт:", fruits[4])

girls = ["lopez", "shakira", "kim kard", "beyonce", "luiza", "shaxlo"]
print("Третий девушка:", girls[4])
Третий девушка: luiza

girls = ["lopez", "shakira", "kim kard", "beyonce", "luiza", "shaxlo"]
print(girls[5]) 
shaxlo

list1 = [10, 20, 30]
list2 = [40, 50, 66]

result = list1 + list2
print(result)

list1 = [100, 200, 300]
list2 = [400, 500, 600]
combined_list = list1 + list2
print("Объединенный список:", combined_list)
numbers = [200, 400, 600, 800, 1000]

new_list = [numbers[0], numbers[len(numbers)//3], numbers[-3]]
print(new_list)

numbers = [1000, 2000, 3000, 4000, 5000, 6000, 7000]
first = numbers[0]
middle = numbers[len(numbers)//2]
last = numbers[-1]
new_list = [first, middle, last]
print("Новый список:", new_list)

cities = ["Toshkent", "Parij", "London", "New York"]

if "Paris" in cities:
    print("Paris ro‘yxatda bor")
else:
    print("Paris ro‘yxatda yo‘q")

girls = ["lopez", "Luiza", "Shaxzoda", "Shakira"]

if "Luiza" in cities:
    print("Luisa ro‘yxatda bor")
else:
    print("Luisa ro‘yxatda yo‘q")

cities = ["Москва", "Лондон", "Париж", "Токио", "Ташкент"]
if "Ташкент" in cities:
    print("Тошкент есть в списке")
else:
    print("Тошкент нет в списке")
    original_list = [1, 2, 3, 4, 5]
duplicated_list = original_list * 2
print("Дублированный список:", duplicated_list)

nums = [1, 2, 3]
dup = nums * 2
print(dup)  # [1, 2, 3, 1, 2, 3]

numbers = [1, 2, 3, 4, 5]
numbers[0], numbers[-1] = numbers[-1], numbers[0]
print("Список после обмена:", numbers)
numbers = [10, 20, 30, 40, 50]

numbers[0], numbers[-1] = numbers[-1], numbers[0]
print(numbers)  # [50, 20, 30, 40, 10]


# Kvadratning tomoni berilgan
a = float(input("Kvadrat tomoni a = "))

perimetr = 4 * a
yuza = a * a

print("Kvadrat perimetri:", perimetr)
print("Kvadrat yuzasi:", yuza)

# Ввод стороны квадрата
side = float(input("Введите сторону квадрата: "))

# Вычисления
perimeter = 4 * side
area = side ** 2

# Вывод результатов
print(f"Периметр квадрата: {perimeter}")
print(f"Площадь квадрата: {area}")


import math

# Doiraning diametri berilgan
d = float(input("Doira diametri d = "))

uzunlik = math.pi * d
print("Doiraning uzunligi (aylanasi):", uzunlik)


import math

# Ввод диаметра круга
diameter = float(input("Введите диаметр круга: "))

# Вычисление длины окружности (C = π * d)
length = math.pi * diameter

# Вывод результата
print(f"Длина окружности: {length:.2f}")


a = float(input("a = "))
b = float(input("b = "))

ortalama = (a + b) / 2
print("O‘rtacha qiymat:", ortalama)

# Ввод двух чисел
a = float(input("Введите первое число (a): "))
b = float(input("Введите второе число (b): "))

# Вычисление среднего арифметического
mean = (a + b) / 2

# Вывод результата
print(f"Среднее арифметическое чисел {a} и {b}: {mean}")

# Ввод двух чисел
a = float(input("Введите первое число (a): "))
b = float(input("Введите второе число (b): "))

# Вычисления
sum_result = a + b
product = a * b
square_a = a ** 2
square_b = b ** 2

# Вывод результатов
print(f"Сумма: {a} + {b} = {sum_result}")
print(f"Произведение: {a} * {b} = {product}")
print(f"Квадрат первого числа: {a}² = {square_a}")
print(f"Квадрат второго числа: {b}² = {square_b}")

a = float(input("a = "))
b = float(input("b = "))

yigindi = a + b
kopaytma = a * b
kvadrat_a = a ** 2
kvadrat_b = b ** 2

print("Yig‘indisi:", yigindi)
print("Ko‘paytmasi:", kopaytma)
print("a ning kvadrati:", kvadrat_a)
print("b ning kvadrati:", kvadrat_b)

