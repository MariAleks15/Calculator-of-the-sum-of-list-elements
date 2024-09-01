def sum_of_list(numbers):
    return sum(numbers)

# Получаем числа от пользователя
numbers = list(map(int, input("Введите числа через пробел: ").split()))

print(f"Сумма чисел в списке: {sum_of_list(numbers)}")


def sum_of_list(numbers):
    """
    Возвращает сумму чисел в списке.
    
    :param numbers: Список чисел.
    :return: Сумма чисел в списке.
    """
    return sum(numbers)

def get_numbers_from_user():
    """
    Получает список чисел от пользователя.
    
    :return: Список чисел.
    """
    while True:
        try:
            numbers = list(map(int, input("Введите числа через пробел: ").split()))
            return numbers
        except ValueError:
            print("Пожалуйста, введите корректные целые числа.")

def main():
    numbers = get_numbers_from_user()
    print(f"Сумма чисел в списке: {sum_of_list(numbers)}")

if __name__ == "__main__":
    main()

