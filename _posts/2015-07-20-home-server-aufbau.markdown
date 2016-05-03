---
layout: 	post
title:  	"Aufbau Home Server"
subtitle:   "Kleiner Server für die WG"
date:   	2015-07-19 17:30:31
author:     "Danny"
comments:   true
header-img: "img/post-bg-02.jpg"
---

Unser alter WG Server hat den Geist aufgegeben und nun soll ein neuer her. Das System vorher war der Acer Aspire X1700, 
der von meinem Mitbewohner zur Verfügung gestellt wurde. Dieser ist defekt und soll deswegen durch eine möglichst
stromsparende Alternative ersetzt werden.

## Anforderungen
Der Server soll hauptsächlich als Mediaserver für die WG dienen. Außerdem soll durch Netzwerkfreigaben der einfache Austausch 
von Daten innerhalb des Heimnetzwerks gewährleistet werden. Zusätzlich soll die Anleitung für die Benutzung des Servers 
in Form einer Webseite zur Verfügung gestellt werden.

Die Hardware soll in einer Studenten-WG natürlich möglichst günstig und stromsparend sein, wobei der Server nicht im 
Dauerbetrieb läuft, sondern nur bei Bedarf per Wake On LAN gestartet wird.


## Board
Als Board wird das [Intel Desktop Board D945GCLF2](http://ark.intel.com/de/products/42491/Intel-Desktop-Board-D945GCLF2) 
verwendet, das ich vor einiger Zeit geschenkt bekommen habe. Dadurch werden die Kosten sehr gering gehalten und der 
Stromverbrauch sollte ebenfalls viel geringer ausfallen (wird noch gemessen). Das Board enthält einen Intel Atom 330 
(1,6 GHz, 2 Kerne, HT, 1 MiB L2, FSB533, Hyper-Thr., 8 Watt TDP), welcher durch Hyper-Threading auf vier logische Kerne 
 kommt. Der Chipsatz der Intel 945GM mit GBit-LAN, 8x USB 2.0, 2x SATA und 1x IDE. Der aktive Kühler des Chipsatzes wurde
 durch einen [passiven](http://www.pollin.de/shop/dt/MDE5OTY1OTk-/Bauelemente_Bauteile/Mechanische_Bauelemente/Kuehlkoerper/Finger_Kuehlkoerper_AAVID_50x50x45_2_Stueck.html)
 Kühlkörper ersetzt. Deswegen ist für das Gehäuse auf jeden Fall ein Gehäuselüfter nötig. Als Speicher wird 1GB DDR2 RAM 
 benutzt.  Ein Upgrade auf die maximal möglichen 2GB ist geplant.  
                                                                                        
 
## Gehäuse 
Dazu wurde als Gehäuse das [MS-Tech LC-01 Rev. C](http://www.arlt.com/Hardware/PC-Komponenten/Gehaeuse/HTPC/MS-Tech-LC-01-Rev-C.html)
verwendet, welches auch schon ein eingebautes 400 W Netzteil enthält. Das Gehäuse liegt bei [Arlt](http://www.arlt.com/) 
derzeit bei ca. 45 Euro uns ist somit relativ günstig. Des Weiteren ist oben ein 80mm Lüfter vorinstalliert, der direkt am 
Netzteil angeschlossen ist.

## HDD
Dadurch, dass ich an meinem PC die HDD durch eine SSD ersetzt habe, hatte ich noch eine 320 GB Hitachi Platte übrig. 
Diese wurde für das Betriebssystem verwendet. Für Daten wurde die 4 TB WD Green aus altem Server benutzt. Damit sind die 
die beiden SATA Ports des Boards auch schon ausgelastet.

## Kritik
Der Gehäuselüfter läuft durchgehend auf 100 %, da er direkt an das Netzteil angeschlossen ist. Dadurch entsteht dauerhaft 
eine gewisse Geräuschkulisse, welche jedoch nicht so sehr stört, da der Server bei uns im Gang steht. Eine Lösung dafür 
wäre das Ersetzen des Lüfters durch einen anderen, der direkt an das Mainboard angeschlossen ist und darüber gesteuert wird.

**update** Der Gehäuselüfter ist trotzdem leiser als das integrierte Netzteil. Daher sollte dieses zuerst z.B. durch 
eine PicoPSU eretzt werden

## Übersicht

* Board: Intel Desktop Board D945GCLF2
* Prozessor: Intel Atom 330 (1,6 GHz, 2 Kerne, HT, 1 MiB L2, FSB533, Hyper-Thr., 8 Watt TDP) 
* Chipsatz: Intel 945GM, GBit-LAN, 8x USB 2.0, 2x SATA, 1x IDE 
* Gehäuse: MS-Tech LC-01 Rev. C
* Netzteil: 400W
* HDD: System: 320 GB Daten: 4 TB

![Server nach dem Einbau der Komponenten]({{ site.url }}/img/server.jpg "Board eingebaut")
{% image_tag src={{ site.url }}/img/server.jpg width="100" %}

## Software
Zu der Software werde ich bald einen neuen Post erstellen.

