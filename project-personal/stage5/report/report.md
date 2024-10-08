---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 5"
author: "Габралян Георгий Александрович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
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

Создать свой собственный сайт на Hugo [@hugo] по инсткурции [@tuis]

# Задание

Сделать записи для персональных проектов.  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору.  

# Выполнение лабораторной работы

В папке project добавим папку, куда мы запишем информацию о нашем проеке - проходимом курсе по АКИОС (рис. [-@fig:001]).

![Информация о курсе](image/1.jpg){#fig:001}

Напишем пост о неделе (рис. [-@fig:002]).

![Пост о неделе](image/2.jpg){#fig:002}

Напишем пост о языках научного программирования (рис. [-@fig:003]).

![Пост о научных языках](image/3.jpg){#fig:003}

# Выводы

На сайт были добавленны проекты и посты

# Список литературы{.unnumbered}

::: {#refs}
:::
