# Задание 1. Написать первую программу

1. Если у вас ещё не установлена Giga IDE, следуйте [инструкции по установке Giga IDE](https://gitverse.ru/netology/Instructions/content/master/GigaIDE/installation.md).

2. Создайте проект в Giga IDE. Для этого нажмите на `Файл` → `Создать проект`. Выберите шаблон для проекта на языке C++ и задайте имя проекта (например, HelloWorld). Нажмите `Создать`. 

3.  В созданном проекте откройте файл main.cpp (если он не был создан автоматически, создайте его вручную). Появится стандартный код ниже:

```cs
#include <iostream>

int main() {
  std::cout << "Hello World!\n";
}
```

4. Измените текст в кавычках "Hello world!" на своё имя, например "Евгений". Не удаляйте символы \n в конце этой строки.

```cs
#include <iostream>

int main() {
  std::cout << "Евгений\n";
}
```

5. Запустите программу, нажав кнопку `Запуск`. На экране вы получите результат выполнения программы – вывод текста «Евгений».

```
Евгений
```

6. Добавьте ещё одну строку с выводом вашего возраста, например 28. Обратите внимание на отсутствие кавычек вокруг числа и отдельный символ переноса строки.

```cs
#include <iostream>

int main() {
  std::cout << "Евгений\n";
  std::cout << 28 << "\n";
}
```

7. Запустите программу. На экране вы увидете текст:

```
Евгений
28
```

8. Задача выполнена. Поздравляем! Не забудьте подставить в код своё имя и возраст :)
