# Heron's formula

### Напишите программу, вычисляющую площадь треугольника по переданным длинам трёх его сторон по формуле Герона:
![Herons formula](https://user-images.githubusercontent.com/101666279/233312813-a129f82f-908d-4315-8769-39248239fdc1.png)
### где
 ![Per](https://user-images.githubusercontent.com/101666279/233312931-f46bbadb-9317-49b7-b212-2bfd57d1b6f6.png)
### – полупериметр треугольника. На вход программе подаются целые числа, выводом программы должно являться вещественное число, соответствующее площади треугольника.

## Code:

<pre>
a = int(input())
b = int(input())
c = int(input())
p = (a + b + c) / 2
print((p * (p - a) * (p - b) * (p - c)) ** 0.5)
