# Cake

### Между информатиками и биологами устраивается соревнование. Победителям соревнования достанется пирог. В команде биологов - a человек, а в команде информатиков — b человек. Нужно заранее разрезать пирог таким образом, чтобы можно было раздать кусочки пирога любой команде, выигравшей соревнование, при этом каждому участнику этой команды должно достаться одинаковое число кусочков пирога. Нужно найти минимальное подходящее число.
### Напишите программу, которая помогает найти это число. Программа должна считывать размеры команд (два положительных целых числа a и b, каждое число вводится на отдельной строке) и выводить наименьшее число d, которое делится на оба этих числа без остатка.

## Code:

<pre>
a = int(input())
b = int(input())
s = 1
while s % a != 0 or s % b != 0:
    s += 1
else:
    print(s)
