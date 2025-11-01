---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 9
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

Приобретение практических навыков по установке и простейшему конфигурированию POP3/IMAP-сервера

## Установка dovecot и telnet

![Установка dovecot и telnet](image/1.png){height=60%}

## Задавание протоколов для dovecot

![Задавание протоколов для dovecot](image/2.png){height=60%}

## /etc/conf.d/10-auth.conf

![/etc/conf.d/10-auth.conf](image/3.png){height=60%}

## /etc/conf.d/auth-system.conf.ext, driver для passwd

![/etc/conf.d/auth-system.conf.ext, driver для passwd](image/4.png){height=60%}

## /etc/conf.d/auth-system.conf.ext, driver для userdb

![/etc/conf.d/auth-system.conf.ext, driver для userdb](image/5.png){height=60%}

## /etc/dovecot/conf.d/10-mail.conf

![/etc/dovecot/conf.d/10-mail.conf](image/6.png){height=60%}

## postconf

![postconf](image/7.png){height=60%}

## Настройка firewall

![Настройка firewall](image/8.png){height=60%}

## Запуск служб

![Запуск служб](image/9.png){height=60%}

## Лог /var/log/maillog

![Лог /var/log/maillog](image/10.png){height=60%}

## mail и doveadm

![mail и doveadm](image/11.png){height=60%}

## Установка evolution

![Установка evolution](image/12.png){height=60%}

## Заполнение вкладки identity

![Заполнение вкладки identity](image/13.png){height=60%}

## Заполнение вкладки recieving email

![Заполнение вкладки recieving email](image/14.png){height=60%}

## Заполнение вкладки sending email

![Заполнение вкладки sending email](image/15.png){height=60%}

## account summary

![account summary](image/16.png){height=60%}

## Сертификат

![Сертификат](image/17.png){height=60%}

## Отправка первого письма

![Отправка первого письма](image/18.png){height=60%}

## Отправка второго письма

![Отправка второго письма](image/19.png){height=60%}

## Проверка отправки

![Проверка отправки](image/20.png){height=60%}

## Почтовый лог сервера

![Почтовый лог сервера](image/21.png){height=60%}

## mail и doveadm

![mail и doveadm](image/22.png){height=60%}

## Работа с почтой через telnet

![Работа с почтой через telnet](image/23.png){height=60%}

## Сохранение конфигурации на сервере

![Сохранение конфигурации на сервере](image/24.png){height=60%}

## mail.sh на сервере

![mail.sh на сервере](image/25.png){height=60%}

## mail.sh на клиенте

![mail.sh на клиенте](image/26.png){height=60%}

## Выводы

В результате выполнения лабораторной работы были получены навыки настройки и использования простейшего imap/pop3 сервера
