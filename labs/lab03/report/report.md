---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Архитектура вычислительных систем"
author: "Виктория Тиграновна Бекназарова"

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
Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown


# Задание

Здесь приводится описание задания в соответствии с рекомендациями
методического пособия и выданным вариантом.


# Выполнение лабораторной работы

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. [-@fig:001])


1. Открываем терминал.


![Открытие терминала](image/1.png){#fig:001 width=95%}



2. Перейдем в каталог курса сформированный при выполнении лаборатор-
ной работы №2



![Переход в каталог курса сформированный при выполнении лабораторной работы №2](image/2.png){#fig:002 width=95%}



![Обновление локального репозитория](image/3.png){#fig:003 width=95%}




3. Перейдём в каталог с шаблоном отчёта по лабораторной работе №3



![Перейдём в каталог с шаблоном отчёта](image/4.png){#fig:004 width=95%}



4. Проведем компиляцию шаблона с использованием Makefile. 




![Проведём компиляцию шаблона с использованием Makefile](image/5.png){#fig:005 width=95%}





5. При успешной компиляции должны сгенерироваться файлы report.pdf и report.docx. 




![При успешной компиляции должны сгенерироваться файлы report.pdf и report.docx. ](image/6.png){#fig:006 width=95%}




6. Удалим полученный файлы с использованием Makefile. 



![Удаляем полученный файл с использованием Makefile](image/7.png){#fig:007 width=95%}



7. Проверим, что после этой команды файлы report.pdf и report.docx были удалены



![Проверяем, что после этой команды файлы report.pdf и report.docx были удалены](image/8.png){#fig:008 width=95%}




8. Откроем файл report.md c помощью любого текстового редактора, например gedit



![Откроем файлы](image/9.png){#fig:009 width=95%}


# Выводы


Я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown


