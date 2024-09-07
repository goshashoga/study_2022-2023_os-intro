---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 3"
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

Добавить информацию о навыках (Skills).  
Добавить информацию об опыте (Experience).  
обавить информацию о достижениях (Accomplishments).  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору  

# Выполнение лабораторной работы

напишем в файле _index.md свои навыки и хобби с освоенными языками (рис. [-@fig:001]).

![Заполнение файла](image/1.jpg){#fig:001}

Напишем, что наш опыт - это учёба в вузе (рис. [-@fig:002]).

![Мой опыт](image/2.jpg){#fig:002}

Напишем пост о прошедшей неделе (рис. [-@fig:003]).

![Пост о неделе](image/3.jpg){#fig:003}

Напишем пост о LaTeX (рис. [-@fig:004]).

![Пост о LaTeX](image/4.jpg){#fig:004}

Так наши навыки будут отображаться на сайте (рис. [-@fig:005]).

![Внешний вид сайта](image/5.jpg){#fig:005}

# Выводы

На сайт были добавлены навыки и посты

# Список литературы{.unnumbered}

::: {#refs}
:::
