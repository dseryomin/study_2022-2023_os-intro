---
## Front matter
title: "Лабораторная работа 12"
subtitle: "Программирование в командном процессоре ОС UNIX. Расширенное программирование"
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

Изучить основы программирования в оболочке ОС UNIX. Научиться писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.


# Выполнение лабораторной работы

1) Написал командный файл,реализующий упрощенный механизм семафоров,после чего добавил право на исполнение (рис. -@fig:001)

![первый командный файл](image/Снимок экрана от 2023-04-24 12-25-28.png){#fig:001 width=90%}

2) Просмотрел содержимое каталога /usr/share/man/man1 (рис. -@fig:002)

![содержимое каталога](image/Снимок экрана от 2023-04-24 12-32-20.png){#fig:002 width=90%}

3) Написал командный файл,позволяющий реализовать команду man с помощью команды less, которая выдает содержимое справки по команде,после чего добавил право на исполнение файла  (рис. -@fig:003)

![вторая программа](image/Снимок экрана от 2023-04-24 12-25-45.png){#fig:003 width=90%}

4) Написал командный файл,который генерировал случайную последовательность букв латинского алфавита,после чего добавил право на исполнение файла  (рис. -@fig:004)

![третья программа](image/Снимок экрана от 2023-04-24 12-26-19.png){#fig:004 width=90%}

Контрольные вопросы: 
    Найдите синтаксическую ошибку в следующей строке: 1 while [$1 != "exit"]

Между скобками должны быть пробелы, иначе символы в скобках и сами скобки буду восприняты как один элемент.

    Как объединить (конкатенация) несколько строк в одну?

cat file.txt | xargs

    Найдите информацию об утилите seq. Какими иными способами можно реализовать её функционал при программировании на bash?

Команда seq выводит последовательность целых или действительных чисел, подходящую для передачи в другие программы. Реализовать ее функционал можно командой for n in {1..5} do <КОМАНДА> done

    Какой результат даст вычисление выражения $((10/3))? Вычисление этого выражения даст результат 3
    Укажите кратко основные отличия командной оболочки zsh от bash.

Zsh очень сильно упрощает работу. Но существуют различия. Например, в zsh после for обязательно вставлять пробел, нумерация массивов в zsh начинается с 1. Если вы собираетесь писать скрипт, который будет запускать множество разработчиков, то рекомендуется Bash. Если скрипты вам не нужны - Zsh.

    Проверьте, верен ли синтаксис данной конструкции 1 for ((a=1; a <= LIMIT; a++))

Да, этот синтаксис верен.

    Сравните язык bash с какими-либо языками программирования. Какие преимущества у bash по сравнению с ними? Какие недостатки?

Многие языки программирования намного удобнее и понятнее для пользователя. Например, Python более быстр, так как компилируется байтами. Однако главное преимущество Bash – его повсеместное распространение. Более того, Bash позволяет очень легко работать с файловой системой без лишних конструкций (в отличие от других языков программирования). Но относительно таких bash очень сжат. То есть, например, C имеет гораздо более широкие возможности для разработчика.




# Выводы

Я изучил основы программирования в оболочке ОС UNIX. Научился писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

