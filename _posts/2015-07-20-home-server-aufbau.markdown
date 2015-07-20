---
layout: 	post
title:  	"Aufbau Home Server"
subtitle:   "Kleiner Server f�r die WG"
date:   	2015-07-19 17:30:31
author:     "Danny"
header-img: "img/post-bg-02.jpg"
---

Unser alter WG Server hat den Geist aufgegeben und nun soll ein neuer her. Das System vorher war der Acer Aspire X1700, 
der von meinem Mitbewohner zur Verf�gung gestellt wurde. Dieser ist defekt und soll deswegen durch eine m�glichst
stromsparende Alternative ersetzt werden.

## Anforderungen
Der Server soll haupts�chlich als Mediaserver f�r die WG dienen. Au�erdem soll durch Netzwerkfreigaben der einfache Austausch 
von Daten innerhalb des Heimnetzwerks gew�hrleisetet werden. Zus�tzlich soll die Anleitung f�r die Benutzung des Servers 
in Form einer Webseite zur Verf�gung gestellt werden.

Die Hardware soll in einer Studentenwg nat�rlich m�glichst g�nstig und stromsparend sein, wobei der Server nicht im 
Dauerbetrieb l�uft, sondern nur bei Bedarf per Wake-on-LAN gestartet wird.


## Board
Als Board wird das [Intel Desktop Board D945GCLF2](http://ark.intel.com/de/products/42491/Intel-Desktop-Board-D945GCLF2) 
verwendet, das ich vor einiger Zeit geschenkt bekommen habe. Dadurch werden die Kosten sehr gering gehalten und der 
Stromverbrauch sollte ebenfalls viel geringer ausfallen (wird noch gemessen). Das Board enth�lt einen Intel Atom 330 
(1,6 GHz, 2 Kerne, HT, 1 MiB L2, FSB533, Hyper-Thr., 8 Watt TDP), welcher durch Hyper-Threading auf vier logische Kerne 
 kommt. Der Chipsatz der Intel 945GM mit GBit-LAN, 8x USB 2.0, 2x SATA udn 1x IDE. Der aktive K�hler des Chipsatzes wurde
 durch einen [passiven](http://www.pollin.de/shop/dt/MDE5OTY1OTk-/Bauelemente_Bauteile/Mechanische_Bauelemente/Kuehlkoerper/Finger_Kuehlkoerper_AAVID_50x50x45_2_Stueck.html)
 K�hlk�rper ersetzt. Deswegen ist f�r das Geh�use auf jeden Fall ein Geh�usel�fter n�tig. Als Speicher wird 1GB DDR2 RAM 
 benutzt.  Ein Upgrad auf die maximal m�glichen 2GB ist geplant.  
                                                                                        
 
## Geh�use 
Dazu wurde als Geh�use das [MS-Tech LC-01 Rev. C](http://www.arlt.com/Hardware/PC-Komponenten/Gehaeuse/HTPC/MS-Tech-LC-01-Rev-C.html)
verwendet, welches auch schon ein eingebautes 400W Netzteil enth�lt. Das Geh�use liegt bei [Arlt](http://www.arlt.com/) 
derzeit bei ca. 45 Euro uns ist somit relativ g�nstig. Des Weiteren ist oben ein 80mm L�fter vorinstalliert, der direkt am 
Netzteil angeschlossen ist.

## HDD
Dadurch, dass ich an meinem PC die HDD durch eine SSD ersetzt habe, hatte ich noch eine 320 GB Hitachi Platte �brig. 
Diese wurde f�r das Betriebssystem verwendet. F�r Daten wurde die 4TB WD Green aus altem Server benutzt. Damit sind die 
die beiden SATA Ports des Boards auch schon ausgelastet.

## Kritik
Der Geh�usel�fter l�uft durchgehen auf 100%, da er direkt an das Netzteil angeschlossen ist. Eine L�sung daf�r w�re das 
ersetzen des L�fters durch einen anderen, der direkt ans Mainboard angeschlossen und dar�ber gesteuert wird.

## �bersicht

* Board: Intel Desktop Board D945GCLF2
* Prozessor: Intel Atom 330 (1,6 GHz, 2 Kerne, HT, 1 MiB L2, FSB533, Hyper-Thr., 8 Watt TDP) 
* Chipsatz: Intel 945GM, GBit-LAN, 8x USB 2.0, 2x SATA, 1x IDE 
* Geh�use: MS-Tech LC-01 Rev. C
* Netzteil: 400W
* HDD: System: 320GB Daten: 4TB

![Server nach dem einbau der Komponenten](img/server.jpg "Board eingebaut")

## Software
Zu der Software werde ich bald einen neuen Post erstellen.

