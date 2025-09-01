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
