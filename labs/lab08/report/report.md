---
## Front matter
title: "Лабораторная работа"
subtitle: "№8"
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

Изучить команды условного и безусловного переходов. Приобрести навыки написания программ с использованием переходов. Познакомиться с назначением и структурой файла листинга

# Задание


# Теоретическое введение


# Выполнение лабораторной работы

1)Создала каталог для программ лабораторной работы No 8, перешла в него и создала файл lab8-1.asm (рис. [-@fig:001])

![Создание каталога](image/Снимок\ экрана\ от\ 2022-12-01\ 10-41-11.png){ #fig:001 width=70% }

2)Вставила текст листинга (рис. [-@fig:002])

![текст листинга](image/Снимок\ экрана\ от\ 2022-12-01\ 10-45-15.png){ #fig:002 width=70% }

3)Создала исполняемый файл и запустила его (рис. [-@fig:003])

![проверка программы](image/Снимок\ экрана\ от\ 2022-12-01\ 10-50-34.png){ #fig:003 width=70% }

4)Изменила текст программы в соответствии с листингом 8.2. (рис. [-@fig:004])

![текст листинга](image/Снимок\ экрана\ от\ 2022-12-01\ 10-54-06.png){ #fig:004 width=70% }

5)Создала исполняемый файл и запустила его. (рис. [-@fig:005])

![проверка программы](image/Снимок\ экрана\ от\ 2022-12-01\ 10-55-20.png){ #fig:005 width=70% }

6)Создала файл. Внимательно изучила текст программы из листинга 8.3 и ввела в lab8-2.asm. (рис. [-@fig:006])

![текст листинга](image/Снимок\ экрана\ от\ 2022-12-01\ 11-03-15.png){ #fig:006 width=70% }

7)Создала исполняемый файл и проверила его работу для разных значений B. (рис. [-@fig:007])

![проверка программы при разных значениях](image/Снимок\ экрана\ от\ 2022-12-01\ 11-07-17.png){ #fig:007 width=70% }

8)Создала файл листинга для программы из файла lab8-2.asm. 
Открыла файл листинга lab8-2.lst с помощью любого текстового редактора mcedit (рис. [-@fig:008])

![файл листинга](image/Снимок\ экрана\ от\ 2022-12-01\ 11-10-42.png){ #fig:008 width=70% }

mov ecx,[max] - присвоение максимума
cmp ecx,[B] - сравнивается max(A,C) и B
jg fin -  если max(A,C)>B, то переходит на fin

9)Открыла файл с программой lab8-2.asm и в инструкции с двумя операндами удалила один операнд.(рис. [-@fig:009])

![текст программы](image/Снимок\ экрана\ от\ 2022-12-01\ 11-31-03.png){ #fig:009 width=70% }

10)В итоге в листинге появилось сообщение об ошибке(рис. [-@fig:010])

![изменение листинга](image/Снимок\ экрана\ от\ 2022-12-01\ 11-36-35.png){ #fig:010 width=70% }



# Выводы

В ходе лабораторной работы я изучила команды условного и безусловного переходов. Приобрела навыки написания программ с использованием переходов. Познакомилась с назначением и структурой файла листинга

# Список литературы{.unnumbered}

::: {#refs}
:::
