---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "НКНбд-00-21"
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

#  Цель работы

- Научиться вычислять системы линейных уравнений, используя ПО Octave.

# Ход работы

1. Решили систему, используя метод Гаусса.(рис. [-@fig:001])

   ![Метод Гаусса](image/1.png){ #fig:001 width=70% }
   
2. Использовали левое деление. (рис. [-@fig:002])
   
   ![Левое Деление](image/2.png){ #fig:002 width=70% }

3. Использовали LU-разложение. (рис. [-@fig:003])

  ![LU-разложение](image/3.png){ #fig:003 width=70% }
  
4. Использовали LUP-разложение (рис. [-@fig:004])

  ![LUP-разложение](image/4.png){ #fig:004 width=70% }
  
# Выводы

Во время выполнения лабораторной работы мы научились решать системы линейных уравнений, используя Octave.

::: {#refs}
:::