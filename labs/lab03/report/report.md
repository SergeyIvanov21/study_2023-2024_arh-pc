---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Дисциплина: Архитектура Компьютера"
author: "Иванов Сергей Владимирович"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Выполнение лабораторной работы

Откроем терминал и перейдем в каталог курса, сформированный при выполнении лабораторной работы №2.Обновим локальный репозиторий, скачав изменения из удаленного репозитория. (Рис. @fig:001)

![ Обновляем локальный репозиторий.](image/1scr.jpg){#fig:001 width=70%}

Проведём компилляцию шаблона с использованием Makefile, используя команду 'make'. Проверим корректность полученный файлов. (Рис. @fig:002)

![ Компилляция шаблона.](image/2scr.jpg){#fig:002 width=70%}

Удалим полученный файл с помощью команды 'make clean' и убедимся что они удалены. (Рис. @fig:003)

![ Удаление файлов.](image/3scr.jpg){#fig:003 width=70%}

Откроем файл report.md командой 'gedit report.md'. (Рис. @fig:004)

![ Открываем файл.](image/4scr.jpg){#fig:004 width=70%}

Заполним отчет и скомпилируем его используя Makefile и загрузим файлы на GitHub. (Рис. @fig:005)

![ Загружаем на GitHub](image/5scr.jpg){#fig:005 width=70%}

# Выводы

В ходе выполнения лабораторной работы мы освоили процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

