---
## Front matter
lang: ru-RU
title: Лабораторная работа №6
author: |
	Malkov Roman Sergeevich
date: 05.05.2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 44
section-titles: true
---


## Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

## Ход работы

Осуществляем вход в систему, используя соответсвующее имя и пароль.

![Screenshot_20](Screens/Screenshot_20.png)


## Ход работы

Записываем в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописываем в этот же файл названия файлов, содержащихся в вашем домашнем каталоге.

![Screenshot_1](Screens/Screenshot_1.png)


## Ход работы

Выводим имена всех файлов из file.txt, имеющих расширение .conf, после чего
записывем их в новый текстовой файл conf.txt.

![Screenshot_2](Screens/Screenshot_2.png)


## Ход работы

Определяем, какие файлы в нашем домашнем каталоге имеют имена, начинающиеся
с символа c. Выполняем несколькими способами.

![Screenshot_3](Screens/Screenshot_3.png)


## Ход работы

![Screenshot_4](Screens/Screenshot_4.png)


## Ход работы

Выводим на экран имена файлов из каталога /etc, начинающиеся
с символа h.

![Screenshot_21](Screens/Screenshot_21.png)

## Ход работы

Запускаем в фоновом режиме процесс, который будет записывать в файл ~/logfile
файлы, имена которых начинаются с log.

![Screenshot_9](Screens/Screenshot_9.png)


## Ход работы

Удаляем файл ~/logfile(Скриншот 8).

![Screenshot_10](Screens/Screenshot_10.png)


## Ход работы

Запускаем из консоли в фоновом режиме редактор gedit.Определяем идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep.

![Screenshot_11](Screens/Screenshot_11.png)


## Ход работы

Читаем справку (man) команды kill, после чего используем её для завершения
процесса gedit.

![Screenshot_12](Screens/Screenshot_12.png)


## Ход работы

![Screenshot_13](Screens/Screenshot_13.png)


## Ход работы

Выполяем команды df и du, предварительно получив более подробную информацию
об этих командах, с помощью команды man.


![Screenshot_14](Screens/Screenshot_14.png)


## Ход работы

![Screenshot_15](Screens/Screenshot_15.png)


## Ход работы

![Screenshot_16](Screens/Screenshot_16.png)


## Ход работы

![Screenshot_17](Screens/Screenshot_17.png)


## Ход работы

Воспользовавшись справкой команды find, выводим имена всех директорий, имеющихся в вашем домашнем каталоге.

![Screenshot_18](Screens/Screenshot_18.png)


## Ход работы

![Screenshot_19](Screens/Screenshot_19.png)


## Вывод
Мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных.
Приобрели практические навыки: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.