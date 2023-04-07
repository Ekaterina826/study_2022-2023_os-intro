---
## Front matter
title: "Отчёт к 3 этапу индивидуального проекта"
subtitle: "Дисциплина - операционные системы"
author: "Тимофеева Екатерина Николаевна"

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

Продолжить редактирование личного сайта. Добавить к сайту достижения. 

# Задание

1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору:
Легковесные языки разметки.
Языки разметки. LaTeX.
Язык разметки Markdown. 

# Теоретическое введение

                                                                      |
Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением [@Site:bash] . Мы создали статический сайт с помощью Hugo. Hugo — генератор статических страниц для интернета.

В этом этапе проекта мы научимся добавлять на сайт наши достижения. А также я напишу пост про язык разметки LaTex.

Язык разметки (markup language) – средство описания данных и метаданных, хранящихся в документе.


# Выполнение лабораторной работы

1. Добавить информацию о навыках (Skills). (рис. @fig:001)

![Добавление информации о навыках](image/1.jpg){#fig:001 width=70%}

2. Добавить информацию об опыте (Experience). (рис. @fig:002)

![Добавление информации об опыте](image/2.jpg){#fig:002 width=70%}

3. Добавить информацию о достижениях (Accomplishments). (рис. @fig:003)

![Добавление информации о достижениях](image/3.jpg){#fig:003 width=70%}

4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору:
Легковесные языки разметки.
Языки разметки. LaTeX.
Язык разметки Markdown. (рис. @fig:004)

![Написание постов](image/4.jpg){#fig:004 width=70%}



# Выводы

В процессе выполнения третьего этапа индивидуального проекта я продолжила редактирование сайта, научилась добавлять на сайт свои достижения, а также продолжила писать посты.

# Список литературы{.unnumbered}

1. Что такое сайт (простыми словами)l [Электронный ресурс]. URL: https:
//uguide.ru/chto-takoe-sajt-prostymi-slovami.
