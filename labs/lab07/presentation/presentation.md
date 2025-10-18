---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 7
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

Получить навыки настройки межсетевого экрана в Linux в части переадресации портов и настройки Masquerading.

## Запуск сервера

![Запуск сервера](image/1.png){height=60%}

## Копирование конфигурационного файла

![Копирование конфигурационного файла](image/2.png){height=60%}

## Редактирование файла /etc/firewalld/services/ssh-custom.xml

![Редактирование файла /etc/firewalld/services/ssh-custom.xml](image/3.png){height=60%}

## Список служб firewalld

![Список служб firewalld](image/4.png){height=60%}

## Списки служб

![Списки служб](image/5.png){height=60%}

## Добавление службы как активной

![Добавление службы как активной](image/6.png){height=60%}

## Форвардинг портов

![Форвардинг портов](image/7.png){height=60%}

## Подключение по ssh

![Подключение по ssh](image/8.png){height=60%}

## Включение перенаправления и маскарадинга

![Включение перенаправления и маскарадинга](image/9.png){height=60%}

## Проверка доступа в интернет

![Проверка доступа в интернет](image/10.png){height=60%}

## Сохранение конфигурации vagrant

![Сохранение конфигурации vagrant](image/11.png){height=60%}

## firewall.sh

![firewall.sh](image/12.png){height=60%}

## Vagrantfile

![Vagrantfile](image/13.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки работы с фаерволом и настройкой форвардинга и маскарадинга
