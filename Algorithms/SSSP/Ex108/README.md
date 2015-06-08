﻿### 108. Алгоритм Дейсктра

<pre>ограничение времени на тест: 0.25 сек.
ограничение памяти на тест: 8192 KB.</pre>

Задан взвешенный неориентированный граф из N вершин. Требуется найти длину кратчайшего пути из вершины v<sub>1</sub> в вершину v<sub>2</sub>.

**Входные данные**

В первой строке через пробел записано четыре натуральных числа N, M, v<sub>1</sub>, v<sub>2</sub> (1 <= N <= 500, 1 <= M <= N*N, 1 <= v<sub>1</sub>,v<sub>2</sub> <= N). 
Каждая из следующих M строк содержит описание одного ребра графа: три числа - начало, конец и длина. Длина ребра - неотрицательное целое число, и не превосходит 1000. 
Никакое ребро во входном файле не встречается дважды.

**Выходные данные**

В выходной файл вывести единственное число - длину кратчайшего пути из вершины v<sub>1</sub> в вершину v<sub>2</sub>, или -1 если такого пути не существует.

**Пример**

<pre>Ввод
2 1 1 2 
2 1 2

Вывод
2</pre>