# IPS Corrently
Adapter Script für die Verwendung von IP-Symcon mit dem Corrently System. Einbinden des Grünstromindex in die Heimsteuerrung

Die Verbindung der Heimautomatisierung von [Symcon](https://www.symcon.de/) im Rahmen der IP-Symcon Plattform erlaubt eine einfache Visualisierung und Steuerrung der Geräte und Sensoren eines Haushaltes. In Verbindung mit [Corrently](https://www.corrently.de/) bekommt das SmartHome einen Blick in das Stromnetz und den Strommarkt.

## Nutzen des Grünstromindex mit IP-Symcon

Bei der Anbindung des [GrünstromIndex](https://www.corrently.de/hintergrund/gruenstromindex/) mit IP-Symcon wird für maximal 36 Stunden der Anteil des Stroms aus Wind, Wasser und Solarenergie am lokalen Strommix nutzbar gemacht. Schaltaktoren können zum Beispiel dann eingeschaltet werden, wenn besonders viel Grünstrom vorhanden ist. Das SmartHome kann somit auf das tatsächliche Dargebot reagieren.

## Installation

Das Script [TarifInfo.ips](./TarifInfo.ips) in die Symcon Management Console hochladen und einmal ausführen.

Es werden automatisch die Variablen angelegt, welche später zu Anzeige oder in Scripten verwendet werden können.

Als Wert der Variable `PLZ` eine gültige Postleizahl in Deutschland eintragen (Standard: 69256).


## Hilfe/Kontakt/Fragen
Bitte im Symcon Forum nachfragen oder per Mail an kontakt@stromdao.de
