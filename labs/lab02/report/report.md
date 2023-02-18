---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Система контроля версий Git"
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

Ознакомиться с принципами работы средств контроля версий. Настроить git для начала работы. Используя git, создать рабочее пространство и репозиторий курса, после чего загрузить файлы на GitHub.

# Задание

Создать репозиторий курса. Загрузить файлы на github.

# Выполнение лабораторной работы

Система контроля версий git уже установлена на пк в дисплейном классе. Базовая настройка проведена. В ходе выполнения лабороторной работы №3 в предыдущем семестре была создана учётная запись на github и репозиторий курса "Архитектура компьютеров". По анологии сделали репозиторий курса "Операционные системы".

![Учётная запись на github](image/1.png)

![SSH ключи](image/2.png)

![Настроили каталог курса на пк в дисплейном классе](image/3.png)

![Скопировали репозиторий с учётной записи github в каталог курса](image/4.png)

![Удалили лишние файлы и создали необходимые каталоги](image/5.png)

![Отправили файлы на сервер](image/6.png)

![Проверили корректность выполнения предыдущего действия](image/7.png)

# Выводы

Идеология и применение средств контроля версий изучены. После базовой настройки git создали иерархию рабочего пространства в локальном репозитории и на странице GitHub.
