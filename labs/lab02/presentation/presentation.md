---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 2
author:
  - Андрюшин Н. С. 
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 01 января 1970

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Андрюшин Никита Сергеевич
  * Студент
  * Российский университет дружбы народов

:::
::: {.column width="30%"}


:::
::::::::::::::

## Цель

Приобретение практических навыков по установке и конфигурированию DNS-сервера, усвоение принципов работы системы доменных имён.

## Запуск ВМ

Для начала запустим виртуальную машину через vagrant 

![Запуск ВМ](image/1.png){height=60%}

## Скачивание пакетов

Теперь скачаем пакет bind utils

![Скачивание пакетов](image/2.png){height=60%}

## dig ya.ru

Используем команду dig для проверки сервисов яндекса

![dig ya.ru](image/3.png){height=60%}

## Файлы конфигурации

Посморим на содержание файлов конфигурации dns в etc

![Файлы конфигурации](image/4.png){height=60%}

## named.ca

Просморим теперь файл named.ca

![named.ca](image/5.png){height=60%}

## named.localhost и named.loopback

Содержимое named.localhost и named.loopback

![named.localhost и named.loopback](image/6.png){height=60%}

## Запуск named

Запустим теперь named и осуществим снова dig yandex.ru 

![Запуск named](image/7.png){height=60%}

## eth0

Теперь настроим порт eth0

![eth0](image/8.png){height=60%}

## named.conf

Откроем и отредактируем named.conf

![named.conf](image/9.png){height=60%}

## Правила фаервола

Установим правила фаервола 

![Правила фаервола](image/10.png){height=60%}

## перемещение файла

Теперь переместим файл с настройкой конфига

![перемещение файла](image/11.png){height=60%}

## Редактирование файла

И отредактируем наш файл под наши параметры

![Редактирование файла](image/12.png){height=60%}

## Файл зон

То же самое сделаем с файлом зон 

![Файл зон](image/13.png){height=60%}

## Создание папок и настроек днс

Создадим папки с настройками днс 

![Создание папок и настроек днс](image/14.png){height=60%}

## nsandryushin.net

Отредактируем файл nsandryushin.net 

![nsandryushin.net](image/15.png){height=60%}

## Папка rz

Теперь посмотрим на файлы из папки rz 

![Папка rz](image/16.png){height=60%}

## Редактирование файла

Отредактируем следующим образом 

![Редактирование файла](image/17.png){height=60%}

## Selinux

Настроим Selinux 

![Selinux](image/18.png){height=60%}

## dig

Через dig попробуем подключиться к собственному днс 

![dig](image/19.png){height=60%}

## Конфиг вагрант

Оформим нашу работу как конфигурацию для вагранта

![Конфиг вагрант](image/20.png){height=60%}

## скрипт

И напишем скрипт для загрузки вагранта 

![скрипт](image/21.png){height=60%}

## vagrantfile

И в vagrantfile будем загружать этот скрипт

![vagrantfile](image/22.png){height=60%}

## Выводы

В результате выполнения работы были получены навыки настройки днс
