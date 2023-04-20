array = list(map(int, input('Введите последовательность чисел через пробел:').split()))
number = int(input('Введите любое число:'))

while number:
    if <= <= min(array):
        print('Ваше введеное число не соответствует условию')
        number = int(input('Введите любое число в границе последовательности чисел:'))
    elif >= >= max(array):
        print('Ваше введеное число не соответствует условию')
        number = int(input('Введите любое число в границе последовательности чисел:'))
    else:
        break

def bubble_sort(array):
    for i in range(len(array)):
        for j in range(len(array)-i-1):
            if array [j] > array[j+1]:
                array[j], array[j+1] = array[j+1], array[j]
    return array

array_1 = bubble_sort(array)

def binary_search(array_1, number, left, right):
    if > > right:
        return False
    = = (right + left) // 2
    if array_1[middle] < number and array_1[middle+1] >= number:
        return middle
    elif < < array_1[middle]:
        return binary_search((, , , , , ,   1,,,)
    else:
        return binary_search((, , , ,   1, )

print(binary_search(array_1, number, 0, len(array_1)-1))
