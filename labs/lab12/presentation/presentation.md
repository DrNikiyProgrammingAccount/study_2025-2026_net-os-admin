---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 12
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

Получение навыков по управлению системным временем и настройке синхронизации времени

## Вывод команды timedatectl на сервере

![Вывод команды timedatectl на сервере](image/1.png){height=60%}

## Просмотр свойств времени с помощью timedatectl show

![Просмотр свойств времени с помощью timedatectl show](image/2.png){height=60%}

## Вывод команды timedatectl на клиенте

![Вывод команды timedatectl на клиенте](image/3.png){height=60%}

## Эксперименты с параметрами команды date на сервере

![Эксперименты с параметрами команды date на сервере](image/4.png){height=60%}

## Просмотр системного времени на клиенте

![Просмотр системного времени на клиенте](image/5.png){height=60%}

## Просмотр аппаратного времени на сервере

![Просмотр аппаратного времени на сервере](image/6.png){height=60%}

## Просмотр аппаратного времени на клиенте

![Просмотр аппаратного времени на клиенте](image/7.png){height=60%}

## Просмотр источников времени на сервере

![Просмотр источников времени на сервере](image/8.png){height=60%}

## Просмотр источников времени на клиенте

![Просмотр источников времени на клиенте](image/9.png){height=60%}

## Настройка доступа к NTP-серверу для локальной сети

![Настройка доступа к NTP-серверу для локальной сети](image/10.png){height=60%}

## Перезапуск службы и настройка Firewall на сервере

![Перезапуск службы и настройка Firewall на сервере](image/11.png){height=60%}

## Настройка клиента на использование локального NTP-сервера

![Настройка клиента на использование локального NTP-сервера](image/12.png){height=60%}

## Перезапуск службы chronyd на клиенте

![Перезапуск службы chronyd на клиенте](image/13.png){height=60%}

## Проверка источников времени на сервере

![Проверка источников времени на сервере](image/14.png){height=60%}

## Проверка источников времени на клиенте

![Проверка источников времени на клиенте](image/15.png){height=60%}

## Просмотр детальной информации о синхронизации на сервере

![Просмотр детальной информации о синхронизации на сервере](image/16.png){height=60%}

## Vagrant

![Vagrant](image/17.png){height=60%}

## Содержимое скрипта настройки ntp.sh для сервера

![Содержимое скрипта настройки ntp.sh для сервера](image/18.png){height=60%}

## Vagrant

![Vagrant](image/19.png){height=60%}

## Содержимое скрипта настройки ntp.sh для клиента

![Содержимое скрипта настройки ntp.sh для клиента](image/20.png){height=60%}

## Vagrantfile

![Vagrantfile](image/21.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки настройки системного времени и ntp синхронизации
