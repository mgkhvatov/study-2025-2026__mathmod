---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Работа с git"
author: "Хватов Максим Григорьевич"

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
lot: false # List of tables
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

Приобрести практические навыки работы с системой управления версиями Git.

# Теоретическое введение

Git — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года; координатор — Дзюн Хамано [@wiki:bash].

# Выполнение лабораторной работы

## Подготовка

Сначала настроим core.autocrlf с параметрами true и input, чтобы сделать все переводы строк текстовых файлов в главном репозитории одинаковыми, а затем настроим отображение unicode(рис. @fig:002).

![Настройка git](image/2.png){#fig:002 width=70%}

Далее создаю директорию, в которой будет проходить вся работа

![Настройка git](image/1.png){#fig:001 width=70%}

Делаю первый коммит и просматриваю статус 

![Настройка git](image/3.png){#fig:003 width=70%}

Вношу изменения в hello.html и просматриваю статус

![Настройка git](image/4.png){#fig:004 width=70%}

Добавляю измененный файл в индексацию

![Настройка git](image/5.png){#fig:002 width=70%}
![Настройка git](image/6.png){#fig:002 width=70%}

 Вношу другие изменения в файл hello.html и снова просматриваю его статус через команду gitt status

Просматриваю историю коммитов с помощью git log

![Настройка git](image/10.png){#fig:010 width=70%}

Переклчаюсь на коммит по его номеру хэша

![Настройка git](image/11.png){#fig:011 width=70%}

Переключаюсьна ветку мастер и просматриваю содержимое файла

![Настройка git](image/12.png){#fig:012 width=70%}

Создаю тэг v1 и v1-beta и переключаюсь между ними. Также просматриваю список тегов и логи коммитов, где указаны также тэги

![Настройка git](image/13.png){#fig:013 width=70%}
![Настройка git](image/14.png){#fig:014 width=70%}
![Настройка git](image/15.png){#fig:015 width=70%}

Сделал Сброс к коммиту с помощью reset и revert

![Настройка git](image/16.png){#fig:016 width=70%}
![Настройка git](image/17.png){#fig:017 width=70%}
![Настройка git](image/18.png){#fig:018 width=70%}
![Настройка git](image/19.png){#fig:019 width=70%}
![Настройка git](image/19.png){#fig:019 width=70%}
![Настройка git](image/20.png){#fig:020 width=70%}
![Настройка git](image/21.png){#fig:021 width=70%}
![Настройка git](image/22.png){#fig:022 width=70%}
![Настройка git](image/23.png){#fig:023 width=70%}
![Настройка git](image/24.png){#fig:024 width=70%}
![Настройка git](image/25.png){#fig:025 width=70%}
![Настройка git](image/26.png){#fig:026 width=70%}
![Настройка git](image/27.png){#fig:027 width=70%}
![Настройка git](image/28.png){#fig:028 width=70%}
![Настройка git](image/29.png){#fig:029 width=70%}
![Настройка git](image/30.png){#fig:030 width=70%}
![Настройка git](image/31.png){#fig:031 width=70%}
![Настройка git](image/32.png){#fig:032 width=70%}
![Настройка git](image/33.png){#fig:033 width=70%}
![Настройка git](image/34.png){#fig:034 width=70%}
![Настройка git](image/35.png){#fig:035 width=70%}
![Настройка git](image/36.png){#fig:036 width=70%}




# Выводы

В процессе выполнения данной лабораторной работы я приобрел практические навыки работы с Git.

# Список литературы{.unnumbered}

::: {#refs}
:::