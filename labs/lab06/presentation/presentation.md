---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 6
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

Приобретение практических навыков по установке и конфигурированию системы управления базами данных на примере программного обеспечения MariaDB.

## Запуск сервера

![Запуск сервера](image/1.png){height=60%}

## Установка пакета

![Установка пакета](image/2.png){height=60%}

## /etc/my.cnf

![/etc/my.cnf](image/3.png){height=60%}

## auth_gssapi.cnf

![auth_gssapi.cnf](image/4.png){height=60%}

## mariadb-server.cnf

![mariadb-server.cnf](image/5.png){height=60%}

## provider_lz4.cnf

![provider_lz4.cnf](image/6.png){height=60%}

## spider.cnf

![spider.cnf](image/7.png){height=60%}

## client.cnf

![client.cnf](image/8.png){height=60%}

## mysql-clients.cnf

![mysql-clients.cnf](image/9.png){height=60%}

## provider_lzo.cnf

![provider_lzo.cnf](image/10.png){height=60%}

## enable_encryption.preset

![enable_encryption.preset](image/11.png){height=60%}

## provider_bzip2.cnf

![provider_bzip2.cnf](image/12.png){height=60%}

## provider_snappy.cnf

![provider_snappy.cnf](image/13.png){height=60%}

## Запуск mariadb

![Запуск mariadb](image/14.png){height=60%}

## Настройка БД

![Настройка БД](image/15.png){height=60%}

## Подключение к БД

![Подключение к БД](image/16.png){height=60%}

## Списки БД

![Списки БД](image/17.png){height=60%}

## Статус БД

![Статус БД](image/18.png){height=60%}

## Создание файла конфигурации

![Создание файла конфигурации](image/19.png){height=60%}

## Содержание файла utf8

![Содержание файла utf8](image/20.png){height=60%}

## Успешная смена кодировки

![Успешная смена кодировки](image/21.png){height=60%}

## Наполнение таблицы

![Наполнение таблицы](image/22.png){height=60%}

## Проверка прав доступа для нового пользователя

![Проверка прав доступа для нового пользователя](image/23.png){height=60%}

## Бэкапы и сохранение vagrant

![Бэкапы и сохранение vagrant](image/24.png){height=60%}

## mysql.sh

![mysql.sh](image/25.png){height=60%}

## Vagrantfile

![Vagrantfile](image/26.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки по конфигурированию HTTP-сервера Apache и https
