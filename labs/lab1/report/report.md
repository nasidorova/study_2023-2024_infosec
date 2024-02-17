!!)10---
## Front matter
title: "Отчёт по лабораторной работе 1"
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
author: "Сидорова Наталья Андреевна"

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

Целью данной работы является приобретение практических навыков
установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.


# Выполнение лабораторной работы

Создала виртуальную машину, версия Debian(64-bit) (рис. [-@fig:001]).

![Версия машины](image/fig:001.jpg){#fig:001 width=70%}

Настроила основную память машины (рис. [-@fig:002]).

![Основная память](image/fig:002.jpg){#fig:002 width=70%}

Настроила виртуальный жесткий диск (рис. [-@fig:003]).

![Виртуальный жесткий диск](image/fig:003.jpg){#fig:003 width=70%}

Добавила оптический привод (рис. [-@fig:004]).

![Оптический привод](image/fig:004.jpg){#fig:004 width=70%}

Выбрала базовое окружение и дополнение (рис. [-@fig:005]).

![Выбор программ](image/fig:005.jpg){#fig:005 width=70%}

Добавила host name (рис. [-@fig:006]).

![Host name](image/fig:006.jpg){#fig:006 width=70%}

Добавила пароль для администратора (рис. [-@fig:007]).

![Root password](image/fig:007.jpg){#fig:007 width=70%}

Создала пользователя (рис. [-@fig:008]).

![Пользователь](image/fig:008.jpg){#fig:008 width=70%}

Полностью настроила Rocky Linux (рис. [-@fig:009]).

![Настройки машины](image/fig:009.jpg){#fig:009 width=70%}

Ввела в терминал команду dsmeg (рис. [-@fig:010]).

![Вывод команды](image/fig:010.jpg){#fig:010 width=70%}

Выполнение дз (рис. [-@fig:011]).

![ДЗ 1 часть](image/fig:011.jpg){#fig:011 width=70%}

(рис. [-@fig:012]).

![ДЗ 2 часть](image/fig:012.jpg){#fig:012 width=70%}

# Выводы

В ходе лабораторной работы я установила новую виртуальную машину, произвела первоначальные настройки и познакомилась с командой dsmeg.

# Список литературы{.unnumbered}

::: {#refs}
:::
