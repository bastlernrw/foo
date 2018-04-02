==Info==

Der '''ESP8266''' ist ein low-Power-32-Bit-Mikrocontroller der chinesischen Firma '''espressif'''. Der 32-Bit-Prozessorkern vom Typ ''Xtensa LX106'' von Tensilica arbeitet mit einem Systemtakt von 80–160&nbsp;MHz, hat 64&nbsp;kB RAM als Befehlspeicher, in den mehrere Megabyte Flash-Speicher eingeblendet werden können, sowie 96&nbsp;kB RAM als Datenspeicher, eine Serial Peripheral Interface - Schnittstelle für Flash-Speichererweiterungen (bis zu 128&nbsp;MBit) und '''integriertes WLAN IEEE 802.11 b/g/n'''. Der ESP8266 ermöglicht den Aufbau von stromsparenden WLAN-Sensoren für Anwendungen im Bereich ''Internet der Dinge''.

Der Mikrocontroller ist auch zusammen mit einer Minimalbeschaltung aus Quarz und Flash-Speicher in Form verschiedener Module zum direkten Einsatz erhältlich. Je nach Modul sind bis zu 12 I/O-Ports, eine I²C-Schnittstelle, eine I²S-Schnittstelle, eine SPI-Schnittstelle, eine asynchrone serielle Schnittstelle und ein 10-bit Analog-Digital-Umsetzer herausgeführt. Alle I/Os werden mit 3,3&nbsp;V betrieben.

Unterstützt werden momentan unterschiedliche Firmware-Varianten:
* ''Lua-basierte'' interaktive Programmierung (NodeMCU)
* ''Micropython'' (Pythonbasierte interaktive Programmierung)
* ''Arduino/C++'' basierte Programmierung
* ''AT-Command'' für die Nutzung als Seriell-zu-WLAN-Schnittstelle
* ''ESP Easy'' zur Ansteuerung von Sensoren/Aktoren über Wlan
* ''ESP Basic''

NodeMCU-, Micropython-Firmware-Varianten unterstützen das interaktive Programmieren auf dem ESP8266. Dabei werden Programme im Flash-Speicher abgelegt, was das Schreiben von Programmen erheblich erleichtert. Sind Programme fertiggestellt, können diese automatisch nach Neustart des Mikrocontrollers ausgeführt werden und steuern so seine Funktion. Der ESP8266 kann auch direkt in C programmiert werden. Hierfür steht vom Hersteller ein SDK zur Verfügung. Außerdem lässt er sich mit dem Arduino-System programmieren. Auch die Programmierung in BASIC und Forth ist möglich.

Als '''Nachfolger des ESP8266''' entwickelte espressif den Mikrocontroller ESP32 mit einigen Verbesserungen wie beispielsweise Bluetooth und einem Hallsensor.

==Projekte==
{| class="wikitable" style="text-align: center;"
!Nummer
!Projekt
!Beschreibung
!Dauer
|-
|1
|Rheinturm-Uhr
|Ein Modell vom Rheinturm mit LED-Sreifen als Uhr.
|
|-
|2
|Temp.-Sensor
|Ein Temperatur-Sensor mit Monitoring.
|
|-
|3
|MQTT
|Client / Server zur Datenübertragung im Aktor Sensor Netzwerk 
|
|-
|4
|???
|???
|
|}
