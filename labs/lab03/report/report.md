---
## Front matter
title: "Лабораторная работа"
subtitle: "№3"
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


# Выполнение лабораторной работы
1)Создала учётную запись на сайте https://github.com/ и заполнила основные данные.Затем сделала предварительную конфигурацию git. Открыла терминал и ввела следующие команды, указав имя и email. Настроила utf-8 в выводе сообщений git. Задала имя начальной ветки.
(рис. [-@fig:001])
![Создание учётной записи в github](image/Снимок\ экрана\ от\ 2022-10-30\ 01-49-24.png){ #fig:001 width=70% }

1,1)Для последующей идентификации пользователя на сервере репозиториев сгенерировала приватный ключ.
(рис. [-@fig:002])
![Генерация приватного ключа](image/Снимок\ экрана\ от\ 2022-10-30\ 01-50-19.png){ #fig:002 width=70% }

1,2)Далее загрузила сгенерённый открытый ключ. 
(рис. [-@fig:003])
![Загрузка сгенерированного ключа](image/Снимок\ экрана\ от\ 2022-10-30\ 01-51-13.png){ #fig:003 width=70% }

1,3)Для создания репозитория, перешла на станицу репозитория с шаблоном курса и выбрала Use this template. Затем в открывшемся окне задала имя репозитория и создала репозиторий
(рис. [-@fig:004])
![Создание репозитория](image/Снимок\ экрана\ от\ 2022-10-30\ 01-51-34.png){ #fig:004 width=70% }

1,4)Открыла терминал и перешла в каталог курса и клонировала созданный репозиторий.
(рис. [-@fig:005])
![Клонирование репозитория](image/Снимок\ экрана\ от\ 2022-10-30\ 01-52-19.png){ #fig:005 width=70% }

1,5)Далее я перешла в каталог курса, удалила лишние файлы, создала необходимые
каталоги и отправила файлы на сервер.
(рис. [-@fig:006])
![Отправка на сервер](image/Снимок\ экрана\ от\ 2022-10-30\ 01-52-55.png){ #fig:006 width=70% }

# Выводы
В ходе лабораторной работы я изучила идеологию и применение средств контроля
версий и приобрела практические навыки по работе с системой git

# Список литературы{.unnumbered}

::: {#refs}
:::
