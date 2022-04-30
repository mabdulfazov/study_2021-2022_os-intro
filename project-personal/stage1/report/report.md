---
# Front matter
lang: ru-RU
title: "Индивидуальный проект"
subtitle: "Этап 1"
author: "Абдулфазов Мансур Али оглы"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty =20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---



# Задание 


Размещение на _Github pages_ заготовки для персонального сайта.
    
  * Установить необходимое программное обеспечение.
  * Скачать шаблон темы сайта
  * Разместить его на хостинге git.
  * Установить параметр для _URLs_ сайта.
  * Разместить заготовку сайта на _Github pages_.


# Выполнение лабораторной работы

1.  Скачал шаблон темы сайта в свой репозиторий. (рис.1)

![Скачивание шаблона темы сайта](./images_st1/1.png){ #fig:001 width=70% }


2.  Создал дополнительный репозиторий для статик файлов. (рис.2)

![Создание дополнительного репозитория](./images_st1/2.png){ #fig:002 width=70% }


3.  Скачал оба репозитория на своё устройство. (рис.3)

![Клонирование репозиториев](./images_st1/3.png "Клонирование репозиториев"){ #fig:003 width=70% }


4.  Добавил сабмодуль для своего сайта. (рис.4)

![Добавление сабмодуля](./images_st1/4.png){ #fig:004 width=70% }


5. Создал сайт с помощью команды hugo. (рис.5)

![Создание сайта](./images_st1/5.png){ #fig:005 width=70% }


6.  Сохранил все изменения в локальном репозитории и отправил их в центральный репозиторий. (рис.6)

![Сохранение изменений](./images_st1/6.png "Сохранение изменений"){ #fig:006 width=70% }



7.  Продемонстрировал результат работы. (рис.7)

![Демонстрация сайта](./images_st1/7.png "Демонстрация сайта"){ #fig:007 width=70% }


# Вывод

Получил первоначальные знания по использованию генератора статических сайтов  Hugo. Обрёл базовые навыки для созданияя собственного сайта.