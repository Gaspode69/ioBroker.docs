---
translatedFrom: en
translatedWarning: Если вы хотите отредактировать этот документ, удалите поле «translatedFrom», в противном случае этот документ будет снова автоматически переведен
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/ru/adapterref/iobroker.hombot/README.md
title: ioBroker.hombot
hash: DwRKXKN9asmG7sZqS4HcJMOgWKUrIOQ4B0zUANzQ8xg=
---
![Количество установок](http://iobroker.live/badges/hombot-stable.svg)
![Версия NPM](http://img.shields.io/npm/v/iobroker.hombot.svg)
![Загрузки](https://img.shields.io/npm/dm/iobroker.hombot.svg)
![Трэвис-CI](https://img.shields.io/travis/AlGu1/ioBroker.hombot/master.svg)
![AppVeyor](https://ci.appveyor.com/api/projects/status/github/AlGu1/ioBroker.hombot?branch=master&svg=true)
![NPM](https://nodei.co/npm/iobroker.hombot.png?downloads=true)

<img src="admin/hombot.png"></img>

# IoBroker.hombot
=================

Адаптер для дизельного двигателя. Устаревшие и надежные роботы LG HomBot Staubsauger-Roboters перед установкой WLAN-Hack. Das Widget kann für die Steuerung und Anzeige der Statuswerte в Vis benutzt werden.

## Требования
* Für die Nutzung dieses Адаптеры для WLAN Hack (http://www.roboter-forum.com/showthread.php?10009-LG-Hombot-3-0-WLAN-amp-Kamera-Steuerung-per-Weboberfläche) erforderlich ,

## Конфигурация
* URL-адрес (URL-адрес) eingetragen werden. Опрос и опроса Интервал необязателен и не подлежит обсуждению. Статус-статус.

   ![Скриншот](../../../en/adapterref/iobroker.hombot/img/settings.png)

* В музее Вис-виджета в музее с идентификатором объекта z.B. "hombot.0" eingetragen werden.

   ![Скриншот](../../../en/adapterref/iobroker.hombot/img/widget.png)

## Сделать
* Weitere Kommandos einbauen (Stimme, Name ändern, Manuelle Steuerung)
* Weiteres Widget für Kamerabild
* Weiteres Widget für letzte Карта
* Travis-CI / AppVeyor Тесты Эйнбауэн

*

## Changelog
### 0.1.3
* (AlGu1) Remove message receive handling, because not used

### 0.1.2
* (AlGu1) Latest repository settings and vis widget JS changes

### 0.1.1
* (AlGu1) Fix syntax error in main.js

### 0.1.0
* (AlGu1) Add JS-Controller compact mode 

### 0.0.9
* (AlGu1) Change settings

### 0.0.8
* (AlGu1) Merge pull request and change settings for adapter checker

### 0.0.7
* (AlGu1) Disable error log if hombot not conected

### 0.0.6
* (AlGu1) Admin3 changes

### 0.0.5
* (AlGu1) Adding test with Travis-CI and AppVeyor

### 0.0.4
* (AlGu1) Fix widget connection state icon

### 0.0.3
* (AlGu1) Extend ReadMe

### 0.0.2
* (AlGu1) Add many functions and vis widget

### 0.0.1
* (AlGu1) initial release

## License
The MIT License (MIT)

Copyright (c) 2019 Alexander Gurtzick <algu1@outlook.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
