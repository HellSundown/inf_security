---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Настройка рабочего пространства для лабораторных работ"
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Настроить рабочее пространство для лабораторных работ, приобрести практические навыки
установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

## Установка и конфигурация операционной системы на виртуальную машину

### Virtual Box

![(рис. 1. Общие настройки)](image/image1.png){ #fig:001 width=70% height=70% }

![(рис. 2. Имя и путь  ОС)](image/image2.png){ #fig:002 width=70% height=70% }

![(рис. 3. Размер пямяти и число процессоров)](image/image3.png){ #fig:003 width=70% height=70% }

![(рис. 4. Виртуальный жесткий диск)](image/image4.png){ #fig:004 width=70% height=70% }

![(рис. 5. Итог настроек)](image/image5.png){ #fig:005 width=70% height=70% }

![(рис. 6. Носители)](image/image6.png){ #fig:006 width=70% height=70% }

![(рис. 7. Стартовое меню установки)](image/image7.png){ #fig:007 width=70% height=70% }

![(рис. 8. Server with GUI)](image/image8.png){ #fig:008 width=70% height=70% }

![(рис. 9. Enable KDUMP)](image/image9.png){ #fig:009 width=70% height=70% }

![(рис. 10. Root password)](image/image10.png){ #fig:010 width=70% height=70% }

![(рис. 11. Итоговое меню установки)](image/image11.png){ #fig:011 width=70% height=70% }

![(рис. 12. Успешное завершение установки и перезагрузка системы)](image/image12.png){ #fig:012 width=70% height=70% }

### Переход в ОС Linux

![(рис. 13. успешное создание пользователя)](image/image13.png){ #fig:013 width=70% height=70% }

![(рис. 14. Подключение гостевых настроек)](image/image14.png){ #fig:014 width=70% height=70% }

### Домашнее задание

![(рис. 15. dmesg)](image/image15.png){ #fig:015 width=70% height=70% }

![(рис. 16. dmesg | less, версия ядра линукс, частота процессора, модель процессора)](image/image16.png){ #fig:016 width=70% height=70% }

![(рис. 17. Объем доступной оперативной памяти)](image/image17.png){ #fig:017 width=70% height=70% }

![(рис. 18. Тип обнаруженного гипервизора)](image/image18.png){ #fig:018 width=70% height=70% }

![(рис. 19. Тип файловой системы корневого раздела)](image/image19.png){ #fig:019 width=70% height=70% }

![(рис. 20. Последовательность монтирования файловых систем)](image/image20.png){ #fig:020 width=70% height=70% }

# Вывод

Были настроено рабочее пространство для лабораторных работ, приобретены практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы. Библиография

[1] Документация по Virtual Box: https://www.virtualbox.org/wiki/Documentation
