---
## Front matter
title: "Отчёт о выполнении индивидуального проекта"
subtitle: "Этап 3"
author: "Михаил Александрович Мелкомуков"

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

Продолжить работы со своим сайтом. Редактировать его в соответствии с требованиями. Добавить данные о своих достижениях.

# Задание

- Добавить информацию о навыках (Skills)
- Добавить информацию об опыте (Experience)
- Добавить информацию о достижениях (Accomplishments)
- Сделать пост по прошедшей неделе

# Выполнение лабораторной работы

![Запустили локальный сервер](image/1.png)

![Перешли в директорию content](image/2.png)

![Изменили информацию о навыках в _index.md](image/3.png)

![Результат изменений](image/4.png)

![Скачали иконки и добавили их в специальный каталог](image/5.png)

![Изменили информацию об опыте](image/6.png)

![Как отображается информация об опыте на сайте](image/7.png)

![Изменили информацию о достижениях](image/8.png)

![Результат изменений](image/9.png)

![Создали каталог поста о прошедшей неделе](image/10.png)

![Отредактировали его и отобразили на станице](image/11.png)

# Выводы

Продолжили работу со своим сайтом. Отредактировали его в соответствии с требованиями. Добавили данные о своих достижениях.

