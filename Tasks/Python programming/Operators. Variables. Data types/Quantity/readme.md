# Quantity

### Напишите программу, считывающую с пользовательского ввода целое число n (неотрицательное), выводящее это число в консоль вместе с правильным образом изменённым словом "программист", для того, чтобы робот мог нормально общаться с людьми, например: 1 программист, 2 программиста, 5 программистов.

## Code:

<pre>
a = int(input())
b = 'программист'
d = a % 10
d2 = (a // 10) % 10
if d2 == 1:
    print(a, b + 'ов')
elif d == 1:
    print(a, b)
elif 2 <= d % 10 <= 4:
    print(a, b + 'а')
elif 5 <= d % 10 <= 9:
    print(a, b + 'ов')
else:
    print(a, b + 'ов')
