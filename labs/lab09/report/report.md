---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "Текстовый редактор emacs"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

- Ознакомиться с теоретическим материалом
- Ознакомиться с редактором emacs
- Выполнить упражнения
- Создать отчёт и презентацию в Markdown
- Загрузить скринкасты на видео хостинг
- Представить работу на сайте ТУИС

# Выполнение лабораторной работы

![Открыли emacs в фоновом режиме](image/1.png)

![Создали файл lab07.sh](image/2.png)

![Набрали текст](image/3.png)

![Сохранили файл](image/4.png)

![Вырезали одной командой целую строку](image/5.png)

![Вставили эту строку в конце файла](image/6.png)

![Выделили область текста](image/7.png)

![Скопировали область в буфер обмена и вставили её в конец файла](image/8.png)

![Вновь выделили область и вырезали её](image/9.png)

![Отменили последнее действие](image/10.png)

![Переместили курсор в начало строчки](image/11.png)

![Переместили курсор в конец строчки](image/12.png)

![Вывели список активных буферов на экран](image/13.png)

![Переключились на другой буфер](image/14.png)

![Поделили фрейм на четыре части](image/15.png)

![В каждом из четырёх созданных окон открыли новый буфер и ввели несколько строк текста](image/16.png)

![Переключились в режим поиска](image/17.png)

![Нашли присутствующее в тексте слово](image/18.png)

![Переключились между результатами поиска](image/19.png)

![Перешли в режим поиска и замены, заменили все слова в тексте](image/20.png)

![Попробовали другой режим поиска. В отличие от первого он находит только первое попавшееся слово, а не все](image/21.png)

# Выводы

Познакомились с операционной системой Linux. Получили практические навыки работы с редактором Emacs.

