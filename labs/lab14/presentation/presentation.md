---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 14
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

Приобретение навыков настройки доступа групп пользователей к общим ресурсам по протоколу SMB.

## Установка пакетов Samba на сервере

![Установка пакетов Samba на сервере](image/1.png){height=60%}

## Создание пользователей, групп и каталога

![Создание пользователей, групп и каталога](image/2.png){height=60%}

## Настройка smb.conf

![Настройка smb.conf](image/3.png){height=60%}

## Проверка конфигурации

![Проверка конфигурации](image/4.png){height=60%}

## Запуск службы SMB

![Запуск службы SMB](image/5.png){height=60%}

## Проверка доступа через smbclient

![Проверка доступа через smbclient](image/6.png){height=60%}

## Файл конфигурации службы samba.xml

![Файл конфигурации службы samba.xml](image/7.png){height=60%}

## Настройка Firewall и прав доступа

![Настройка Firewall и прав доступа](image/8.png){height=60%}

## Настройка контекста SELinux

![Настройка контекста SELinux](image/9.png){height=60%}

## Настройка boolean SELinux

![Настройка boolean SELinux](image/10.png){height=60%}

## Создание тестового файла и SMB-пользователя

![Создание тестового файла и SMB-пользователя](image/11.png){height=60%}

## Установка пакетов на клиенте

![Установка пакетов на клиенте](image/12.png){height=60%}

## Просмотр samba-client.xml

![Просмотр samba-client.xml](image/13.png){height=60%}

## Настройка окружения на клиенте

![Настройка окружения на клиенте](image/14.png){height=60%}

## Настройка рабочей группы на клиенте

![Настройка рабочей группы на клиенте](image/15.png){height=60%}

## Проверка списка ресурсов сервера с клиента

![Проверка списка ресурсов сервера с клиента](image/16.png){height=60%}

## Ручное монтирование и проверка записи

![Ручное монтирование и проверка записи](image/17.png){height=60%}

## Создание файла учетных данных

![Создание файла учетных данных](image/18.png){height=60%}

## Содержимое файла smbusers

![Содержимое файла smbusers](image/19.png){height=60%}

## Редактирование fstab

![Редактирование fstab](image/20.png){height=60%}

## Проверка автоматического монтирования

![Проверка автоматического монтирования](image/21.png){height=60%}

## Список файлов в общем ресурсе

![Список файлов в общем ресурсе](image/22.png){height=60%}

## Подготовка каталогов provision на сервере

![Подготовка каталогов provision на сервере](image/23.png){height=60%}

## Скрипт smb.sh для сервера

![Скрипт smb.sh для сервера](image/24.png){height=60%}

## Подготовка каталогов provision на клиенте

![Подготовка каталогов provision на клиенте](image/25.png){height=60%}

## Скрипт smb.sh для клиента

![Скрипт smb.sh для клиента](image/26.png){height=60%}

## Обновленный Vagrantfile

![Обновленный Vagrantfile](image/27.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки настройки и использования Samba
