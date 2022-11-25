---
## Front matter
title: "Лабораторная работа"
subtitle: "№7"
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

Освоить арифметические инструкции языка ассемблера NASM.

# Задание

# Теоретическое введение
Создала каталог lab07 и внутри создал файл lab7-1.asm

# Выполнение лабораторной работы

1)Создала каталог lab07 и внутри создал файл lab7-1.asm (рис. [-@fig:001])

![Создание файла lab7-1.asm](image/Cнимок\ экрана\ от\ 2022-11-23\ 22-45-14.png){ #fig:001 width=70% }

2)Записала в файл текст (рис. [-@fig:002])

![Листинг](image/Cнимок\ экрана\ от\ 2022-11-23\ 22-52-06.png){ #fig:002 width=70% }

Создала файл, он вывел j (рис. [-@fig:003])
![Проверка работы файла](image/Cнимок\ экрана\ от\ 2022-11-23\ 22-52-02.png){ #fig:003 width=70% }

3)Затем заменила текст программы (рис. [-@fig:004])

![Изменённый текст программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 22-56-39.png){ #fig:004 width=70% }

Она вывела невидимый символ (рис. [-@fig:005])

![Проверка программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 22-58-29.png){ #fig:005 width=70% }

4)Создала файл lab7-2.asm, ввела текст программы (рис. [-@fig:006])

![Листинг](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-27-40.png){ #fig:006 width=70% }

Проверила его. Он выводит число 106 (рис. [-@fig:007])

![Проверка программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-46-44.png){ #fig:007 width=70% }

5)Изменила текст программы lab7-2 и проверила её. (рис. [-@fig:008])

![Замена текста программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-50-37.png){ #fig:008 width=70% }

Она вывела число 10 (рис. [-@fig:009])

![Проверка изменённой программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-49-24.png){ #fig:009 width=70% }

6)Изменила функцию iprintLF на iprint в программе lab7-2. (рис. [-@fig:010])

![Замена текста программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-50-37.png){ #fig:010 width=70% }

Получила так же результат 10, но отличие в том, что данные выводятся на той же строке. (рис. [-@fig:011])

![Проверка изменённой программы](image/Cнимок\ экрана\ от\ 2022-11-23\ 23-55-39.png){ #fig:011 width=70% }

6)Создала файл lab7-3.asm, ввела текст программы (рис. [-@fig:011])

![Замена текста программы](image/Cнимок\ экрана\ от\ 2022-11-24\ 10-34-41.png){ #fig:012 width=70% }

Проверила его. Он выводит результат 4 и остаток 1 (рис. [-@fig:012])

![Проверка программы](image/Cнимок\ экрана\ от\ 2022-11-24\ 10-47-14.png){ #fig:013 width=70% }

7)Изменила текст программы, чтобы посчитать функцию. (рис. [-@fig:013])

![Замена текста программы](image/Cнимок\ экрана\ от\ 2022-11-24\ 10-50-33.png){ #fig:013 width=70% }

Она вывела результат 5 и остаток 1 (рис. [-@fig:014])

![Проверка программы](image/Cнимок\ экрана\ от\ 2022-11-24\ 10-51-33.png){ #fig:014 width=70% }

8)Я сосзада файл variant.asm, ввела нужный текст и проверила его работу. 
Ввела номер своего студенческого билета и получила 14 вариант. (рис. [-@fig:015])

![Получение варианта](image/Cнимок\ экрана\ от\ 2022-11-24\ 10-59-03.png){ #fig:015 width=70% }

ОТВЕТЫ НА ВОПРОСЫ:
1)mov eax,msg call srintLF
2)Функции используются для ввода переменных с клавиатуры и сохранения введённых данных.
3)Используется для преобразования в число
4)mov ebx, 20 div ebx inc edx
5)В регистре ebx
6)Для увелечения значения edx на 1
7)mov eax,edx call iprintLF

Самостоятельная работа:
1)Я написала программу которая будет считать выражение при вводе различных значениях переменной х. Я писала программу для 14 варианта. Проверила работу программы для х=1 и х=4. Ответы верные. (рис. [-@fig:016])

![Программа для вычисления выражения](image/Cнимок\ экрана\ от\ 2022-11-24\ 12-12-23.png){ #fig:016 width=70% }

Проверила (рис. [-@fig:017])

![Проверка программы](image/Cнимок\ экрана\ от\ 2022-11-24\ 12-13-06.png){ #fig:017 width=70% }




# Выводы

В ходе лабораторной работы я освоила арифметические инструкции языка ассемблера NASM.

# Список литературы{.unnumbered}

::: {#refs}
:::
