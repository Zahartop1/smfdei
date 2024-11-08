#1
start = int(input("Первое число"))
end = int(input("Второе число")) 
print(f"Числа кратные 7 в диопозоне {start} до {end}:")
for number in range(start, end + 1):
    if number % 7 == 0: 
        print(number)

#2
start = int(input("Первое число"))
end = int(input("Второе число")) 
print(f"Все числа диапозона от {start} до {end}") 
for number in range(start, end + 1): 
      print(number) 


start = int(input("Первое число"))
end = int(input("Второе число")) 
for number in range(start, end + 1): 
    print(sorted(numbers, reverse=True))

start = int(input("Первое число"))
end = int(input("Второе число")) 
print(f"Числа кратные 7 в диопозоне {start} до {end}:")
for number in range(start, end + 1):
    if number % 7 == 0: 
        print(number)

start = int(input("Первое число"))
end = int(input("Второе число")) 
print(f"Числа кратные 7 в диопозоне {start} до {end}:")
for number in range(start, end + 1):
    if number % 5 == 0: 
        print(number)
