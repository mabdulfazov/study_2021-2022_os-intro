---
## Front matter
lang: ru-RU
title: Анализ файловой системы Linux. Команды для работы с файлами и каталогами
author: Мансур А. о. Абдулфазов\inst{1,3}
        Группа НФИбд-01-21
date: 4 Мая, 2021, Россия, Москва

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---




## Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке исполь- зования диска и обслуживанию файловой системы.


## Выполнение лабораторной работы

1. Выполните все примеры, приведённые в первой части описания лабораторной работы. (рис. 1)


![Выполнение всех примеров](./images_lab5/1.png){#fig:001 width=70%}


##


2. Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите его equipment. (рис. 2)


![Копирование файла с помощью команды  cp](./images_lab5/2.png){#fig:002 width=70%}


##


3. В домашнем каталоге создал директорию~/ski.plases. Переместил файл equipment  в каталог ~/ski.plases. (рис. 3)

![Перемещение файла с помощью команды mv](./images_lab5/3.png){#fig:003 width=70%}


##


4.  В домашнем каталоге создайте директорию~/ski.plases. Переместите файл equipment  в каталог ~/ski.plases. Переименуйте файл ~/ski.plases/equipment в ~/ski.plases/equiplist. (рис. 4)


![Создание каталога с помощью команды mkdir. Перемещение и переименование файлов с помощью команды mv](./images_lab5/4.png){#fig:004 width=70%}


##


5. Создал в домашнем каталоге файл abc1 и скопировал его в каталог ~/ski.plases, назвал его equiplist2. (рис. 5)


![Создание файла с помощью команды touch и копирование его в каталог с помощью команды cp](./images_lab5/5.png){#fig:005 width=70%}


##


6.  Создал каталог с именем equipment в каталоге ~/ski.plases. Переместил файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment. (рис. 6)

![Создание каталога и перемещение файлов в этот каталог](./images_lab5/6.png){#fig:006 width=70%}


##


7. Создал и переместил каталог ~/newdir в каталог ~/ski.plases и назвал
его plans. (рис. 7)

![Создание каталога и перемещение его в другой каталог](./images_lab5/7.png){#fig:007 width=70%}


##


8.  С помощью команды chmod изменил права доступа, данные по заданию, к следующим файлам (рис. 8)

![Изменение прав доступа с помощью команды chmod](./images_lab5/8.png){#fig:008 width=70%}


##


9.  С помощью команды cat просмотрел содержимое файла /etc/password (рис. 9)

![Просмотр содержимого файла с помощью команды cat](./images_lab5/9.png){#fig:009 width=70%}


##


10. Скопировал файл ~/feathers в файл ~/file.old. Переместил файл ~/file.old в каталог ~/play. Скопировал каталог ~/play в каталог ~/fun. Переместил каталог ~/fun в каталог ~/play и назвал его games. (рис. 10)


![Копирование и перемещение файлов и каталогов с помощью команд cp и mv](./images_lab5/10.png){#fig:010 width=70%}


##


11. Лишил владельца файла ~/feathers права на чтение. Попытался просмотреть файл ~/feathers командой cat. Попытался скопировать файл ~/feathers. Дал владельцу файла ~/feathers право на чтение. (рис. 11)


![Изменение прав доступа владельца к файлу](./images_lab5/11.png){#fig:011 width=70%}


##


12. Лишил владельца каталога ~/play права на выполнение. Попытался перейти в каталог ~/play. Дал владельцу каталога ~/play право на выполнение. (рис. 12)


![Изменение прав доступа владельца к каталогу](./images_lab5/12.png){#fig:012 width=70%}


##


13. Прочитал man по командам mount, fsck, mkfs, kill (рис. 13, рис. 14, рис. 15, рис. 16)


![Справка по команде mount](./images_lab5/13.png){#fig:013 width=70%}


##


![Справка по команде fsck](./images_lab5/14.png){#fig:014 width=70%}


##


![Справка по команде mkfs](./images_lab5/15.png){#fig:015 width=70%}


##


![Справка по команде kill](./images_lab5/16.png){#fig:016 width=70%}



## Вывод

Ознакомился с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрёл практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

