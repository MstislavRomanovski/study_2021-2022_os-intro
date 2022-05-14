---
## Front matter
title: "Проектная работа"
subtitle: "третий этап"
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

Выполнение третьего этапа проектной работы.

# Задание

* Добавить к сайту достижения.
Список достижений:
1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору:
- [ ] Легковесные языки разметки.
- [ ] Языки разметки. LaTeX.
- [x]Язык разметки Markdown.

# Выполнение проектной работы
1. Запускаем локальный хост hugo командой ```hugo server```( Скриншот 1 ).

![Screenshot_1](screeny/Screenshot_1.png)

( Скриншот 1 )

2. Изменяем наш список достижений, для этого переходим в директорию <папка с hugo>/content/home , после этого изменяем информацию в файлах: skills.md, experience.md, accomplishments.md ( Скриншоты 2 - 5 ).

![Screenshot_2](screeny/Screenshot_2.png)
( Скриншот 2 )

![Screenshot_4](screeny/Screenshot_4.png)
( Скриншот 3 )

![Screenshot_5](screeny/Screenshot_5.png)
( Скриншот 4 )

![Screenshot_6](screeny/Screenshot_6.png)
( Скриншот 5 )

3. Добавляем пост по прошедшей неделе а также пост про markdown. Для этого прописываем команду ``` hugo new <папка>/<файл>.md ```. Далее перекидываем наши папки со статьями в папку post. Редактируем содержимое файлов .md ( Скриншоты 6 - 8 ).

![Screenshot_7](screeny/Screenshot_7.png)
( Скриншот 6 )

![Screenshot_8](screeny/Screenshot_8.png)
( Скриншот 7 )

![Screenshot_9](screeny/Screenshot_9.png)
( Скриншот 8 )

4. Прописываем команду hugo -D, она обновит нашу диреуторию public. Затем содержимое public , как и в первой части выполнения работы, переносим в директорию сайта github.io. После данных мероприятий выгружаем все изменения в github ( Скриншоты 9-11 ).

![Screenshot_12](screeny/Screenshot_12.png)
( Скриншот 9 )

![Screenshot_10](screeny/Screenshot_10.png)
( Скриншот 10 )

![Screenshot_11](screeny/Screenshot_11.png)
( Скриншот 11 )

![Screenshot_13](screeny/Screenshot_13.png)
( Скриншот 12 )

![Screenshot_14](screeny/Screenshot_14.png)
( Скриншот 13 )

И вот результат на скриншотах 13 - 14:

![Screenshot_15](screeny/Screenshot_15.png)
( Скриншот 14 )

![Screenshot_16](screeny/Screenshot_16.png)
( Скриншот 15 )

# Выводы

Третий этап проеткной работы выполнен.

