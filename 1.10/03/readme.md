# Задача 3. Динамическая таблица умножения

### Описание
Напишите четыре функции:
1. `create_two_dim_array`: принимает на вход количество строк и столбцов. Создаёт целочисленный двумерный динамический массив заданной размерности и возвращает указатель на него.
2. `fill_two_dim_array`: принимает на вход указатель на двумерный целочисленный массив, количество строк и столбцов в нём. Заполняет полученный массив значениями из таблицы умножения. Таблица не ограничена 10 строками или 10 столбцами. Не возвращает ничего.
3. `print_two_dim_array`: принимает на вход указатель на двумерный целочисленный массив, количество строк и столбцов в нём. Выводит полученный массив на консоль. Не возвращает ничего.
4. `delete_two_dim_array`: принимает на вход указатель на двумерный целочисленный массив, количество строк и столбцов в нём. Очищает полученный массив. Не возвращает ничего.

Используйте эти функции для организации работы программы, которая спрашивает у пользователя количество строк и столбцов и выводит на консоль таблицу умножения заданной размерности.

### Примеры работы программы
```
Введите количество строк: 10
Введите количество столбцов: 10
Таблица умножения:
 1  2  3  4  5  6  7  8  9  10
 2  4  6  8 10 12 14 16 18  20
 3  6  9 12 15 18 21 24 27  30
 4  8 12 16 20 24 28 32 36  40
 5 10 15 20 25 30 35 40 45  50
 6 12 18 24 30 36 42 48 54  60
 7 14 21 28 35 42 49 56 63  70
 8 16 24 32 40 48 56 64 72  80
 9 18 27 36 45 54 63 72 81  90
10 20 30 40 50 60 70 80 90 100
```
```
Введите количество строк: 5
Введите количество столбцов: 3
Таблица умножения:
1  2  3
2  4  6
3  6  9
4  8 12
5 10 15
```
```
Введите количество строк: 3
Введите количество столбцов: 3
Таблица умножения:
1 2 3
2 4 6
3 6 9
```
#### Подсказки

> Не читайте этот раздел сразу. Попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Что использовать для решения.</summary>

Процесс создания двумерного динамического массива описан в лекции.

Для ввода с консоли используйте `std::cin`.

Сигнатура функции `create_two_dim_array`: `int** create_two_dim_array(int rows, int cols)`.

Сигнатура функции `fill_two_dim_array` и остальных: `void fill_two_dim_array(int** arr, int rows, int cols)`.

Для вывода на консоль используйте `std::cout`.

Процесс очистки двумерного динамического массива описан в лекции.

</details>
