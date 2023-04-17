---
## Front matter
title: "Отчёт по лабораторной работе №11"
subtitle: "Программирование в командном процессоре ОС UNIX. Ветвления и циклы"
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

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Задание

- Рассмотреть выполнение команд, приведённых в первой части описания лабораторной работы
- Выполнить действия, зафиксировав в отчёте по лабораторной работе используемые при этом команды и результаты их выполнения
- Создать отчёт и презентацию в Markdown
- Загрузить скринкасты на видео хостинг
- Представить работу на сайте ТУИС

# Выполнение лабораторной работы

![Создали директорию для выполнения 11 лабораторной работы](image/1.png)

![Создали файл для выполнения первого задания и сделали его исполняемым](image/2.png)

![Ввели текст программы в файл sh](image/3.png)

![Создали побочные текстовые файлы для работы с программой](image/4.png)

![Запустили программу](image/5.png)

![Создали файл для выполнения второго задания и сделали его исполняемым, создали файл с программой на языке С](image/6.png)

![Ввели текст программы на языке С в файл](image/7.png)

![Ввели текст программы в файл sh](image/8.png)

![Проверили корректность выполнения программы в исполняемом файле](image/9.png)

![Создали файл для выполнения третьего задания и сделали его исполняемым](image/10.png)

![Ввели текст программы в файл sh](image/11.png)

![Создали временные файлы для примера](image/12.png)

![Запустили программу и ввели аргумент строки](image/13.png)

![На один временный файл стало меньше, как и задумывалось](image/14.png)

![Создали файл для выполнения четвертого задания и сделали его исполняемым](image/15.png)

![Ввели текст программы в файл sh](image/16.png)

![Проверили корректность выполнения программы в исполняемом файле, архив готов](image/17.png)

# Выводы

Изучили основы программирования в оболочке ОС UNIX. Научились писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

