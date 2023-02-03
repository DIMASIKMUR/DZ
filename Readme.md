# Задача по практикуму

## Условия задачи:

_Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами._

## Решение задачи:

1. Объявляем массив (array1) с типом string;
2. Объявляем второй массив (array2) с типом string;
3. Прописываем метод (void SecondArrayOfThree);
4. Создаем переменную счетчик (count);
5. Внутри метода с помощью цикла (for) проверяем условия (<=3), если да, то элемент первого массива (array1) заносится в переменную (count) второго массива (array2);
6. После присвоения, увеличиваем переменную (count) на 1 (count++), возвращаемся к циклу (for) в котором i увеличивается на 1 (i++), проверяем до конца. В файле DiagramFinalWork.drawio.png хранится блок-схема решения задачи.

## Блок-схема

![Блок-схема](DZ.png)

## Программа:

Для запуска программы перейдите в папку  ***work*** и запустите команду через терминал:

> dotnet run 

Пример вывода программы:

> [2, hello, sun, 33, world] -> [2, sun, 33]