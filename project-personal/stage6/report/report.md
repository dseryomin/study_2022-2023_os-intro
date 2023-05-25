---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 6"
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

Добавить поддержку английского языка, разместить элементы на этом языке и добавить новые посты


# Выполнение лабораторной работы

1) Получаю ссылку на локальный сайт,создаю поддиректории для двух языков,после чего в файле config.yaml добавляю поддержку английского языка и приступаю к добавлению на сайт информации на английском.

(рис. -@fig:001)

![создание поддиректорий для контента на разных языках](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2023-05-25 12-32-38.png){#fig:001 width=90%}

2) Перевожу сегмент опыт на английский,также как и другие сегменты сайта (рис. -@fig:002)

![перевод сегмента опыт](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2023-05-25 12-21-15.png){#fig:002 width=90%}

3) добавляю англоязычные версии постов (рис. -@fig:003)

![en версия одного из постов](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2023-05-25 12-22-35.png){#fig:003 width=90%}

4) Создаю пост на английском языке (рис. -@fig:004)

![пост на английском языке](/afs/.dk.sci.pfu.edu.ru/home/d/s/dseryomin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2023-05-25 12-28-57.png){#fig:004 width=90%}




# Выводы

Я добавил поддержку английского языка, разместил элементы на этом языке и добавил новые посты
