---
## Front matter
title: "Лабораторная работа 9"
subtitle: "Текстовый редактор emacs"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.


# Выполнение лабораторной работы

1) Открываю емакс и создаю файл lab07.sh,после чего набираю в ней необходимый текст (рис. -@fig:001)

![текст](image/Снимок экрана от 2023-04-06 13-32-27.png){#fig:001 width=90%}

2) Сохраняю файл и с помощью различных комбинаций клавиш выполняю стандартные процедуры редактирования текста  (рис. -@fig:002)

![новый текст](image/Снимок экрана от 2023-04-06 13-34-19.png){#fig:002 width=90%}

3)Использую команды по перемещению курсора, управляю буферами и окнами (рис. -@fig:003)

![управление окнами](mage/Снимок экрана от 2023-04-06 13-34-54.png){#fig:003 width=90%}

(рис. -@fig:004)

![4 окна](image/Снимок экрана от 2023-04-06 13-36-44.png){#fig:004 width=90%}

4) Переключаюсь в режим поиска и работаю в нем,после чего пробую другой режим клавишами M+s и вижу разницу (рис. -@fig:005)

![режим поиска](image/Снимок экрана от 2023-04-06 13-37-21.png){#fig:005 width=90%}


Контрольные вопросы:

    Кратко охарактеризуйте редактор emacs.

Emacs это мощный экранный редактор текста, написанный на языке высокого уровня Elisp.

    Какие особенности данного редактора могут сделать его сложным для освоения новичком?

Сложности могут возникнуть в запоминании большого количества сложный комбинаций клавиш, используемых emacs, а также на клавиатуре для IBM PC совместимых ПК клавиши Meta нет, но вместо неё можно использовать Alt или Esc.

    Своими словами опишите, что такое буфер и окно в терминологии emacs’а.

Буфер — объект, представляющий какой-либо текст.

Окно — прямоугольная область фрейма, отображающая один из буферов.

    Можно ли открыть больше 10 буферов в одном окне?

Да, можно.

    Какие буферы создаются по умолчанию при запуске emacs?

По умолчанию при открытии Emacs создает два буфера — scratch и Messages.

    Какие клавиши вы нажмёте, чтобы ввести следующую комбинацию C-c | и C-c C-|?

Ctrl+C Shift+\ и Ctrl+C Ctrl+Shift+.

    Как поделить текущее окно на две части?

Ctrl+2 разделить по горизонтали. Ctrl+3 разделить по вертикали.

    В каком файле хранятся настройки редактора emacs?

В файле .emacs хранятся настройки редактора emacs

    Какую функцию выполняет клавиша <– и можно ли её переназначить?

Backspace – стереть символ. Ее можно переобозначить.

    Какой редактор вам показался удобнее в работе vi или emacs? Поясните почему.

Для работы с маленькими файлами вполне удобно использовать vi, однако emacs несколько удобнее и имеет более расширенный функционал.

# Выводы

Познакомился с операционной системой Linux. Получить практические навыки работы с редактором Emacs.
