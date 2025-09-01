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

