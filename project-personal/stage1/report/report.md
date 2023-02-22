---
## Front matter
title: "Отчёт о выполнении индивидуального прокета"
subtitle: "Этап 1"
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

Ознакомиться с порядком действий при создании сайта. Создать свой сайт научного работника, используя готовый шаблон и следуя инструкциям из видео лекции.

# Задание

- Следовать инструкциям из видео лекции
- Создать персональный сайт, используя шаблон
- Создать отчёт и презентацию
- Загрузить скринкасты на видео хостинг
- Представить работу на сайте ТУИС

# Выполнение лабораторной работы

![Скачиваем исполняемы файл, необходимый для создания сайта](image/1.png)

![Распаковываем скачанный архив](image/2.png)

![Меняем путь к файлу hugo на ~/bin/](image/3.png)

![Копируем репозиторий сайта к себе на github, называем его блог](image/4.png)

![Рекурсивно клонируем репозиторий blog в каталог курса](image/5.png)

![Проверяем корректность выполненных действий с помощью команды ls -l](image/6.png)

![Запускаем исполняемый файл hugo, указывая путь к файлу](image/7.png)

![Рекурсивно удалили каталог public](image/8.png)

![После повторного запуска исполняемого файла открывается сайт с ненужным нам шаблоном на синем фоне](image/9.png)

![Переходим в каталог ~/work/blog/, открываем файл _index.md и удаляем первый блок](image/10.png)

![Проверяем, что шаблон на синем фоне удалился](image/11.png)

![Создаём новый репозиторий с именем Alchemicael.github.io](image/12.png)

![Клонируем его в каталог ~/work](image/13.png)

![Проверяем корректность выполненных действий](image/14.png)

![Переходим в каталог Alchemicael.github.io и переключаемся на новую ветку с именем 'main'](image/15.png)

![Создаём пустой файл README.md и загружаем его на github](image/16.png)

![Проверяем, что файл загружен правильно](image/17.png)

![Переходим в каталог ~/work/blog и клонируем ветку Alchemicael.github.io из репозитория, меняя её название на public](image/18.png)

![Из-за некорректности клонирования открываем файл .gitignore через MidnightCommander и комментируем его строчку 'public/'](image/19.png)

![С помощью команды cat проверяем корректность выполненных действий](image/20.png)

![Повторно клонируем ветку Alchemicael.github.io из репозитория, меняя её название на public](image/21.png)

![С помощью команды git remote -v убедились, что репозиторий Alchemicael.github.io привязан к каталогу public](image/22.png)

![Загрузили файлы на github](image/23.png)

![Скопировали ссылку на наш новый сайт и проверили его работу](image/24.png)

# Выводы

Ознакомились с порядком действий при создании сайта. Создали персональный сайт научного работника, используя готовый шаблон и следуя инструкциям из видео лекции.


