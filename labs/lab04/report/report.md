---
## Front matter
title: "Лабораторная работа №4"
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
Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Выполнение лабораторной работы
1)Обновила локальный репозиторий, скачав изменения из удалённого репозитория.
(рис. [-@fig:001])
![обновление репозитория.](image/Снимок\ экрана\ от\ 2022-10-29\ 23-35-32.png){ #fig:001 width=70% }

1.1)Провела компиляцию шаблона с использованием Makefile, введя команду make. Сгенерировались файлы report.pdf и report.docx. Удалила полученный файлы с использованием Makefile, введя команду make clean.
(рис. [-@fig:002] )
![Команды make, make clean.](image/Снимок\ экрана\ от\ 2022-10-29\ 23-54-28.png){ #fig:002 width=70% }

1.2)Открыла файл report.md c помощью текстового редактора gedit.
(рис. [-@fig:003])
![создание отчёта в mardown.](image/Снимок\ экрана\ от\ 2022-10-30\ 01-17-34.png){ #fig:003 width=70% }
# Выводы

В ходе лабораторной работы я освоила процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
