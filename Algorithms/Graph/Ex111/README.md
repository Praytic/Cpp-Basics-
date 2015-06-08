﻿### 111. Странная игра

<pre>ограничение времени на тест: 0.25 сек.
ограничение памяти на тест: 32768 KB.</pre>

Витя играет сам с собой в странную игру: он задумывает целые числа N (2 <= N <= 100000), a и b (0 <= a, b < N). После этого, отправляясь от числа a, он хочет получить число b за наименьшее число ходов. За один ход разрешается от числа x перейти к одному из чисел (x + 1) mod N, (x*x+1) mod N или (x*x*x+1) mod N. Ваша задача: написать программу, которая определяет искомое наименьшее число ходов и последовательность чисел, которые при этом получаются (включая начальное a и конечное b).

**Входные данные**

В первой строке входного файла записаны целые числа N, a и b.

**Выходные данные**

Если не существует способа получить число b из числа a указанным в условии способом, то в первой строке выходного файла должно располагаться число -1. 
В противном случае в ней должно быть искомое наименьшее число ходов L. В этом случае во второй строке должна быть выведена последовательность a = a<sub>0</sub>, a<sub>1</sub>, ..., a<sub>L</sub> = b чисел в том порядке, в котором они получаются в процессе преобразования.

**Пример**

<pre>Ввод
7 5 2

Вывод
2 
5 6 2</pre>