---
## Front matter
title: "Лабораторная работа 1"
subtitle: "Настройка git"
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

Изучить идеологию и применение средств контроля версий. Освоить умения по работе с git.


# Выполнение лабораторной работы

1) создадим ключ pgp и загрузим его на гитхаб (рис. -@fig:001)

![создание ключа pgp](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 18-01-16.png){ #fig:001 width=90% }

(рис.-@fig:002) 

![ключи на гитхаб](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 18-11-52.png){ #fig:002 width=90% }

2) Настроим автоматические подписи коммитов git (рис. -@fig:003)

![набор команд для настройки автоматических подписей коммитов гит](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 17-59-51.png){ #fig:003 }

3) Содадим репозиторий курса на основе шаблона (рис. -@fig:004)

![создание репозитория](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 18-02-50.png){ #fig:004 width=90% }

4) Настройка каталога курса и отправка файлов на сервер (рис. -@fig:005)

![настройка репозитория](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 18-04-48.png){ #fig:005 width=90% }

(рис. -@fig:006)
![отправка файлов на гитхаб](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/labs/lab01/report/Снимок экрана от 2023-02-15 18-04-08.png){ #fig:006 width=90% }



# Выводы

В рамках данной лабораторной работы я изучил идеологию и применение средств контроля версий. Освоил умения по работе с git.

