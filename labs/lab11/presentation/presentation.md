---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 11
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

Приобретение практических навыков по настройке удалённого доступа к серверу с помощью SSH

## Смена пароля для root

![Смена пароля для root](image/1.png){height=60%}

## journalctl

![journalctl](image/2.png){height=60%}

## Авторизация под root по ssh

![Авторизация под root по ssh](image/3.png){height=60%}

## Лог авторизации

![Лог авторизации](image/4.png){height=60%}

## Редактирование /etc/ssh/sshd_config

![Редактирование /etc/ssh/sshd_config](image/5.png){height=60%}

## Перезапуск sshd

![Перезапуск sshd](image/6.png){height=60%}

## Повторная авторизация под root по ssh

![Повторная авторизация под root по ssh](image/7.png){height=60%}

## Лог авторизации

![Лог авторизации](image/8.png){height=60%}

## Авторизация под своей учётной записью по ssh

![Авторизация под своей учётной записью по ssh](image/9.png){height=60%}

## Добавление белого списка пользователей

![Добавление белого списка пользователей](image/10.png){height=60%}

## Перезапуск sshd

![Перезапуск sshd](image/11.png){height=60%}

## Провальная авторизация под своей учётной записью

![Провальная авторизация под своей учётной записью](image/12.png){height=60%}

## Добавление нового пользователя в белый

![Добавление нового пользователя в белый](image/13.png){height=60%}

## Успешная авторизация под своей учётной записью

![Успешная авторизация под своей учётной записью](image/14.png){height=60%}

## Добавление портов

![Добавление портов](image/15.png){height=60%}

## Статус службы sshd

![Статус службы sshd](image/16.png){height=60%}

## Лог с SElinux

![Лог с SElinux](image/17.png){height=60%}

## Настройка SElinux и firewall

![Настройка SElinux и firewall](image/18.png){height=60%}

## Проверка портов

![Проверка портов](image/19.png){height=60%}

## Включение авторизации по ключу

![Включение авторизации по ключу](image/20.png){height=60%}

## Перезапуск sshd

![Перезапуск sshd](image/21.png){height=60%}

## Формирование ключа для авторизации

![Формирование ключа для авторизации](image/22.png){height=60%}

## Подключение без пароля

![Подключение без пароля](image/23.png){height=60%}

## Список служб, использующих TCP

![Список служб, использующих TCP](image/24.png){height=60%}

## Перенаправление порта

![Перенаправление порта](image/25.png){height=60%}

## Список служб

![Список служб](image/26.png){height=60%}

## Результат переадресации

![Результат переадресации](image/27.png){height=60%}

## Запуск консольных утилит по ssh

![Запуск консольных утилит по ssh](image/28.png){height=60%}

## Включение форвардинга иксов

![Включение форвардинга иксов](image/29.png){height=60%}

## Перезапуск sshd

![Перезапуск sshd](image/30.png){height=60%}

## Запуск графического приложения по ssh

![Запуск графического приложения по ssh](image/31.png){height=60%}

## Результат запуска графического приложения по ssh

![Результат запуска графического приложения по ssh](image/32.png){height=60%}

## Сохранение в vagrant

![Сохранение в vagrant](image/33.png){height=60%}

## ssh.sh

![ssh.sh](image/34.png){height=60%}

## Vagrantfile

![Vagrantfile](image/35.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки настройки ssh, форвардинга через него и настройки авторизации
