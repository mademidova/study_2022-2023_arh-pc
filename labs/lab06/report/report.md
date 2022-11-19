---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Архитектура компьютера"
author: "Демидова Мария Александровна"

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

Цель работы:Приобретение практических навыков работы в Midnight Commander. Освоение
инструкций языка ассемблера mov и int.


# Задание

# Теоретическое введение

# Выполнение лабораторной работы
1.Воспользовалась командой mc и перешла в каталог ~/work/arch-pc созданный при выполнении лабораторной работы No5, создала папку lab06 (рис. [-@fig:001])

![переход в каталог](image/Снимок\ экрана\ от\ 2022-11-17\ 10-53-36.png){ #fig:001 width=70% }
2.Воспользовалась строкой ввода и командой touch для создания файла lab6-1.asm

![Создание файла](image/Снимок\ экрана\ от\ 2022-11-17\ 10-55-00.png){ #fig:002 width=70% }
3.Ввела текст программы в редактор nano

![введение програмы в nano](image/Снимок\ экрана\ от\ 2022-11-17\ 11-06-10.png){ #fig:003 width=70% }
4.Оттранслировала текст программы lab6-1.asm в объектный файл. Выполнила компоновку объектного файла и запустила получившийся исполняемый файл. Программа выводит строку 'Введите строку:'. Ввела своё ФИО.

![Работа программы](image/Снимок\ экрана\ от\ 2022-11-17\ 11-12-08.png){ #fig:004 width=70% }
5.Скачала файл in_out.asm со страницы курса в ТУИС. Переместила файл с один каталог. 

![Работа программы](image/Снимок\ экрана\ от\ 2022-11-17\ 11-17-24.png){ #fig:005 width=70% }
6.С помощью функциональной клавиши F6 создала копию файла lab6-1.asm с именем lab6-2.asm. 

![Перемещение](image/Снимок\ экрана\ от\ 2022-11-17\ 11-19-18.png){ #fig:006 width=70% }
7.Исправила текст программы в файле lab6-2.asm с использование подпрограмм из внешнего файла in_out.asm 

![Программа](image/Снимок\ экрана\ от\ 2022-11-19\ 20-55-19.png){ #fig:007 width=70% }
8.В файле lab6-2.asm замените подпрограмму sprintLF на sprint. Создала исполняемый файл и проверила его работу. sprintLF работает аналогично sprint, но при выводе на экран добавляет к сообщению символ перевода строки
# Выводы
Приобрела практические навыки работы в Midnight Commander. Освоила инструкции языка ассемблера mov и int.



# Список литературы{.unnumbered}

::: {#refs}
:::
