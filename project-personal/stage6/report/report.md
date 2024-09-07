---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 6"
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

Сделать поддержку английского и русского языков.  
Разместить элементы сайта на обоих языках.  
Разместить контент на обоих языках.  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору (на двух языках)  

# Выполнение лабораторной работы

Создадим 2 папки - ru и en, куда скопируем содержимое папки content, и переносим в них файлы ru.yaml и en.yaml соответственно (рис. [-@fig:001]).

![Создание папок](image/1.jpg){#fig:001}

В папке config/_default/ меняем файл languages.yaml следующим образом. В файле index.md нашегей папки en переводим текст на английский текст (рис. [-@fig:002]).

![Изменение файла languages.yaml](image/2.jpg){#fig:002}

Напишем пост о прошедшей неделе (рис. [-@fig:003]).

![Пост о прошедшей неделе](image/3.jpg){#fig:003}

Теперь мы можем переключать язык на сайте и язык текста будет меняться (рис. [-@fig:004]).

![Внешний вид сайта](image/4.jpg){#fig:004}

# Выводы

Сайт был переведён на английский язык и были добавлены посты

# Список литературы{.unnumbered}

::: {#refs}
:::
