Поиск по нескольким образцам
алгоритмами Рабина-Карпа и Ахо-Корасик

Требуется найти все вхождения любого из образцов в текст. Результаты поиска не
должны зависеть от регистра букв, то есть каждая буква в образце и тексте может быть
как строчной, так и прописной.
Ввод из файла INPUT.TXT. Первая строка файла определяет количество образцов N. В
следующих N строках задаются образцы. Каждый из них имеет длину от 1 до 30 символов.
Последняя строка задает имя текстового файла.
В файле нет переноса слов. Образец может включать пробелы и переходить с одной
строки файла на другую. Конец строки файла может интерпретироваться как пробел.
Результаты поиска не должны зависеть от регистра букв, то есть каждая буква в образце и
файле может быть как строчной, так и прописной.
Вывод в файл OUTPUT.TXT. В каждой строке вывести номера строки и позиции, а
также тот образец, который найден в тексте, начиная с указанного места. Нумерация строк
и позиций в строке начинается с 1. Если вхождений нет, вывести No.
Пример. Файл Bukvar.txt состоит из 3 строк:
Мама мыла раму, потом мама
мыла дочку, а папа
весь день мыл свой мотоцикл.
Ввод
2
Мыл
Мама мыла
Bukvar.txt
Вывод
Line 1, position 1: Мама мыла
Line 1, position 6: Мыл
Line 1, position 23: Мама мыла
Line 2, position 1: Мыл
Line 3, position 11: Мыл