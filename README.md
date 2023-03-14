#работа №1
print(f"")
print(f"Привет! Предлагаю проверить свои знания английского!\nРасскажи, как тебя зовут!")

user = input(f'Как тебя зовут: ')

print(f"")
print(f"Привет,{user}, начинаем тренировку!")

#вопрос 1
print(f"")
print(f'My name ___ Vova')
answer_1 = input("Ответ: ")

if answer_1 == "is":
    print("Ответ верный!\nВы получили 10 баллов")
else:
    print("Неправильно. Правильный ответ: is")

#вопрос 2
print(f"")
print(f'I ___ a coder')
answer_2 = input("Ответ: ")

if answer_2 == "am":
    print("Ответ верный!\nВы получили 10 баллов")
else:
    print("Неправильно. Правильный ответ: am")

#вопрос 3
print(f"")
print(f'I live ___ Moscow')
answer_3 = input("Ответ: ")

if answer_3 == "in":
    print("Ответ верный!\nВы получили 10 баллов")
else:
    print("Неправильно. Правильный ответ: in")

#статистика
print(f"")
count = 0
if answer_1 == "is":
    count += 1
if answer_2 == "am":
    count += 1
if answer_3 == "in":
    count += 1

print(f'Вот и всё,{user}!\nВы ответили на {count} вопрос из 3 верно. ')
print(f"Вы заработали {count * 10} баллов.\nЭто {count * 33 + 1}")
