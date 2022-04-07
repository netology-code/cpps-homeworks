# Задача 2. Угадайка

### Описание
Напишите программу, которая просит пользователя угадать слово, записанное в коде - то есть вводить слова до тех пор, пока они не совпадут с загаданным

### Пример работы программы
```
Угадайте слово: арбуз
Неправильно
Угадайте слово: клубника
Неправильно
Угадайте слово: малина
Правильно! Вы победили! Загаданное слово - малина
```
#### Подсказки

> Не читайте этот раздел сразу, попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Подсказка. Что использовать для решения?</summary>

Для работы со строками вы можете использовать как обычные строки (`char *`), так и тип `std::string`

В случае использования обычных строк вам необходимо заранее выделить память под переменную, в которую вы будете записывать очередную попытку пользователя

Для сравнения строк используйте функцию `strcmp` в случае обычных строк, в случае `std::string` используйте `compare` или `==`

Для того, чтобы спрашивать пользователя до тех пор, пока он не угадает, используйте цикл `do...while`

Для ввода значений с консоли используйте `std::cin`

Для вывода на консоль используйте `std::cout`

</details>