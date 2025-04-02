# Параллельное вычисление суммы элементов массива
Этот репозиторий содержит реализацию последовательного и параллельного вычисления суммы элементов массива с использованием OpenMP.

## Описание 

-Генерация большого массива случайных чисел

-Последовательное вычисление суммы (функция sum())

-Параллельное вычисление суммы с использованием OpenMP (функция sum_parallel())

-Сравнение времени выполнения обоих подходов

## Особенности реализации
Генерация случайных чисел с использованием <random> (более надежная, чем rand())

Параллельная версия использует директиву OpenMP #pragma omp parallel for

Применение редукции для корректного суммирования в параллельной версии


## Пример вывода программы

-Вычисленную сумму элементов

-Время выполнения последовательной версии

-Время выполнения параллельной версии

SUM: 42345

SERIAL: 20ms

PARALLEL: 5ms


