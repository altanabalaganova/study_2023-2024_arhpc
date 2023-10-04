---
## Front matter
title: "Лабораторная работа номер 3"
subtitle: "Компьютерные науки и технологии программирования"
author: "Балаганова Алтана Владиславовна"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Задание

1. В соответствующем каталоге сделайте отчёт по лабораторной работе No 2 в формате
Markdown. В качестве отчёта необходимо предоставить отчёты в 3 форматах: pdf, docx
и md.
2. Загрузите файлы на github

# Выполнение лабораторной работы

1. Открыли терминал
2. Перешли в каталог курса сформированный при выполнении лабораторной работы
No2:
cd ~/work/study/2023-2024/"Архитектура компьютера"/arch-pc/
Обновите локальный репозиторий, скачав изменения из удаленного репозитория с помо-
щью команды
git pull
3. Перешли в каталог с шаблоном отчета по лабораторной работе No 3
cd ~/work/study/2023-2024/"Архитектура компьютера"/study_2023-2024_archpc/labs/lab03/report
4. Провели компиляцию шаблона с использованием Makefile. Для этого ввели ко-
манду make

![Название рисунка](Снимок экрана от 2023-10-04 12-55-58.png){#fig:001 width=70%}
Компиляция прошла успешно, сгенерировались файлы report.pdf и report.docx.
Открыли и проверили корректность полученных файлов.
5. Удалили полученные файлы с использованием Makefile. Для этого ввели команду
make clean
Проверили, что после этой команды файлы report.pdf и report.docx были удалены.
![Название рисунка](Снимок экрана от 2023-10-04 12-56-44.png){#fig:001 width=70%}
![Название рисунка](Снимок экрана от 2023-10-04 12-57-03.png){#fig:001 width=70%}

# Выводы

Освоили процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
