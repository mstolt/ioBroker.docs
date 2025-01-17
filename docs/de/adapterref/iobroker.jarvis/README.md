---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.jarvis/README.md
title: ioBroker.jarvis
hash: hEhY9ZtTShlgbofIzCvWIdunG4h1LcUueEycbYGtzqA=
---
![Logo](../../../en/adapterref/iobroker.jarvis/admin/jarvis.png)

![Paypal-Spende](https://img.shields.io/badge/paypal-donate%20|%20spenden-blue.svg)
![Anzahl der Installationen](https://iobroker.live/badges/jarvis-installed.svg)
![Stabile Version](https://iobroker.live/badges/jarvis-stable.svg)
![NPM-Version](http://img.shields.io/npm/v/iobroker.jarvis.svg)
![Commits seit der letzten Veröffentlichung](https://img.shields.io/github/commits-since/Zefau/ioBroker.jarvis/latest.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.jarvis.svg)
![NPM](https://nodei.co/npm/iobroker.jarvis.png?downloads=true)

# IoBroker.jarvis jarvis - nur ein weiteres bemerkenswertes vis
[![Travis CI](https://travis-ci.com/Zefau/ioBroker.jarvis.svg?branch=master)](https://travis-ci.com/Zefau/ioBroker.jarvis)

##Deutsche Version
[Hier gibt es die deutsche Übersetzung](README.de.md).

## Was ist Jarvis?
jarvis ist eine Material Design Visualisierung basierend auf [Material-UI](https://material-ui.com/). jarvis bietet eine Struktur und Module, die für die Visualisierung verwendet und flexibel konfiguriert werden können.

jarvis ist [*ansprechbar*](https://de.wikipedia.org/wiki/Responsive_Webdesign) und passt sich der Bildschirmgröße des Browsers an.

Das Layout ist flexibel konfigurierbar. Sie können beliebig viele Registerkarten hinzufügen. Jede Registerkarte kann entweder `fullscreen` sein oder beliebig viele `columns` haben, wobei jede Spalte die `modules` in einer flexiblen Reihenfolge enthält.

Jedes Modul hat seine eigenen Konfigurationsmöglichkeiten ([siehe Wiki](https://github.com/Zefau/ioBroker.jarvis/wiki)).

## Warum Jarvis?
jarvis ist nicht so flexibel wie ioBroker.vis, bietet aber ein einheitliches Design für eine schnelle Visualisierung.

## Installation und weitere Informationen
[Weitere Informationen - insbesondere Redarding-Konfiguration - finden Sie im Wiki](https://zefau.gitbook.io/jarvis-v3/).

_____

## Impressionen
Die Konfiguration der Module kann frei ausgerichtet werden. Nachfolgend einige Impressionen / Beispiele:

###Screencast / Video
[![Video abspielen](https://raw.githubusercontent.com/Zefau/ioBroker.jarvis/master/App/play.png)](https://youtu.be/jltXTSDGoQw)

Weitere Videos finden Sie unter [YouTube-Kanäle](https://www.youtube.com/channel/UCQ7rw5Uect8PSx1aVzEOlzQ).

### Screenshots
#### Beispiel: Dashboard (3 `columns`)
![Dashboard.png](https://raw.githubusercontent.com/Zefau/ioBroker.jarvis/master/App/Dashboard.png)

#### Beispiel: Karte (Vollbild)
![Karte.png](https://raw.githubusercontent.com/Zefau/ioBroker.jarvis/master/App/Map.png)

#### Beispiel: Statistik (2 `columns`)
![Statistik.png](https://raw.githubusercontent.com/Zefau/ioBroker.jarvis/master/App/Statistik.png)

#### Beispiel: Status (3 `columns`, davon 2 leer)
![Status.png](https://raw.githubusercontent.com/Zefau/ioBroker.jarvis/master/App/Status.png)

## Changelog

Please also see [release page](https://github.com/Zefau/ioBroker.jarvis/releases) for changelog and detailed information.


### v2.2.0 - Sherlock Holmes (2021-02-24)

#### :exclamation: BREAKING CHANGES
- Remove all hard coded state keys from source code ([550](https://github.com/Zefau/ioBroker.jarvis/issues/550))

#### :star2: newly added features
- Shelly Importer ([622](https://github.com/Zefau/ioBroker.jarvis/issues/622))
- Support of Yeelight devices in the importer ([593](https://github.com/Zefau/ioBroker.jarvis/issues/593))
- Support of Lifx devices in the importer ([592](https://github.com/Zefau/ioBroker.jarvis/issues/592))
- add additional device Types to ioBroker.hmip adapter import ([573](https://github.com/Zefau/ioBroker.jarvis/issues/573))
- Support import of devices from ioBroker.deconz adapter ([565](https://github.com/Zefau/ioBroker.jarvis/issues/565))
- Move icons to iconify ([563](https://github.com/Zefau/ioBroker.jarvis/issues/563))
- Introduce new functions ([546](https://github.com/Zefau/ioBroker.jarvis/issues/546))
- Improve general error page ([539](https://github.com/Zefau/ioBroker.jarvis/issues/539))
- DeviceImporter: Automatically detect function based on name ([532](https://github.com/Zefau/ioBroker.jarvis/issues/532))
- Support import of devices from ioBroker.unifi.0 ([483](https://github.com/Zefau/ioBroker.jarvis/issues/483))
- Support import of devices from ioBroker.innogy-smarthome ([479](https://github.com/Zefau/ioBroker.jarvis/issues/479))
- Option zur Sicherung der Jarvis Dateien ([478](https://github.com/Zefau/ioBroker.jarvis/issues/478))
- Support import of devices from ioBroker.linkeddevices ([467](https://github.com/Zefau/ioBroker.jarvis/issues/467))
- Support import of devices from ioBroker.ble ([465](https://github.com/Zefau/ioBroker.jarvis/issues/465))
- Support import of devices from ioBroker.rpi2 ([463](https://github.com/Zefau/ioBroker.jarvis/issues/463))
- Farbliche Sekundäre Datenpunkte ([456](https://github.com/Zefau/ioBroker.jarvis/issues/456))
- Support import of devices from ioBroker.mqtt ([454](https://github.com/Zefau/ioBroker.jarvis/issues/454))
- Support import of devices from ioBroker.mihome ([448](https://github.com/Zefau/ioBroker.jarvis/issues/448))
- Formatieren von Werten via Formeln / Callback function ([416](https://github.com/Zefau/ioBroker.jarvis/issues/416))
- Support import of more devices from ioBroker.hm-rpc ([414](https://github.com/Zefau/ioBroker.jarvis/issues/414))
- Support import of devices from ioBroker.modbus adapter ([360](https://github.com/Zefau/ioBroker.jarvis/issues/360))
- Support import wifilight.0 Objects ([325](https://github.com/Zefau/ioBroker.jarvis/issues/325))
- add new module MediaControl ([173](https://github.com/Zefau/ioBroker.jarvis/issues/173))
- add option to hide TopBar ([124](https://github.com/Zefau/ioBroker.jarvis/issues/124))
- Notifications ([56](https://github.com/Zefau/ioBroker.jarvis/issues/56))

#### :bug: fixed bugs
- Remove all hard coded state keys from source code ([550](https://github.com/Zefau/ioBroker.jarvis/issues/550))

#### core
- Remove all hard coded state keys from source code ([550](https://github.com/Zefau/ioBroker.jarvis/issues/550))


### v2.1.0-rc.4 - Into the Wild (2021-01-01)

#### :star2: newly added features
- Support import of more devices from ioBroker.hm-rpc ([414](https://github.com/Zefau/ioBroker.jarvis/issues/414))


### v2.1.0-rc.2 - Spotlight (2020-12-30)

#### :star2: newly added features
- Support import of more devices from ioBroker.hm-rpc ([414](https://github.com/Zefau/ioBroker.jarvis/issues/414))


### v2.1.0-rc.1 - Captain Phillips (2020-12-30)

#### :star2: newly added features
- Detect color input of LightColorBody ([498](https://github.com/Zefau/ioBroker.jarvis/issues/498))
- Support import of devices from ioBroker.mihome-vacuum ([462](https://github.com/Zefau/ioBroker.jarvis/issues/462))
- add component CustomTextBody ([461](https://github.com/Zefau/ioBroker.jarvis/issues/461))
- add option to only show overview and / or preview ([460](https://github.com/Zefau/ioBroker.jarvis/issues/460))
- Support import of more devices from ioBroker.hm-rpc ([414](https://github.com/Zefau/ioBroker.jarvis/issues/414))
- Objektauswahl vereinfachen ([321](https://github.com/Zefau/ioBroker.jarvis/issues/321))
- Allow to show states and to trigger action ([319](https://github.com/Zefau/ioBroker.jarvis/issues/319))
- Feature: Triggern sekundäre Datenpunkte zuweisen ([267](https://github.com/Zefau/ioBroker.jarvis/issues/267))
- Support import of devices from ioBroker.knx adapter ([231](https://github.com/Zefau/ioBroker.jarvis/issues/231))
- StateList: Add option to configure which state will be triggered via group action ([178](https://github.com/Zefau/ioBroker.jarvis/issues/178))
- Add filter / search option to device list ([141](https://github.com/Zefau/ioBroker.jarvis/issues/141))
- Allow user defined global CSS styles overwriting any default styles ([117](https://github.com/Zefau/ioBroker.jarvis/issues/117))
- add JSON Editor for inputs fields in Devices configuration ([98](https://github.com/Zefau/ioBroker.jarvis/issues/98))

#### :bug: fixed bugs
- Calender-Widget zeigt keine wiederkehrenden Termine an ([433](https://github.com/Zefau/ioBroker.jarvis/issues/433))


### v2.0.0-rc.1 - City of God (2020-11-27)

#### :exclamation: BREAKING CHANGES
- hiddenstates / ignoredstates removed ([227](https://github.com/Zefau/ioBroker.jarvis/issues/227))

#### :star2: newly added features
- Modul StateListHorizontal: Anzeige sekundärer Datenpunkte ([364](https://github.com/Zefau/ioBroker.jarvis/issues/364))
- Button 'Speichern und schließen' für die Einstellungen ([318](https://github.com/Zefau/ioBroker.jarvis/issues/318))
- jarvis hinter Reverse Proxy / im Docker ([304](https://github.com/Zefau/ioBroker.jarvis/issues/304))
- Calender: Support for local ical / ics files ([270](https://github.com/Zefau/ioBroker.jarvis/issues/270))
- add warning if state is not part of history adapter ([255](https://github.com/Zefau/ioBroker.jarvis/issues/255))
- Calendar Widget - Add List Layout ([253](https://github.com/Zefau/ioBroker.jarvis/issues/253))
- Backup / Restore ([224](https://github.com/Zefau/ioBroker.jarvis/issues/224))
- ImportDevices: add bulk (un)selection ([223](https://github.com/Zefau/ioBroker.jarvis/issues/223))
- add option for Widget justification ([210](https://github.com/Zefau/ioBroker.jarvis/issues/210))
- Scale contents to fit widget height ([208](https://github.com/Zefau/ioBroker.jarvis/issues/208))
- add option for minHeight and maxHeight to widget ([191](https://github.com/Zefau/ioBroker.jarvis/issues/191))
- DevicesPage: Group devices by functions and allow collapsing groups ([190](https://github.com/Zefau/ioBroker.jarvis/issues/190))
- Allow JavaScript in CustomHTML module ([181](https://github.com/Zefau/ioBroker.jarvis/issues/181))
- Improve connection error screen ([179](https://github.com/Zefau/ioBroker.jarvis/issues/179))
- Change unit input in device configuration to json ([168](https://github.com/Zefau/ioBroker.jarvis/issues/168))
- Import devices: Display states of device that have been retrieved ([160](https://github.com/Zefau/ioBroker.jarvis/issues/160))
- Import devices: Display which states are supported ([159](https://github.com/Zefau/ioBroker.jarvis/issues/159))
- Settings may be changed via ioBroker directly (outside jarvis) ([145](https://github.com/Zefau/ioBroker.jarvis/issues/145))
- Multiple views via adapter instances ([142](https://github.com/Zefau/ioBroker.jarvis/issues/142))
- add calendar week to DateTime ([137](https://github.com/Zefau/ioBroker.jarvis/issues/137))
- add setting to adapt columns based on screen width ([134](https://github.com/Zefau/ioBroker.jarvis/issues/134))
- add custom device label to StateListHorizontal (same as in StateList) ([128](https://github.com/Zefau/ioBroker.jarvis/issues/128))
- hide last update in the status ([121](https://github.com/Zefau/ioBroker.jarvis/issues/121))
- add option for a fullscreen Widget  ([116](https://github.com/Zefau/ioBroker.jarvis/issues/116))
- add possibility to configure options for Body and Action Components ([115](https://github.com/Zefau/ioBroker.jarvis/issues/115))
- add new module DisplayImage ([110](https://github.com/Zefau/ioBroker.jarvis/issues/110))
- add a CheckboxAction ([109](https://github.com/Zefau/ioBroker.jarvis/issues/109))
- Dark Mode ([108](https://github.com/Zefau/ioBroker.jarvis/issues/108))
- Customize button labels of groups ([105](https://github.com/Zefau/ioBroker.jarvis/issues/105))
- Support additional functions ([103](https://github.com/Zefau/ioBroker.jarvis/issues/103))
- Support images as icons ([101](https://github.com/Zefau/ioBroker.jarvis/issues/101))
- add component for user input to StateList module ([99](https://github.com/Zefau/ioBroker.jarvis/issues/99))
- add Donation Page ([96](https://github.com/Zefau/ioBroker.jarvis/issues/96))
- Hide icon and / or title in the TopBar ([95](https://github.com/Zefau/ioBroker.jarvis/issues/95))
- add further HomeMatic and HomeMatic IP devices to the Device Import ([85](https://github.com/Zefau/ioBroker.jarvis/issues/85))
- ButtonAction without label ([83](https://github.com/Zefau/ioBroker.jarvis/issues/83))
- Module for custom HTML ([75](https://github.com/Zefau/ioBroker.jarvis/issues/75))
- add new module Calendar ([70](https://github.com/Zefau/ioBroker.jarvis/issues/70))
- Default icon for device ([42](https://github.com/Zefau/ioBroker.jarvis/issues/42))
- DeviceStateDetails: Custom Device popup configuration ([40](https://github.com/Zefau/ioBroker.jarvis/issues/40))
- Add option to send usage data to developer ([36](https://github.com/Zefau/ioBroker.jarvis/issues/36))
- add new module Weather ([32](https://github.com/Zefau/ioBroker.jarvis/issues/32))
- Quick jump: Quick access to groups ([8](https://github.com/Zefau/ioBroker.jarvis/issues/8))

#### :bug: fixed bugs
- Keep same colors for chart lines ([174](https://github.com/Zefau/ioBroker.jarvis/issues/174))
- States may not contain whitespaces ([171](https://github.com/Zefau/ioBroker.jarvis/issues/171))
- Change unit input in device configuration to json ([168](https://github.com/Zefau/ioBroker.jarvis/issues/168))
- Remove device from layout when deleted ([136](https://github.com/Zefau/ioBroker.jarvis/issues/136))

#### core
- Improve rendering performance on configuration page ([39](https://github.com/Zefau/ioBroker.jarvis/issues/39))


### v1.0.0-rc.16 - Independence Day (2020-09-23)

#### :star2: newly added features
- Add standard state keys to device depending on function ([89](https://github.com/Zefau/ioBroker.jarvis/issues/89))

#### :bug: fixed bugs
- Validate IconStyle and StateStyle ([104](https://github.com/Zefau/ioBroker.jarvis/issues/104))
- BlindLevelAction: Stop-Button shown even though activity is not given ([100](https://github.com/Zefau/ioBroker.jarvis/issues/100))
- Group action fails on certain device state configuration ([94](https://github.com/Zefau/ioBroker.jarvis/issues/94))
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Can't add devices to Map module ([92](https://github.com/Zefau/ioBroker.jarvis/issues/92))
- Map in Widget not shown and jumper is wrongly positioned ([88](https://github.com/Zefau/ioBroker.jarvis/issues/88))
- Import of alias devices may fail in case of insufficient declaration ([87](https://github.com/Zefau/ioBroker.jarvis/issues/87))

#### core
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Add all required language transitions ([91](https://github.com/Zefau/ioBroker.jarvis/issues/91))
- Remove `installedFrom` from io-package the deployment process ([90](https://github.com/Zefau/ioBroker.jarvis/issues/90))


### v1.0.0-rc.15 - Django Unchained

#### :star2: newly added features
- Add standard state keys to device depending on function ([89](https://github.com/Zefau/ioBroker.jarvis/issues/89))

#### :bug: fixed bugs
- BlindLevelAction: Stop-Button shown even though activity is not given ([100](https://github.com/Zefau/ioBroker.jarvis/issues/100))
- Group action fails on certain device state configuration ([94](https://github.com/Zefau/ioBroker.jarvis/issues/94))
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Can't add devices to Map module ([92](https://github.com/Zefau/ioBroker.jarvis/issues/92))
- Map in Widget not shown and jumper is wrongly positioned ([88](https://github.com/Zefau/ioBroker.jarvis/issues/88))
- Import of alias devices may fail in case of insufficient declaration ([87](https://github.com/Zefau/ioBroker.jarvis/issues/87))

#### core
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Add all required language transitions ([91](https://github.com/Zefau/ioBroker.jarvis/issues/91))
- Remove `installedFrom` from io-package the deployment process ([90](https://github.com/Zefau/ioBroker.jarvis/issues/90))


### v1.0.0-rc.10 - Fight Club

#### :star2: newly added features
- Add standard state keys to device depending on function ([89](https://github.com/Zefau/ioBroker.jarvis/issues/89))

#### :bug: fixed bugs
- Group action fails on certain device state configuration ([94](https://github.com/Zefau/ioBroker.jarvis/issues/94))
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Can't add devices to Map module ([92](https://github.com/Zefau/ioBroker.jarvis/issues/92))
- Map in Widget not shown and jumper is wrongly positioned ([88](https://github.com/Zefau/ioBroker.jarvis/issues/88))

#### core
- Unhandled promise rejection ([93](https://github.com/Zefau/ioBroker.jarvis/issues/93))
- Add all required language transitions ([91](https://github.com/Zefau/ioBroker.jarvis/issues/91))
- Remove `installedFrom` from io-package the deployment process ([90](https://github.com/Zefau/ioBroker.jarvis/issues/90))


### v1.0.0-rc.6 - The Matrix Reloaded

#### :bug: fixed bugs
- WidgetPage: Cannot read property "map" of undefined ([77](https://github.com/Zefau/ioBroker.jarvis/issues/77))


### v1.0.0-rc.5 - The Matrix

#### :bug: fixed bugs
- Connection issues when using socket.io as separated adapter (not socket via integrated web adapter) ([74](https://github.com/Zefau/ioBroker.jarvis/issues/74))
- Adapters without a status are shown with yellow status ([68](https://github.com/Zefau/ioBroker.jarvis/issues/68))
- Stop button of blind level state not working in pop-up ([60](https://github.com/Zefau/ioBroker.jarvis/issues/60))


### v1.0.0-rc.1 - The Matrix Revolution

#### :exclamation: BREAKING CHANGES
- Preview for the Action Elements in widget configuration ([43](https://github.com/Zefau/ioBroker.jarvis/issues/43))
- Idea for improved configuration of groups and devices ([26](https://github.com/Zefau/ioBroker.jarvis/issues/26))

#### :star2: newly added features
- Add unreach state ([66](https://github.com/Zefau/ioBroker.jarvis/issues/66))
- Add possibility for boolean battery state ([65](https://github.com/Zefau/ioBroker.jarvis/issues/65))
- Import of blind alias devices ([47](https://github.com/Zefau/ioBroker.jarvis/issues/47))
- Preview for the Action Elements in widget configuration ([43](https://github.com/Zefau/ioBroker.jarvis/issues/43))
- Improve mobile view ([34](https://github.com/Zefau/ioBroker.jarvis/issues/34))
- Customize icons / avatars shown on Map ([33](https://github.com/Zefau/ioBroker.jarvis/issues/33))
- Add pre-defined layout and devices based on user-defined enums ([31](https://github.com/Zefau/ioBroker.jarvis/issues/31))
- Widget iFrame ([29](https://github.com/Zefau/ioBroker.jarvis/issues/29))
- Idea for improved configuration of groups and devices ([26](https://github.com/Zefau/ioBroker.jarvis/issues/26))
- Is it possible to add i18n support ([23](https://github.com/Zefau/ioBroker.jarvis/issues/23))
- Suggestion of new data structure ([21](https://github.com/Zefau/ioBroker.jarvis/issues/21))
- Add dropdown field ([20](https://github.com/Zefau/ioBroker.jarvis/issues/20))
- Device configuration ([18](https://github.com/Zefau/ioBroker.jarvis/issues/18))
- On value of dimmable lights ([12](https://github.com/Zefau/ioBroker.jarvis/issues/12))

#### :bug: fixed bugs
- Blind level shown as null if level is 0 ([72](https://github.com/Zefau/ioBroker.jarvis/issues/72))
- Missing translation of functions ([64](https://github.com/Zefau/ioBroker.jarvis/issues/64))
- Expert mode not loading ([63](https://github.com/Zefau/ioBroker.jarvis/issues/63))
- State icon depending on state value ([61](https://github.com/Zefau/ioBroker.jarvis/issues/61))
- Stop button of blind level state not working in pop-up ([60](https://github.com/Zefau/ioBroker.jarvis/issues/60))
- Add action to imported devices ([59](https://github.com/Zefau/ioBroker.jarvis/issues/59))
- Import of light alias devices ([55](https://github.com/Zefau/ioBroker.jarvis/issues/55))
- Import of heating alias devices ([54](https://github.com/Zefau/ioBroker.jarvis/issues/54))
- Import of window alias devices ([53](https://github.com/Zefau/ioBroker.jarvis/issues/53))
- Function not recognized while importing alias devices ([52](https://github.com/Zefau/ioBroker.jarvis/issues/52))
- Button is pulsating ([51](https://github.com/Zefau/ioBroker.jarvis/issues/51))
- Unit missing after using BlindLevelAction ([50](https://github.com/Zefau/ioBroker.jarvis/issues/50))
- Icons of blinds states not working ([49](https://github.com/Zefau/ioBroker.jarvis/issues/49))
- Label of blinds states not used in widget ([48](https://github.com/Zefau/ioBroker.jarvis/issues/48))
- Changing colors has no effect ([46](https://github.com/Zefau/ioBroker.jarvis/issues/46))
- Problems in settings dialogue after changing language ([45](https://github.com/Zefau/ioBroker.jarvis/issues/45))
- LevelBody for blinds not working as expected ([44](https://github.com/Zefau/ioBroker.jarvis/issues/44))
- Newly created devices / states are not directly available in widget configuration ([41](https://github.com/Zefau/ioBroker.jarvis/issues/41))
- Function blind throws error ([27](https://github.com/Zefau/ioBroker.jarvis/issues/27))
- Sorting states of a device ([25](https://github.com/Zefau/ioBroker.jarvis/issues/25))
- Saving device config ([22](https://github.com/Zefau/ioBroker.jarvis/issues/22))
- Position of configuration pop-up  ([16](https://github.com/Zefau/ioBroker.jarvis/issues/16))


### 0.1.0 - Shawshank Redemption (2020-03-28)

### 0.0.1 (2020-02-21)
- (Zefau) initial version

## License
The MIT License (MIT)

Copyright (c) 2019-2021 Zefau <zefau@mailbox.org>

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