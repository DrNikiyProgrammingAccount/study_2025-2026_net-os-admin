---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 5
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

## Цель работы

Приобретение практических навыков по расширенному конфигурированию HTTP-сервера Apache в части безопасности и возможности использования PHP.

## Запуск сервера

![Запуск сервера](image/1.png){height=60%}

## Создание сертификата

![Создание сертификата](image/2.png){height=60%}

## Редактирование конфигурационного файла httpd

![Редактирование конфигурационного файла httpd](image/3.png){height=60%}

## www.nsandryushin.net.conf

![www.nsandryushin.net.conf](image/4.png){height=60%}

## Настройка фаервола

![Настройка фаервола](image/5.png){height=60%}

## Предупреждение

![Предупреждение](image/6.png){height=60%}

## Подключение к сайту

![Подключение к сайту](image/7.png){height=60%}

## Сертификат

![Сертификат](image/8.png){height=60%}

## Установка php

![Установка php](image/9.png){height=60%}

## Замена файла index.html на index.php

![Замена файла index.html на index.php](image/10.png){height=60%}

## Содержимое index.php

![Содержимое index.php](image/11.png){height=60%}

## Исправление настроек доступа

![Исправление настроек доступа](image/12.png){height=60%}

## Отображение сайта

![Отображение сайта](image/13.png){height=60%}

## Сохранение конфигурации

![Сохранение конфигурации](image/14.png){height=60%}

## http.sh

![http.sh](image/15.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки по конфигурированию HTTP-сервера Apache и https
