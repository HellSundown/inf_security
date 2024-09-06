---
## Front matter
title: "Проект. Этап №1


Информационная безопасность"
subtitle: "Установка Kali Linux"
author: "Выполнила: Павлова Полина Алексеевна, 


НПИбд-02-21, 1032212967"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Установка Kali Linux

# Выполнение лабораторной работы

## Установка операционной системы на виртуальную машину

### Virtual Box

![(рис. 1. Общие настройки)](image/image1.png){ #fig:001 width=70% height=70% }

![(рис. 2. Имя и путь  ОС)](image/image2.png){ #fig:002 width=70% height=70% }

![(рис. 3. Размер пямяти и число процессоров)](image/image3.png){ #fig:003 width=70% height=70% }

![(рис. 4. Виртуальный жесткий диск)](image/image4.png){ #fig:004 width=70% height=70% }

![(рис. 5. Итог настроек)](image/image5.png){ #fig:005 width=70% height=70% }

![(рис. 6. Язык установки)](image/image6.png){ #fig:006 width=70% height=70% }

![(рис. 7. Выбор региона)](image/image7.png){ #fig:007 width=70% height=70% }

![(рис. 8. Выбор раскладки)](image/image8.png){ #fig:008 width=70% height=70% }

![(рис. 9. hostname)](image/image9.png){ #fig:009 width=70% height=70% }

![(рис. 10. Domain name)](image/image10.png){ #fig:010 width=70% height=70% }

![(рис. 11. Создание пользователя)](image/image11.png){ #fig:011 width=70% height=70% }

![(рис. 12. Установка пароля для пользователя)](image/image12.png){ #fig:012 width=70% height=70% }

![(рис. 13. Установка ОС)](image/image12.png){ #fig:012 width=70% height=70% }

# Список литературы. Библиография

[1] Документация по Virtual Box: https://www.virtualbox.org/wiki/Documentation
