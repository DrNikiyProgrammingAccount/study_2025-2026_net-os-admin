---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 15
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

Получение навыков по работе с журналами системных событий

## Создание файла конфигурации на сервере

![Создание файла конфигурации на сервере](image/1.png){height=60%}

## Редактирование конфигурации rsyslog на сервере

![Редактирование конфигурации rsyslog на сервере](image/2.png){height=60%}

## Перезапуск службы и начало проверки портов

![Перезапуск службы и начало проверки портов](image/3.png){height=60%}

## Подтверждение прослушивания порта 514

![Подтверждение прослушивания порта 514](image/4.png){height=60%}

## Настройка firewall на сервере

![Настройка firewall на сервере](image/5.png){height=60%}

## Создание файла конфигурации на клиенте

![Создание файла конфигурации на клиенте](image/6.png){height=60%}

## Редактирование конфигурации rsyslog на клиенте

![Редактирование конфигурации rsyslog на клиенте](image/7.png){height=60%}

## Просмотр логов на сервере через tail

![Просмотр логов на сервере через tail](image/8.png){height=60%}

## Интерфейс Gnome System Monitor

![Интерфейс Gnome System Monitor](image/9.png){height=60%}

## Ручная установка lnav на сервере

![Ручная установка lnav на сервере](image/10.png){height=60%}

## Просмотр логов через lnav на сервере

![Просмотр логов через lnav на сервере](image/11.png){height=60%}

## Установка и запуск lnav на клиенте

![Установка и запуск lnav на клиенте](image/12.png){height=60%}

## Просмотр логов через lnav на клиенте

![Просмотр логов через lnav на клиенте](image/13.png){height=60%}

## Подготовка файлов для автоматизации сервера

![Подготовка файлов для автоматизации сервера](image/14.png){height=60%}

## Скрипт provisioning для сервера

![Скрипт provisioning для сервера](image/15.png){height=60%}

## Подготовка файлов для автоматизации клиента

![Подготовка файлов для автоматизации клиента](image/16.png){height=60%}

## Скрипт provisioning для клиента

![Скрипт provisioning для клиента](image/17.png){height=60%}

## Настройка Vagrantfile

![Настройка Vagrantfile](image/18.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки использования журналов системных событий
