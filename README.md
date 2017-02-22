## Репозиторий для лабораторной №1 группы ИКБО-05-16

[Инструкция](http://lab.mtudev.ru/pull-request.html) как сдать лабораторную. 

# Лабораторная №1. Структуры. Чтение из файла

**Входные данные**: на вход программы подается файл заранее неизвестного размера, в котором в двоичном формате записано некоторое количество пакетов данных. Структура пакета: целочисленное значение, строка длиной 255 символов (+ символ конца строки), число с плавающей точкой одинарной точности.

**Задача**: прочитать файл и вывести таблицу на экран. Указать размер прочитанного файла.

**Требования**

* Программа должна принимать имя файла в качестве аргумента командной строки. Если при запуске аргумент не был передан или такого файла не существует, программа должна требовать ввести имя файла
* Программа должнв быть написана на C89
* Программа должна быть кросс-платформенной

**Задача со звездочкой**: вывести таблицу с применением графического интерфейса пользователя (Qt, WinAPI, etc). Программа должна предусматривать возможность редактирования записей и добавления новых. Основная часть программы (чтение записей из файла) должна быть реализована на C89, все остальное может быть реализовано на C, C++, C#, Python или Ruby.

**Как код компилируется при проверке?** 
`gcc --std=c89 -Wall -Werror file.c` 