---
## Front matter
title: "Лабораторная работа"
subtitle: "№9"
author: "Демидова Мария Александровна-"

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

Приобретение навыков написания программ с использованием циклов и
обработкой аргументов командной строки.

# Задание

# Теоретическое введение


# Выполнение лабораторной работы

1)Создала каталог для программам лабораторной работы No 9, перешла в него и создала файл lab9-1.asm (рис. [-@fig:001])

![Создание файла](image/Снимок экрна\ от\ 2022-12-09\ 11-05-55.png){ #fig:001 width=70% }

2)Ввела в файл lab9-1.asm текст программы из листинга 9.1. (рис. [-@fig:002])

![текст листинга](image/Снимок экрна\ от\ 2022-12-09\ 11-31-44.png){ #fig:002 width=70% }

Создала исполняемый файл и проверила его работу. (рис. [-@fig:003])

![проверка програмыы](image/Снимок экрна\ от\ 2022-12-09\ 11-43-40.png){ #fig:003 width=70% }

3)Изменила текст программы, добавив изменение значение регистра ecx в цикле. (рис. [-@fig:004])

![изменённая программа](image/Снимок экрна\ от\ 2022-12-09\ 13-47-03.png){ #fig:004 width=70% }

Создала исполняемый файл и проверила его работу. Число проходов цикла не соответсвует значению 𝑁
введенному с клавиатуры(рис. [-@fig:005])

![проверка программы](image/Снимок экрна\ от\ 2022-12-09\ 13-48-45.png){ #fig:005 width=70% }

4)Внесла изменения в текст программы, добавив команды push и pop для сохранения значения счетчика цикла loop (рис. [-@fig:006])

![изменённая программа](image/Снимок экрна\ от\ 2022-12-09\ 13-52-41.png){ #fig:006 width=70% }

Создала исполняемый файл и проверила его работу. Число проходов цикла соответсвует значению 𝑁 введенному с клавиатуры.(рис. [-@fig:007])

![проверка программы](image/Снимок экрна\ от\ 2022-12-09\ 13-54-14.png){ #fig:007 width=70% }

5)Создала файл lab9-2.asm и ввела в него текст программы из листинга 9.2.(рис. [-@fig:008])

![текст листинга](image/Снимок экрна\ от\ 2022-12-09\ 13-59-17.png){ #fig:008 width=70% }

Создала исполняемый файл и запустила его, указав аргументы. Программой было обработано 4 аргумента(рис. [-@fig:009])

![проверка программы](image/Снимок экрна\ от\ 2022-12-09\ 14-12-18.png){ #fig:009 width=70% }

6)Создайте файл lab9-3.asm и введите в него текст программы из листинга 9.3(рис. [-@fig:010])

![текст листинга](image/Снимок экрна\ от\ 2022-12-09\ 14-37-16.png){ #fig:010 width=70% }

Создала исполняемый файл и запустила его, указав аргументы. (рис. [-@fig:011])

![проверка программы](image/Снимок экрна\ от\ 2022-12-09\ 14-30-49.png){ #fig:011 width=70% }

7)Изменила текст программы из листинга 9.3 для вычисления произведения аргументов командной строки. (рис. [-@fig:012])

![текст программы](image/Снимок экрна\ от\ 2022-12-11\ 18-12-29.png){ #fig:012 width=70% }

Создала исполняемый файл и запустила его, указав аргументы. (рис. [-@fig:013])

![проверка программы](image/Снимок экрна\ от\ 2022-12-09\ 14-40-27.png){ #fig:013 width=70% }

8)Самостоятельная работа
текст программы для функции 7(𝑥 - 1) (рис. [-@fig:014])

![проверка программы](image/Снимок экрна\ от\ 2022-12-11\ 18-23-32.png){ #fig:014 width=70% }

Проверка программы (рис. [-@fig:015])

![проверка программы](image/Снимок экрна\ от\ 2022-12-11\ 18-30-25.png){ #fig:015 width=70% }


# Выводы

В ходе лабораторной работы я приобрела навыки написания программ с использованием циклов и
обработкой аргументов командной строки.

# Список литературы{.unnumbered}

::: {#refs}
:::
