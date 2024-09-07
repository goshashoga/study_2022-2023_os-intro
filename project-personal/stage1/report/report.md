---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 1"
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

Установить необходимое программное обеспечение.  
Скачать шаблон темы сайта.  
Разместить его на хостинге git.  
Установить параметр для URLs сайта.  
Разместить заготовку сайта на Github pages.  


# Выполнение лабораторной работы

Для начала скачаем hugo (рис. [-@fig:001]).

![Скачивание Hugo](image/1.jpg){#fig:001}

Распакуем его и установим, перенеся в /usr/local/bin (рис. [-@fig:002]).

![Установка Hugo](image/2.jpg){#fig:002}

Создадим из предложенного шаблона сайта репозиторий (рис. [-@fig:003]).

![Создание репозитория](image/3.jpg){#fig:003}

Клонируем репозиторий (рис. [-@fig:004]).

![Клонирование репозитория](image/4.jpg){#fig:004}

Установим Go (он нужен для запуска сайта) (рис. [-@fig:005]).

![Установка Go](image/5.jpg){#fig:005}

Запустим наш сайт командой Hugo server (рис. [-@fig:006]).

![Запуск сайта](image/6.jpg){#fig:006}

Создадим репозиторий, на котором наш сайт будет хоститься (рис. [-@fig:007]).

![Создание репозитория](image/7.jpg){#fig:007}

Клонируем только что созданный репозиторий, предварительно удалив папку public в папке blog  (рис. [-@fig:008]).

![Клонирование репозитория](image/8.jpg){#fig:008}

Создадим файл README для склонированного репозитория и загрузим изменения (рис. [-@fig:009]).

![Создание README и загрузка изменений](image/9.jpg){#fig:009}

Делаем клонированный репозиторий сабмодулем нашего первого репозитория blog (рис. [-@fig:010]).

![Настройка сабмодуля](image/10.jpg){#fig:010}

Запустим наш сайт ещё раз, чтобы прогрузить изменения в public (рис. [-@fig:011]).

![Запуск сайта](image/11.jpg){#fig:011}

Выложим изменения в public на github (рис. [-@fig:012]).

![Загрузка изменений в public](image/12.jpg){#fig:012}

Так теперь выглядит сайт на собственном домене (рис. [-@fig:013]).

![Внешний вид сайта](image/13.jpg){#fig:013}

# Выводы

В результате выполнения лабораторной работы был создан сайт из шаблона

# Список литературы{.unnumbered}

::: {#refs}
:::
