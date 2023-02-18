---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
author: "Михаил Александрович Мелкомуков

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

Целью данной работы является ознакомление с процессом установки ОС Linux на виртуальную машину VirtualBox и настройкой основного программного обеспечения для дальнейшей работы.

# Задание

Настроить и создать виртуальную машину. Запустить виртуальную машину и установить систему. Научиться пользоваться ОС Linux на виртуальной машине. 

# Выполнение лабораторной работы

## Настройка и создание виртуальной машины

![Запустили VirtualBox](image/1.png)

![Проверили в свойствах VirtualBox месторасположение каталога для виртуальных машин](image/2.png)

![Сменили комбинацию для хост-клавиши](image/3.png)

![Начали создание новой виртуальной машины](image/4.png)

![Указали размер основной памяти виртуальной машины](image/5.png)

![Начали создавать виртуальный жёсткий диск](image/6.png)

![Указали тип виртуального жёсткого диска](image/7.png)

![Указали формат хранения](image/8.png)

![Задали размер диска](image/9.png)

![Создали новую виртуальную машину](image/10.png)

![Увеличили доступный объем видеопамяти до 128 МБ в настройках виртуальной машины](image/11.png)

![Добавили новый привод оптических дисков](image/12.png)

## Запуск виртуальной машины и установка системы

![Запустили виртуальную машину](image/13.png)

![Выбрали язык для использования в процессе установки](image/14.png)

![Окно настроек установки образа ОС](image/15.png)

![Выбрали раскладку клавиатуры](image/16.png)

![Выбрали место установки ОС](image/17.png)

![Установка Fedora завершена](image/18.png)

![Вышли из системы](image/19.png)

![Извлекли образ диска из дисковода](image/20.png)

![Запустили установленную в VirtualBox ОС](image/21.png)

![Указали имя пользователя](image/22.png)

![Установили пароль](image/23.png)

![Запустили терминал](image/24.png)

![Ввели команду для установки Midnight Commander](image/25.png)

![Запустили MC](image/26.png)

![Установили git](image/27.png)

![Установили Netwide Assembler](image/28.png)

# Домашнее задание

В окне терминала проанализировали последовательность загрузки системы и получили следующую информацию:

![Версия ядра Linux](image/29.png)

![Частота процессора](image/30.png)

![Модель процессора](image/31.png)

![Объём доступной оперативной памяти](image/32.png)

![Тип обнаруженного гипервизора](image/33.png)

![Тип файловой системы корневого раздела](image/34.png)

![Последовательность монтирования файловых систем](image/35.png)

# Контрольные вопросы

1. Какую информацию содержит учётная запись пользователя?
Имя пользователя (user name)
Индентификационный номер пользователя (UID)
Индентификационный номер группы (GID)
Пароль (password)
Полное имя (full name)
Домашний каталог (home directory)
Начальную оболочку (login shell)

2. Укажите команды терминала и приведите примеры:
pwd (Print Working Directory_ - определение текущего каталога
cd (Change Directory) -  смена каталога
ls (LiSt) - вывод списка файлов
mkdir (MaKe DIRectory) - создание пустых каталогов
touch - создание пустых файлов
rm (ReMove) - удаление файлов или каталогов
mv (MoVe) - перемещение файлов и каталогов
cp (CoPy) - копирование файлов и каталогов
cat - вывод содержимого файлов

3. Что такое файловая система? Приведите примеры с краткой характеристикой.
Файловая система - порядок,определяющий способ организации, хранения и наименования данных на носителях информации в компьютерах, а также в другом электронном оборудовании: цифровых фотоаппаратах, мобильных телефонах и т.п.
Примеры: файловая система FAT, файловая система NTFS

4. Как посмотреть, какие файловые системы подмонтированы в ОС?
DF - утилита, показывающая список всех файловых систем по имени устройства, сообщает их размер, занятое и свободное пространство и точки монтирования. При выполнении без аргумента команда mount выводит все подключённые данные.

5. Как удалить зависший процесс?
С помощью команды killall-killall ().

# Выводы

Ознакомление с процессом установки ОС Linux на виртуальную машину
VirtualBox и настройкой основного программного обеспечения для дальнейшей
работы прошло успешно.

