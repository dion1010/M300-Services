[**ZURÜCK**](../README.md)

# 20-Infrastruktur-Automatisierung

## Inhaltsverzeichnis

* 01 - [Vagrant Cloud](#vagrant-cloud)

## Vagrant Cloud

**Vagrant VM von Cloud downloaden**

Zuerst sollte man überhaupt nach einer bestimmten Box suchen die man downloaden möchte:

![Vagrant Cloud search](../Bilder_Markdown/Cloudsearch.jpg)

Nachdem man dann gefunden hat was man möchte und auch nachgeschaut hat, ob es kompatibel ist mit der Virtualisierungslösung die man verwendet, kann man weiter gehen zum download:

![Vagrant Cloud download](../Bilder_Markdown/Clouddownload.jpg)

Sobald der download vollendet ist kann man nochmals mit dem folgenden Befehl korrigieren ob es wirklich heruntergeladen wurde:

`vagrant box list`

BILD

(OPTIONAL)Nun kann man einen weitren Ordner erstellen indem man die VM dann erstellt:

`mkdir myserver`

BILD

Nun die neue Vagrant Umgebung (VM) ind dem Verzeichnis erstellen:

`vagrant init "Name der Box"`

BILD

Zu guter Letzt kann man die VM starten:

 `vagrant up`

 