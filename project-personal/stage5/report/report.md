---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 5"
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

Добавить к сайту все остальные элементы.


# Выполнение лабораторной работы

1) Получаю ссылку на локальный сайт и добавляю свой проект (рис. -@fig:001)

![новый проект](image/Снимок экрана от 2023-05-11 12-54-45.png){#fig:001 width=90%}

2)создаю два поста и заполняю их (рис. -@fig:002)

![очередной ласт вик пост](image/Снимок экрана от 2023-05-11 12-56-24.png){#fig:002 width=90%}

(рис. -@fig:003)

![пост про programming languages](image/Снимок экрана от 2023-05-11 12-59-44.png){#fig:003 width=90%}

3)запушил изменения на сервер и убедился в корректности своих действий

# Выводы

Добавил к сайту все остальные элементы.
