# WEEK01

## Задача 1.
Да се напише програма, която приема ключ (положително число до 10 цифри) и
изречение (низ до 50 символа) от потребителя, след което записва числото цифра по цифра в масив и
променя изречението, като добавя към буква цифрата на съответната позиция.
Ако числото е по-късо от изречението, цифрите да започнат да се повтарят от началото.

Пример: 
> 123 baba -> cceb  // c = b + 1, c = a + 2, e = b + 3, b = a + 1

Програмата да извежда кодираня низ, след което да го декодира в оригиналния и отново
да го изведе.

## Задача 2.
Да се напише програма, която приема квадратна целочислена матрица (с размер до 15) от потребителя. Да се напише функция, която записва в едномерен масив поред всички прости числа в матрицата, като тя се обходи по вторичните диагонали в посока "отгоре-надолу".

Пример:
> 1 5 7 -> 5 3 7 2

> 3 2 6

> 4 8 9

   Програмата да изведе въведената матрица и масива, в който са записани подредените прости числа.

## Задача 3.
Да се напише програма, която приема едномерен целочислен масив (с размер до 100 елемента) и "пресява" елементите му по следния начин: В началото изтрива първото число, както и всяко следващо през една позиция, след това изтрива последното число и всяко предишно през една позиция и т.н.

Пример:
> 1 2 3 4 5 6 7 8 9 10 -> остават 2 4 6 8 10 -> остават 4 8 -> остава 8

Програмата да изведе числото, което остава след пресяването.

## Задача 4.
Да се напише рекурсивна функция, която приема като аргумент две числа и казва дали едното се съдържа в другото.

Пример:
> 528, 1252890 -> 1, 24, 42657 -> 0
