# micro-plc
I want to design and develop an tiny PLC platform because the regular systems (like Siemens) are way to expensive in my opinion.
Currently, I'm just taking some notes. For that reason, they're going to be in German. Later i'll polish everything up and engineer a proper system on top of my thoughts. 
I have to stop working on this project for a short while (3 weeks) because I have class tests currently.

--
System: Controller (Erstmal ESP32), gibt Bussignal an Module weiter. Module können IO, Relais oder so sein. 
stabile cycle times durch vTaskDelayUntil()

---
Gehäuse: 
Din-Rail kompatibel,
Design stark am Hager ESC225 inspiriert bzw. wird als Referenzgehäuse genutzt. Insbesondere für den Din-Rail Mechanismus. 
Grobes Design: Schiene von oben umklammern, unten kleiner Schlitten mit Feder, kann mit Schraubendreher zurückgezogen werden. 
Feder Maße: 11mm Lang (Unbelastet), 4mm Durchmesser

Versuche erstmal einen ESP32 ETH01 einzubauen, damit kann man schonmal was anfangen.
