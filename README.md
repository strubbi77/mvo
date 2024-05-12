MVO
===

Dies ist das öffentliche Repository zu meiner App: **Mobiles Veranstaltungs Ordersystem** kurz MVO. 


Es ist ein überwiegend aus Consumer-Hardware bestehendes System zur Abwicklung von Bestellungen für kleine bis mittlere Heckenfeste. 

Tablets  
---- 
![Consumer-Hardware!](Bilder/bild_tablet_laden.jpg)
![App  Tablet!](Bilder/bild_tablet_mit_app.jpg)

Als Kasse sind 90 Bestellungen pro Stunde gut möglich. Eine Bedienung schafft dauerhaft etwa 30 Bestellungen die Stunde, wenn es zusätzliche Träger gibt. In Spitzenzeiten gehen auch 40 Bestellungen die Stunde. 


![App  Tablet!](Bilder/bild_bons.jpg)


Das System besteht aus:

- Server (Raspberry Pi - Python)
- Client Tabletts (Android / Kivy - Python for Android)
- WLAN-Drucker
- Epson TSE (Keine Vermietung einer Kasse ohne TSE)
- Netzwerktechnik

Ausleihbar (Kosten)
---------

Meine Preisliste sieht in der Einführungsphase folgendermaßen aus: 

| Name | Zeitraum | Preis (€) | Kommentar
| :-- | --- |  --: |  :---
| Tagespauschale | täglich | 45  | 
| Drucker  | je Wochenende | 10  | (Papier extra)
| Kassenrolle | je angefanger Rolle | 1,80 | Blue4est
| Tablet | je Tag | 5  |   Bedienung 7", Kasse 10"  
| TSE | je Wochenende | 20 | (ist bei Vermietung nicht optional, da Pflicht Vermietung einer Kasse) 
| | | alle Preise + Mehrwehrsteuer.  

Inkludiert sind: 

- Netzwerktechnik (1 Router, 1 Repeater, 1 LAN-Kabel)
- Ladestation für Tablets
- Kassenschublade
- Server 
Unterstützung bei der Erstellung der Preisliste
Einrichtung der Tablets (Preislistenauswahl + Bedienungsname)
 
Das System ist absichtlich im Inselbetrieb. Hat den Nachteil, dass es keine Fernwartungsfunktionalität gibt, aber im Funkloch funktioniert es trotzdem. 

Somit muss für digitales Zahlen auch ein anderes System beschafft werden. 

Sinnvoll kann ich es derzeit nur im Bereich südl. Breisgau Hochschwarzwald + Freiburg vermieten.

Derzeit habe ich auch noch nicht genug Hardware um sinnvoll vielfach zu vermieten auch fehlen noch einige Features um die Wartbarkeit der App zu verbessern. 
Deswegen ist es 2024 noch mehr oder weniger eine Einführungsphase für weitere Feste, für die ich bisher noch nicht vermietet hatte:

Bisherige Einsätze
----
teilweise schon mehrere Jahre

| Fest | Was wurde verwendet
| --- | --- 
| Dorffest Offnadingen | 3 Tage, bis zu 8 Tablets, bis zu 2 Kassen, 6 Thekendrucker
| Theater Offnadingen | 2 Abende, 5 Tables, 2 Thekendrucker
| Konzert Offnadingen | 1 Abend, 3 Tablets, 2 Thekendrucker
| Schlossgrabenhock Kirchhofen Tischtennisverein| 3 Tage, Kasse, 2 Tablets, 3 Thekendrucker
| Bergwerkfest Münstertal | 2 Tage, Kasse, 3 Tablets, 3 Thekendrucker
| Konzert Bad Krozingen | 1 Abend, 3 Tablets, 2 Thekendrucker
| Hock 1. Mai Wittnau Fußballverein | 1 Tag, Kasse, 3 Thekendrucker
| Bezirkstag  Ehrenkirchen Tischtennis | 1 Abend, 2 Tablets, 2 Thekendrucker

Mögliche Gesamtkosten in der Einführungsphase:
------
- Kasse mit zwei zusätzlichen Thekendruckern für ein 1. Maifest 107,20€ + 19% = 127,56 €
- Kasse, 4 Tablets für Bedienungen, 4 Thekendrucker für ein 3 tägiges Fest: 297€ + 19% = 353,43 €

Preisliste (App)
-------
Die konfiugierte Preisliste für die Kasse ist eine Kommaseparierte Liste mit 5 Spalten

| ID | Typ | Name | Preis | Parent
| -- | --- | ---- | ----  | -------
| aufsteigende Zahl | Getränk oder Trinken (Vorkonfiguration Drucker und Farbe im Menu) | Name bis 50 Zeichen  | Preis mit Komma in " | 0 oder ID eines Oberpunktes

Ein Beispiel der Preisliste ist unter [Preisliste](Preisliste_komma_vorlage_2024.csv) abgelegt. 

Kontakt
------
Kontakt über strub at gmx de oder direkt über das Repository. 
