---
## Front matter
lang: ru-RU
title: Проектная работа шестой этап
author: |
	Malkov Roman Sergeevich
date: 04.06.2022

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
Выполнение шестого этапа проектной работы.

## Выполнение проектной работы

1. Запускаем локальный хост hugo командой ```hugo server```.

2. Заходи в директорию сайта переходим в config а затем в _default. Редактируем файл languages.yaml (Скриншот 1).

## Выполнение проектной работы

![Screenshot_1](screeny/Screenshot_1.png)

## Выполнение проектной работы

3. Создаем в директории content две папки "en" и "ru". В них помещаем содержимое контента ( Скриншот 2 ).

![Screenshot_2](screeny/Screenshot_2.png)

## Выполнение проектной работы

2. Создаем запись для персонального проекта. Для этого прописываем команду ``` hugo new project/<папка>/<файл>.md ```. Редактируем.
3. Добавляем пост по прошедшей неделе а также пост про оформление отчёта. Для этого прописываем команду ``` hugo new post/<папка>/<файл>.md ```. Редактируем содержимое файлов .md ( Скриншоты 3 - 4 ).

## Выполнение проектной работы

![Screenshot_3](screeny/Screenshot_3.png)

## Выполнение проектной работы

![Screenshot_4](screeny/Screenshot_4.png)

## Выполнение проектной работы

4. Прописываем команду hugo -D, она обновит нашу диреуторию public. Затем содержимое public , как и в предыдущей части выполнения работы, переносим в директорию сайта github.io. После данных мероприятий выгружаем все изменения в github. И вот результат на скриншоте 5:

## Выполнение проектной работы

![Screenshot_5](screeny/Screenshot_5.png)


## Вывод

Шестой этап проеткной работы выполнен.