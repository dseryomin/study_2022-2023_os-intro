---
## Front matter
title: "Лабораторная работа 10"
subtitle: "Программирование в командном процессоре ОС UNIX. Командные файлы"
author: "Ерёмин Даниил"

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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.


# Выполнение лабораторной работы

1) Создаю папку в которой будут храниться sh файлы с кодом программ и создаю в ней sh файлы (рис. -@fig:001)

![создание sh файлов](image/Снимок экрана от 2023-04-10 13-17-56.png){#fig:001 width=90%}

2) Последовательно пишу 4 скрипта, указанных в лабораторной работе  (рис. -@fig:002)

![первый скрипт](image/Снимок экрана от 2023-04-10 13-20-53.png){#fig:002 width=90%}

(рис. -@fig:003)

![второй скрипт](image/Снимок экрана от 2023-04-10 13-21-02.png){#fig:003 width=90%}

(рис. -@fig:004)

![третий скрипт](image/Снимок экрана от 2023-04-10 13-21-08.png){#fig:004 width=90%}

(рис. -@fig:005)

![четвертый скрипт](image/Снимок экрана от 2023-04-10 13-21-15.png){#fig:005 width=90%}



# Выводы

Я изучил основы программирования в оболочке ОС UNIX/Linux. Научился писать небольшие командные файлы.


