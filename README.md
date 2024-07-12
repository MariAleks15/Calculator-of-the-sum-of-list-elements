def sum_of_list(numbers):
    return sum(numbers)

# Получаем числа от пользователя
numbers = list(map(int, input("Введите числа через пробел: ").split()))

print(f"Сумма чисел в списке: {sum_of_list(numbers)}")
