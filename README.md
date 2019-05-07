# lfb-monipi2019

Material zum MoniPi Workshop in Esslingen 2019

## Vorbemerkung, Quellen und Links

Dieser Workshop ist gewissermassen ein Mashup aus bestehenden Projekten und Infos

* Das (alte) Projekt MoniPi für linuxmuster.net: http://docs.linuxmuster.net/de/latest/addons/monipi/index.html *Das sollte man nicht mehr verwenden*. Alle Versuche, einen "alten" MoniPi, aus dieser Anleitung zu aktualisieren sind leider fehlgeschlagen.
* Inhalte des Linux-Workshops an der LAK Esslingen 2016: https://github.com/ironiemix/lfb-linuxworkshop2016 Hier finden sich Präsentatationen zum Umgang mit OMD und cehck_mk.
* Das check_mk-arm Paket von Christian Hofer (chrisss404) https://github.com/chrisss404/check-mk-arm
* Die Anleitungen von Check_MK: https://mathias-kettner.de/cms.html

Das "Installationsrepo" findet sich hier: https://github.com/linuxmuster/linuxmuster-omd

## Installation auf einem Paspi

* Es gibt kein Raspberry-Image mehr
* Basis ist ein „nacktes“ raspbian lite stretch

* Raspbian installieren (Image → SD) 
* Raspbian Basisconfig (SSH Zugang, Tastatur, Locales, Zeitzone, Passwort)
* root werden
* git und ansible installieren  (apt-get update, apt-get install git ansible)
* Also root: monipi-Repo klonen
* ``git clone https://github.com/linuxmuster/linuxmuster-omd.git``
* Ins Verzeichnis ``linuxmuster-omd`` wechseln 
*``./create.sh`` aufrufen


