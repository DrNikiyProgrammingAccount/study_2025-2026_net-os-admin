---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 3
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

Приобретение практических навыков по установке и конфигурированию DHCP-сервера.

## Запуск сервера

![Запуск сервера](image/1.png){height=60%}

## Установка kea

![Установка kea](image/2.png){height=60%}

## Бекап конфига

![Бекап конфига](image/3.png){height=60%}

## Редактирование конфига

![Редактирование конфига](image/4.png){height=60%}

## Настройка подсети

![Настройка подсети](image/5.png){height=60%}

## Установка интерфейса

![Установка интерфейса](image/6.png){height=60%}

## Загрузка конфига

![Загрузка конфига](image/7.png){height=60%}

## Перезагрузка даемонов

![Перезагрузка даемонов](image/8.png){height=60%}

## Редактирование fz

![Редактирование fz](image/9.png){height=60%}

## rz

![rz](image/10.png){height=60%}

## Пинг dhcp

![Пинг dhcp](image/11.png){height=60%}

## firewall и selinux

![firewall и selinux](image/12.png){height=60%}

## Логи сервера 

![Логи сервера](image/13.png){height=60%}

## Запуск dhcp

![Запуск dhcp](image/14.png){height=60%}

## Сверка по логу

![Сверка по логу](image/15.png){height=60%}

## Скрипт для клиента 

![Скрипт для клиента](image/16.png){height=60%}

## Vagrantfile

![Vagrantfile](image/17.png){height=60%}

## Запуск клиента

![Запуск клиента](image/18.png){height=60%}

## ifconfig

![ifconfig](image/19.png){height=60%}

## Таблица с назначениями

![Таблица с назначениями](image/20.png){height=60%}

## Ключ sha512 

![Ключ sha512](image/21.png){height=60%}

## Добавление ключа

![Добавление ключа](image/22.png){height=60%}

## Обновление файла

![Обновление файла](image/23.png){height=60%}

## Применение изменений

![Применение изменений](image/24.png){height=60%}

## Порядок монтирования 

![Порядок монтирования](image/25.png){height=60%}

## Смена прав файла

![Смена прав файла](image/26.png){height=60%}

## Изменение конфигурации

![Изменение конфигурации](image/27.png){height=60%}

## Перезапуск ddns

![Перезапуск ddns](image/28.png){height=60%}

## Добавление информации о ddns

![Добавление информации о ddns](image/29.png){height=60%}

## Перезапуск службы с приминением изменений 

![Перезапуск службы с приминением изменений](image/30.png){height=60%}

## Обновление данных 

![Обновление данных](image/31.png){height=60%}

## dig 

![dig](image/32.png){height=60%}

## Перенос конфигурации

![Перенос конфигурации](image/33.png){height=60%}

## Скрипт vagrant

![Скрипт vagrant](image/34.png){height=60%}

## Vagtantfile

![Vagtantfile](image/35.png){height=60%}

## Выводы

в результате выполнения работы были получены навыки настройки dhcp
