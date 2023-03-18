---
## Front matter
title: "Отчёт ко второму этапу индивидуального проекта"
subtitle: "Операционные системы"
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

Продолжить работы со своим сайтом. Редактировать его в соответствие с требованиями. Добавить данные о себе на сайт.

# Задание

1. Разместить фотографию владельца сайта.
2. Разместить краткое описание владельца сайта (Biography).
3. Добавить информацию об интересах (Interests).
4. Добавить информацию об образовании (Education).
5. Сделать пост по прошедшей неделе.
6. Добавить пост на тему по выбору: Управление версиями. Git. Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением. Мы будем создавать статический сайт, для этого нам понадобится Hugo. Hugo — генератор статических страниц для интернета.

Мы продолжаем работу с Hugo. Будем учиться редактировать данные о себе и писать посты.



# Выполнение лабораторной работы

Размещаем свою фотографию на сайте, краткое описание владельца сайта (Biography), добавляем информацию об интересах (Interests) и информацию об образовании (Education). (рис. @fig:001), (рис. @fig:002)

![Изменение в файле данных о себе](image/к1.jpg){#fig:001 width=70%}

![Результат на сайте на сайте](image/к2.jpg){#fig:002 width=70%}

Добавим пост на тему по выбору. Я выбрала тему: Управление версиями. Git. (рис. @fig:003)

![Написание информации про пост](image/к3.jpg){#fig:003 width=70%}

Сделаем пост по прошедшей неделе. (рис. @fig:004), (рис. @fig:005)

![Написание информации про пост о прошедшей недели](image/к4.jpg){#fig:004 width=70%}

![Результат на сайте](image/к5.jpg){#fig:005 width=70%}

# Выводы

В процессе выполнения второго этапа индивидуального проекта я научилась редактировать данные о себе, а также писать посты и добывлять их на сайт.

# Список литературы{.unnumbered}

Что такое сайт (простыми словами)l [Электронный ресурс]. URL: https:
//uguide.ru/chto-takoe-sajt-prostymi-slovami.
