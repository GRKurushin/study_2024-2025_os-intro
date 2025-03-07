---
## Front matter
title: "Отчёт по первому этапу итогового проекта"
subtitle: "Специальность: архитерктура компьютеров"
author: "Курушин Георгий Романович"

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

Размещение на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение персонального проекта

1. Установим hugo (рис. [-@fig:001]).

![Установка hugo](image/report1.png){#fig:001 width=70%}

2. Проверяем корректность установки, узнав версию hugo (рис. [-@fig:002]).

![Версия hugo](image/report2.png){#fig:002 width=70%}

3. Клонируем репозиторий с темой theme-academic-cv в новый репозиторий grkurushin.github.io (рис. [-@fig:003]).

![Новый репозиторий](image/report3.png){#fig:003 width=70%}

4. Заходим в настройки репозитория, переходим во вкладку Pages и открываем наш сайт (рис. [-@fig:004]).

![Сайт](image/report4.png){#fig:004 width=70%}

5. Клонируем свой репозиторий на компьютер (рис. [-@fig:005]).

![Клонирование репозитория](image/report5.png){#fig:005 width=70%}

6. Запускаем локальный сервер hugo, чтобы вносить изменения в live-режиме (рис. [-@fig:006]).

![Запуск локального сервера](image/report6.png){#fig:006 width=70%}

7. Пушим изменения в github (рис. [-@fig:007]).

![Пуш изменений](image/report7.png){#fig:007 width=70%}

# Выводы

Разместил на Github Pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

