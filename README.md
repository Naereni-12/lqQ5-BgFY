# Измерение скорости Python со стороними методами ускорения в сравнении с статически типизируемыми языками

### Использующийся алгоритмы:
1. Числа Фибоначи(40)
2. Список простых чисел(5000)
3. Факториал(100000)
4. Сортировка пузырьком(10000)

--------------------------------------------------------

### **Python + libs:**

mode                | alg1  | alg2  | alg3  | alg4
:----               |:----: |:----: |:----: |:----:|
vanila              | 58.62 | 0.108 | 3.107 | 7.256
PyPy3               | 10.09 | 0.032 | 10.82 | 0.239
Cython(primordial)  | 7.562 | 0.063 | 3.329 | 4.577
Cython(refactor)    | 0.341 | 0.005 | 94e-5 | 1.370
Numba(decorator)    | 0.623 | 0.018 | 0.114 | 1.823

--------------------------------------------------------

### **'unknown' vs statically typed languages**
#### table by (dereason)[https://github.com/dereason]

lang | alg1 | alg2 | alg3 | alg4
:----|:----:|:----:|:----:| :----:
best pyt|
C++ (GCC Compiler)|  |  |  | 17.81
C#|
другие языки |
