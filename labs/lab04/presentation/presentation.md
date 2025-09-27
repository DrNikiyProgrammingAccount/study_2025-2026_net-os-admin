---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 4
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

Приобретение практических навыков по установке и базовому конфигурированию HTTP-сервера Apache.

## Запуск сервера

![Запуск сервера](image/1.png){height=60%}

## Установка пакетов
![Установка пакетов](image/2.png){height=60%}

## /etc/httpd/conf/httpd.conf
![/etc/httpd/conf/httpd.conf](image/3.png){height=60%}

## /etc/httpd/conf/magic

![/etc/httpd/conf/magic](image/4.png){height=60%}

## /etc/httpd/conf.d/autoindex.conf

![/etc/httpd/conf.d/autoindex.conf](image/5.png){height=60%}

## /etc/httpd/conf.d/manual.conf

![/etc/httpd/conf.d/manual.conf](image/6.png){height=60%}

## /etc/httpd/conf.d/userdir.conf

![/etc/httpd/conf.d/userdir.conf](image/7.png){height=60%}

## /etc/httpd/conf.d/fcgid.conf

![/etc/httpd/conf.d/fcgid.conf](image/8.png){height=60%}

## /etc/httpd/conf.d/ssl.conf

![/etc/httpd/conf.d/ssl.conf](image/9.png){height=60%}

## /etc/httpd/conf.d/welcome.conf

![/etc/httpd/conf.d/welcome.conf](image/10.png){height=60%}

## Настройка firewall

![Настройка firewall](image/11.png){height=60%}

## journalctl

![journalctl](image/12.png){height=60%}

## запуск службы httpd

![запуск службы httpd](image/13.png){height=60%}

## Лог об успешном запуске

![Лог об успешном запуске](image/14.png){height=60%}

## Запуск клиента

![Запуск клиента](image/15.png){height=60%}

## Страница по умолчанию

![Страница по умолчанию](image/16.png){height=60%}

## /var/log/httpd/error_log

![/var/log/httpd/error_log](image/17.png){height=60%}

## /var/log/httpd/access_log

![/var/log/httpd/access_log](image/18.png){height=60%}

## Остановка службы named

![Остановка службы named](image/19.png){height=60%}

## Файл зоны /var/named/master/fz/nsandryushin

![Файл зоны /var/named/master/fz/nsandryushin](image/20.png){height=60%}

## Файл зоны /var/named/master/rz/192.168.1

![Файл зоны /var/named/master/rz/192.168.1](image/21.png){height=60%}

## Удаление журналов

![Удаление журналов](image/22.png){height=60%}

## Создание конфигурационных файлов

![Создание конфигурационных файлов](image/23.png){height=60%}

## server.nsandryushin.net

![server.nsandryushin.net](image/24.png){height=60%}

## www.nsandryushin.net

![www.nsandryushin.net](image/25.png){height=60%}

## Файлы index.html

![Файлы index.html](image/26.png){height=60%}

## Обновление меток и перезапуск службы

![Обновление меток и перезапуск службы](image/27.png){height=60%}

## server.nsandryushin.net

![server.nsandryushin.net](image/28.png){height=60%}

## www.nsandryushin.net

![www.nsandryushin.net](image/29.png){height=60%}

## Обновление конфигурации vagrant

![Обновление конфигурации vagrant](image/30.png){height=60%}

## Скрипт http.sh

![Скрипт http.sh](image/31.png){height=60%}

## Vagrantfile

![Vagrantfile](image/32.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки работы и настройки http сервера
