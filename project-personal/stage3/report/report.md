---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 3"
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

1) Введя команду ~/bin/hugo server,получаю ссылку на лок.сайт,на котором буду промежуточно отслеживать все изменения
2) Изменяю информацию о навыках,достижениях и опыте, заполняю новые посты про прошедшую неделю и маркдаун(рис. -@fig:001)

![мои скиллы](image/Снимок экрана от 2023-04-06 12-57-19.png){#fig:001 width=90%}

(рис. -@fig:002)

![мой экспирианс](image/Снимок экрана от 2023-04-06 12-57-23.png){#fig:002 width=90%}

(рис. -@fig:003)

![новые посты](image/Снимок экрана от 2023-04-06 12-57-31.png){#fig:003 width=90%}

3) Затем выполняю ~/bin/hugo и отправляю изменения на сервер (рис. -@fig:004)

![отправка файлов на сервер](image/Снимок экрана от 2023-04-06 12-02-40.png){#fig:004 width=90%}


# Выводы

Я добавил информацию на сайт

