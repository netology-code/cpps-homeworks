# Задача 1. Арифметические функции

### Описание
Дана программа:

```cpp
int main(int argc, char** argv)
{
	int a = 5, b = 10;

	int s = sum(a, b);
	int dif = diff(a, b);
	int mult = multiplication(a, b);
	double div = division(a, b);

	std::cout << a << " + " << b << " = " << s << std::endl;
	std::cout << a << " - " << b << " = " << dif << std::endl;
	std::cout << a << " * " << b << " = " << mult << std::endl;
	std::cout << a << " / " << b << " = " << div << std::endl;
	
	return 0;
}
```

В ней используются функции `sum`, `diff`, `multiplication`, `division`. Ваша задача — написать эти функции, чтобы результат работы программы выглядел следующим образом:
```
5 + 10 = 15
5 - 10 = -5
5 * 10 = 50
5 / 10 = 0.5
```
#### Подсказки

> Не читайте этот раздел сразу. Попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Что использовать для решения.</summary>

Из результата работы программы видно, что ваши функции реализуют базовые арифметические операции — сложение, вычитание, умножение и деление.

Помните о том, что результатами сложения, вычитания и умножения целых чисел будет также целое число, а вот результатом деления целых чисел может быть и  число дробное.

Для реализации самих арифметических операций используйте базовые операторы — `+`, `-`, `*`, `/`.

Не забывайте, что функция должна быть объявлена ранее, чтобы можно было её использовать.

</details>
