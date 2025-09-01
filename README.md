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


