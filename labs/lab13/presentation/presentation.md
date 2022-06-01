---
## Front matter
lang: ru-RU
title: Лабораторная работа номер 13
author: Malkov Roman Sergeevich
date: 01.06.2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---


## Цель работы

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями.

## Ход работы

1. В домашнем каталоге создаем подкаталог ~/work/os/lab_prog ( Скриншот 1 ).

![Screenshot_1](screeny/Screenshot_1.png)

## Ход работы

2. Создаем в нём файлы: calculate.h, calculate.c, main.c ( Скриншоты 2 - 4 ).

![Screenshot_2](screeny/Screenshot_3.png)

## Ход работы

![Screenshot_3](screeny/Screenshot_2.png)

## Ход работы

![Screenshot_4](screeny/Screenshot_4.png)

## Ход работы

3. Выполняем компиляцию программы посредством использования gcc:

![Screenshot_5](screeny/Screenshot_5.png)

## Ход работы

4. При необходимости исправляем синтаксические ошибки.

5. Создаем Makefile ( Скриншоты 6 - 7 )

![Screenshot_6](screeny/Screenshot_6.png)

## Ход работы

![Screenshot_7](screeny/Screenshot_7.png)

## Ход работы

6. С помощью gdb выполняем отладку программы calcul( при этом стоит исправить файл Makefile, удалить все файлы формата .o и calcul файл, затем запустить Makefile ( Скриншоты 8 - 10 )):

![Screenshot_8](screeny/Screenshot_10.png)

## Ход работы

![Screenshot_9](screeny/Screenshot_11.png)

![Screenshot_10](screeny/Screenshot_12.png)

## Ход работы

– Запускаем отладчик GDB, загрузив в него программу для отладки ( Скриншот 11 ):
``` 
gdb ./calcul 
```

![Screenshot_11](screeny/Screenshot_9.png)

## Ход работы

– Для запуска программы внутри отладчика вводим команду run:
``` 
run 
```
## Ход работы

– Для постраничного (по 9 строк) просмотра исходного код используем команду
list ( Скриншот 12 ):
``` 
list 
```

![Screenshot_12](screeny/Screenshot_13.png)

## Ход работы

– Для просмотра строк с 12 по 15 основного файла используем list с параметрами ( Скриншот 13 ):
``` 
list 12,15 
```

![Screenshot_13](screeny/Screenshot_14.png)

## Ход работы

– Для просмотра определённых строк не основного файла используем list с параметрами:
``` 
list calculate.c:20,29 
```
– Устанавливаем точку останова в файле calculate.c на строке номер 21 ( Скриншот 14 ):
``` 
list calculate.c:20,27 
```
``` 
break 21 
```

## Ход работы

![Screenshot_14](screeny/Screenshot_15.png)

## Ход работы

– Выводим информацию об имеющихся в проекте точка останова ( Скриншот 15 ):
``` 
info breakpoints 
```

![Screenshot_15](screeny/Screenshot_16.png)

## Ход работы

– Запускаем программу внутри отладчика и убеждаемся, что программа остановится
в момент прохождения точки останова:
```
run
5
-
backtrace
```
– Отладчик выдаст следующую информацию ( Скриншот 16 ):
```
#0 Calculate (Numeral=5, Operation=0x7fffffffd280 "-")
at calculate.c:21
#1 0x0000000000400b2b in main () at main.c:17
```

## Ход работы

![Screenshot_16](screeny/Screenshot_17.png)


а команда backtrace покажет весь стек вызываемых функций от начала программы до текущего места.

## Ход работы

– Посмотрим, чему равно на этом этапе значение переменной Numeral, введя:
```
print Numeral
```

На экран должно быть выведено число 5.
– Сравниваем с результатом вывода на экран после использования команды:
```
display Numeral
```
– Убераем точки останова ( Скриншот 17 ):
```
info breakpoints
delete 1
```

## Ход работы

![Screenshot_17](screeny/Screenshot_18.png)

## Ход работы

7. С помощью утилиты splint попробуем проанализировать коды файлов calculate.c
и main.c. ( Скриншоты 18 - 19). 

![Screenshot_18](screeny/Screenshot_19.png)

## Ход работы

![Screenshot_19](screeny/Screenshot_20.png)

## Выводы

Мы приобрели простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.
