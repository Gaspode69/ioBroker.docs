---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.vis-homekittiles/README.md
title: ioBroker.vis-homekittiles
hash: kqvZ7d9RUB2YoTuHY5Nbx+5/WhQ8RixDVyUkEi820nU=
---
# IoBroker.vis-homekittiles

![NPM-Version](https://img.shields.io/npm/v/iobroker.vis-homekittiles.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.vis-homekittiles.svg)
![Anzahl der Installationen](https://iobroker.live/badges/vis-homekittiles-installed.svg)
![Aktuelle Version im stabilen Repository](https://iobroker.live/badges/vis-homekittiles-stable.svg)
![NPM](https://nodei.co/npm/iobroker.vis-homekittiles.png?downloads=true)

<img src="doc/img/title-pic_hkt-on-ipad.png" />

**Tests:** ![Testen und Freigeben](https://github.com/Standarduser/ioBroker.vis-homekittiles/workflows/Test%20and%20Release/badge.svg)

## HomeKit-Kacheln für ioBroker-VIS
Homekit Tiles ist ein Widget-Set, das sich am Design von Apple HomeKit orientiert.
Das Besondere an den Widgets ist, dass diese keine festen Style-Elemente enthalten, sondern alles per CSS formatiert ist. Dadurch gibt es im VIS-Editor keine eigenen Einstellungen für die Position und/oder Größe der Icons, Labels etc. Das Design wird durch Veränderung des CSS-Codes angepasst. Hierzu kann der CSS-Code aus der Datei `/widgets/homekittiles/css/style.css` als Vorlage verwendet werden. Der Code wird im VIS-Editor in den Reiter CSS eingefügt und kann beliebig angepasst werden. Auch das Hinzufügen eigener CSS-Klassen über den VIS-Editor im Bereich „Allgemein“ der Widgets ist möglich.

Die Widgets sind für VIS 1.x konzipiert.

**Hinweis:** Aus Lizenzgründen sind in diesem Adapter keine Icons enthalten. Sehr gute Quellen für Icons sind:

* [https://www.flaticon.com](https://www.flaticon.com)
* [https://icons8.com](https://icons8.com)

[🇩🇪 Dokumentation](doc/homekittiles-de.md) [🇺🇸 Dokumentation](doc/homekittiles-en.md)

## Dinge die zu tun sind
* Mini-Mediaplayer erstellen
* Select-Kachel erstellen
* Untermenü-Button erstellen
* Radiobutton: neue Eigenschaft "Teilung" mit wählbaren Werten (1:1; 3:4)

## Changelog
<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->
### 0.0.13 (2024-05-05)

* (Standarduser) made colors of datepicker window nice
* (Standarduser) removed test divs from hkt-ViewInWidget-Dialog
* (Standarduser) added thermostat widget

### 0.0.12 (2024-05-03)

* (Standarduser) added preview for label-widget
* (Standarduser) added notification bubbles for navigation button-set
* (Standarduser) removed navigation button (use navigation button-set instead)
* (Standarduser) added Settings-Widget with select value list

### 0.0.11 (2024-04-30)

* (Standarduser) added own signal pictures for all tiles widgets
* (Standarduser) Radiobutton: allow HTML in button label
* (Standarduser) Radiobutton: some css corrections
* (Standarduser) added Text field (label) with predefined css-classes

### 0.0.10 (2024-04-26)

* (Standarduser) added Object ID for Active State for View in Widget Dialog tile and Value tile
* (Standarduser) repaired Increment function
* (Standarduser) added own signal pictures

### 0.0.9 (2024-02-02)

* (Standarduser) corrected block operation. ATTENTION! You may have to delete and reinsert your widgets, if you used a different Object ID for blocking operation! Of cause only these widgets, where you used this function ;)
* (Standarduser) corrected formatValue function

### 0.0.7 (2023-12-26)

* (Standarduser) CSS adjustments
* (Standarduser) changed block operation to old variant
* (Standarduser) corrected value formatting in label groups

### 0.0.6 (2023-11-10)

* (Standarduser) just some cleanup

### 0.0.5 (2023-11-04)

* (Standarduser) fixed: adjustment of decimals in labelgroup 1 & 2
* (Standarduser) fixed: readme
* (Standarduser) not fixed: increment not working properbly

### 0.0.4 (2023-11-01)

* (Standarduser) fixed: some corrections on CSS code
* (Standarduser) fixed: widget description text
* (Standarduser) fixed: wrong placement if dialog-height had a unit (ViewInWidget-Dialog)
* (Standarduser) fixed: increment buttons on tiles were working insuficient
* (Standarduser) added: variable number of digits at value-tile
* (Standarduser) added: slider for ViewInWidget-Swipe
* (Standarduser) added: ability to manipulate values in label-groups

### 0.0.2 (2023-10-14)

* (Standarduser) initial release

## License

MIT License

Copyright (c) 2024 Standarduser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.