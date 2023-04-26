# Multiplication Table

### Напишите программу, на вход которой даются четыре числа a, b, c и d, каждое в своей строке. Программа должна вывести фрагмент таблицы умножения для всех чисел отрезка [a;b] на все числа отрезка [c;d].

## Code:

<pre>
a = int(input())
b = int(input())
c = int(input())
d = int(input())
for x in range(c, d + 1):
    print('\t', x, end='')
for y in range(a, b + 1):
    print('\n', y, end='\t')
    for z in range(c, d + 1):
        print(y * z, end='\t')
print()
