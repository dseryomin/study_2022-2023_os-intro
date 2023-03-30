---
## Front matter
title: "Лабораторная работа 8"
subtitle: "Текстовый редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Выполнение лабораторной работы

1)Создаю каталог с именем ~/work/os/lab06 и перехожу в него (рис. -@fig:001)

![создание каталога](image/Снимок экрана от 2023-03-30 12-48-32.png){#fig:001 width=90%}

2) вызываю vi и создаю файл hello.sh (рис. -@fig:002)

![запуск vi](image/Снимок экрана от 2023-03-30 12-49-26.png){#fig:002 width=90%}

3) Нажимаю i и ввожу необходимый текст (рис. -@fig:003)

![введенный текст](image/Снимок экрана от 2023-03-30 12-51-53.png){#fig:003 width=90%}

4) Нажимаю клавишу esc,перехожу в режим последней строки и ввожу wq (рис. -@fig:004)

![сохранение изменений](image/Снимок экрана от 2023-03-30 12-53-38.png){#fig:004 width=90%}

5) Добавляю права выполнения для файла hello.sh (рис. -@fig:005)

![добавление прав](image/Снимок экрана от 2023-03-30 12-54-29.png){#fig:005 width=90%}

Задание 2:
 
1) Вызываю редактор vi на редактирование файла и устанавливаю курсор в конец слова HELL,после чего,нажав i,добавляю букву О (рис. -@fig:006)

![добавляю букву О](image/Снимок экрана от 2023-03-30 12-57-30.png){#fig:006 width=90%}

2) Устанавливаю курсор на 4 строку и стираю слово LOCAL,вписывая вместо него local (рис. -@fig:007)

![заменяю LOCAL на local](image/Снимок экрана от 2023-03-30 12-58-32.png){#fig:007 width=90%}

3) Вставляю после последней строки файла определенный текст и удаляю последнюю строку,после чего удаляю последнюю команду клавишей u и выхожу из редактора,сохранив изменения (рис. -@fig:008)

![удаление строки](image/Снимок экрана от 2023-03-30 12-59-26.png){#fig:008 width=90%}


# Выводы

Я познакомился с операционной системой Linux. Получил практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

