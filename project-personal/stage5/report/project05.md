---
## Front matter
title: "Проектная работа"
subtitle: "пятый этап"
author: "Мальков Роман Сергеевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Выполнение четвертого этапа проектной работы.

# Задание

Добавить с сайту все остальные элементы.

- Сделать записи для персональных проектов.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору.
- [x ]Языки научного программирования.

# Выполнение проектной работы

1. Запускаем локальный хост hugo командой ```hugo server```( Скриншот 1 ).

![Screenshot_10](screeny/Screenshot_10.png)
( Скриншот 1 )

2. Создаем запись для персонального проекта. Для этого прописываем команду ``` hugo new project/<папка>/<файл>.md ```. Редактируем ( Скриншот 2 ).

![Screenshot_3](screeny/Screenshot_3.png)
( Скриншот 2 )

3. Добавляем пост по прошедшей неделе а также пост про оформление отчёта. Для этого прописываем команду ``` hugo new post/<папка>/<файл>.md ```. Редактируем содержимое файлов .md ( Скриншоты 3 - 4 ).

![Screenshot_1](screeny/Screenshot_1.png)
( Скриншот 3 )

![Screenshot_2](screeny/Screenshot_2.png)
( Скриншот 4 )


4. Прописываем команду hugo -D, она обновит нашу диреуторию public. Затем содержимое public , как и в предыдущей части выполнения работы, переносим в директорию сайта github.io. После данных мероприятий выгружаем все изменения в github ( Скриншоты 5-9 ).

![Screenshot_11](screeny/Screenshot_11.png)
( Скриншот 5 )

![Screenshot_4](screeny/Screenshot_4.png)
( Скриншот 6 )

![Screenshot_5](screeny/Screenshot_5.png)
( Скриншот 7 )

![Screenshot_9](screeny/Screenshot_9.png)
( Скриншот 8 )

![Screenshot_8](screeny/Screenshot_8.png)
( Скриншот 9 )

И вот результат на скриншотах 10 - 11:

![Screenshot_7](screeny/Screenshot_7.png)
( Скриншот 10 )

![Screenshot_6](screeny/Screenshot_6.png)
( Скриншот 11 )

# Выводы
Пятый этап проеткной работы выполнен.

