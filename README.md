# Test

Описание алгоритма. 
Для поиска пути использовался алгоритм А*. 
Суть алгоритма в том, что он просматривает соседей текущего узла и считает их вес
при помощи эврестической функции, которая высчитывает манхэттенское расстояние. 
Потом из списка выбирается узел с наименьшим весом и проверяются его соседи.

Минус алгоритма в том, что он не особо подходит для трехмерных пространств.

Сложность алгоритма О(n).
