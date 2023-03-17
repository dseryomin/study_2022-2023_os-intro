---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 2"
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

Добавить на сайт данные о себе,а также разместить несколько постов



# Выполнение лабораторной работы

1) Размещаю свою фотографию (рис. -@fig:001)

![почти моя фотография](image/Снимок экрана от 2023-03-17 12-38-32.png){#fig:001 width=90%}

2) Размещаю основную информацию о себе, только правду (рис.-@fig:002) 

![немного о себе](image/Снимок экрана от 2023-03-17 12-38-50.png){#fig:002 width=90%}

3) Проверяю изменения на сайте, все изменилось (рис.-@fig:003) 

![новый сайт](image/Снимок экрана от 2023-03-17 12-54-01.png){#fig:003 width=90%}

4) Размещаю пост о прошедшей неделе (рис.-@fig:004) 

![last week post](image/Снимок экрана от 2023-03-17 13-03-50.png){#fig:004 width=90%}

5) Размещаю пост про Лионелю Месю (рис.-@fig:005) 

![лионеля меся пост](image/Снимок экрана от 2023-03-17 13-07-25.png){#fig:005 width=90%}



# Выводы

Я добавил на сайт данные о себе и сделал 2 поста.

