---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 13
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

Приобретение навыков настройки сервера NFS для удалённого доступа к ресурсам

## Установка пакета nfs-utils на сервере

![Установка пакета nfs-utils на сервере](image/1.png){height=60%}

## Создание каталога и открытие файла конфигурации

![Создание каталога и открытие файла конфигурации](image/2.png){height=60%}

## Настройка экспорта каталога

![Настройка экспорта каталога](image/3.png){height=60%}

## Настройка SELinux, запуск служб и настройка firewall

![Настройка SELinux, запуск служб и настройка firewall](image/4.png){height=60%}

## Установка nfs-utils на клиенте

![Установка nfs-utils на клиенте](image/5.png){height=60%}

## Ошибка подключения RPC при просмотре ресурсов на клиенте

![Ошибка подключения RPC при просмотре ресурсов на клиенте](image/6.png){height=60%}

## Остановка межсетевого экрана на сервере

![Остановка межсетевого экрана на сервере](image/7.png){height=60%}

## Успешный просмотр списка экспорта при отключенном фаерволе

![Успешный просмотр списка экспорта при отключенном фаерволе](image/8.png){height=60%}

## Запуск firewalld и просмотр открытых портов

![Запуск firewalld и просмотр открытых портов](image/9.png){height=60%}

## Службы rpcbind и mountd в выводе lsof

![Службы rpcbind и mountd в выводе lsof](image/10.png){height=60%}

## Просмотр UDP‑соединений с помощью lsof (начало вывода)

![Просмотр UDP‑соединений с помощью lsof (начало вывода)](image/11.png){height=60%}

## Просмотр UDP‑соединений с помощью lsof (окончание вывода)

![Просмотр UDP‑соединений с помощью lsof (окончание вывода)](image/12.png){height=60%}

## Настройка firewalld для работы служб mountd и rpc-bind

![Настройка firewalld для работы служб mountd и rpc-bind](image/13.png){height=60%}

## Проверка экспорта NFS‑ресурса командой showmount

![Проверка экспорта NFS‑ресурса командой showmount](image/14.png){height=60%}

## Монтирование каталога NFS на клиенте и проверка через mount

![Монтирование каталога NFS на клиенте и проверка через mount](image/15.png){height=60%}

## Настройка автоматического монтирования в /etc/fstab

![Настройка автоматического монтирования в /etc/fstab](image/16.png){height=60%}

## Проверка статуса remote-fs.target

![Проверка статуса remote-fs.target](image/17.png){height=60%}

## Проверка подключенных ресурсов командой mount

![Проверка подключенных ресурсов командой mount](image/18.png){height=60%}

## Bind-монтирование каталога веб-сервера на сервере NFS

![Bind-монтирование каталога веб-сервера на сервере NFS](image/19.png){height=60%}

## Проверка отображения нового каталога на клиенте

![Проверка отображения нового каталога на клиенте](image/20.png){height=60%}

## Редактирование файла /etc/exports на сервере

![Редактирование файла /etc/exports на сервере](image/21.png){height=60%}

## Экспорт каталогов командой exportfs

![Экспорт каталогов командой exportfs](image/22.png){height=60%}

## Проверка наличия каталога www на клиенте

![Проверка наличия каталога www на клиенте](image/23.png){height=60%}

## Добавление bind-монтирования в /etc/fstab

![Добавление bind-монтирования в /etc/fstab](image/24.png){height=60%}

## Повторный запуск exportfs на сервере

![Повторный запуск exportfs на сервере](image/25.png){height=60%}

## Проверка доступа к каталогу www на клиенте

![Проверка доступа к каталогу www на клиенте](image/26.png){height=60%}

## Подготовка каталога пользователя и bind-монтирование на сервере

![Подготовка каталога пользователя и bind-монтирование на сервере](image/27.png){height=60%}

## Настройка экспорта каталога пользователя

![Настройка экспорта каталога пользователя](image/28.png){height=60%}

## Настройка автоматического bind-монтирования в fstab

![Настройка автоматического bind-монтирования в fstab](image/29.png){height=60%}

## Проверка доступа к каталогу home на клиенте

![Проверка доступа к каталогу home на клиенте](image/30.png){height=60%}

## Проверка доступа к смонтированному каталогу пользователя на клиенте

![Проверка доступа к смонтированному каталогу пользователя на клиенте](image/31.png){height=60%}

## Проверка изменений в каталоге common на сервере

![Проверка изменений в каталоге common на сервере](image/32.png){height=60%}

## Подготовка каталогов и создание скрипта nfs.sh на сервере

![Подготовка каталогов и создание скрипта nfs.sh на сервере](image/33.png){height=60%}

## Содержимое скрипта автоматической настройки сервера

![Содержимое скрипта автоматической настройки сервера](image/34.png){height=60%}

## Создание скрипта nfs.sh на клиенте

![Создание скрипта nfs.sh на клиенте](image/35.png){height=60%}

## Скрипт настройки NFS на клиенте

![Скрипт настройки NFS на клиенте](image/36.png){height=60%}

## Добавление запуска скриптов в Vagrantfile

![Добавление запуска скриптов в Vagrantfile](image/37.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки работы с nfs и сетевыми хранилищами, а так же их настройка
