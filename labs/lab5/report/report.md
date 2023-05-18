---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "НКНбд-01-21"
author: "Самигуллин Эмиль Артурович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
lofTitle: "Цель Работы"
lotTitle: "Ход Работы"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Продолжение изучения Octave для решения задач.

# Ход работы

1. Подгонка полиномиальной кривой (рис. [-@fig:001])

   ![Подгонка полиномиальной кривой](image/1.png){ #fig:001 width=70% }

2. Построения уравнения вида y = ax^2 + bx + c (рис. [-@fig:002])

   ![уравнения вида y = ax^2 + bx + c](image/2.png){ #fig:002 width=70% }

3. Матричное вращение (рис. [-@fig:003])

   ![Вращение](image/3.png){ #fig:003 width=70% }

4. Матричное отражение (рис. [-@fig:004])

   ![Отражение](image/4.png){ #fig:004 width=70% }

5. Матричное дилатация (рис. [-@fig:005])

   ![Дилатация](image/5.png){ #fig:005 width=70% }
   

::: {#refs}
:::
