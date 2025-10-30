## Komponentendiagram:

<img width="1314" height="631" alt="Bildschirmfoto vom 2025-10-23 19-09-53" src="https://github.com/user-attachments/assets/1de0a6eb-0c47-4b71-850d-608d530dabef" />


# Verantwortlichkeit der Komponenten:

| **Komponente**      | **Rolle**                  | **Verantwortlichkeiten**                                                 |
|---------------------|----------------------------|--------------------------------------------------------------------------|
| Aus Knopf       | User Interface       | Sendet Signal an Kontrolleinheit momentanen Modus und sich selbst aus zu schalten |
| An Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Bereitschaftsmodus zu aktivieren |
| Leise Modus Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Leise Modus des Rotors zu aktivieren |
| Stufe 1 Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Stufe 1 des Rotors zu aktivieren |
| Stufe 2 Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Stufe 2 des Rotors zu aktivieren |
| Leistungsmodul        | Stromzufuhrkontrolle  | Zu- und Abstellen von Strom für den Rotor|
| Kontrolleinheit | Microcontroller | Kontrolliert abhängig von dem angegebenen Modus wie viel Energie zum Rotor weitergeleitet wird, um die Stärke zu regulieren                   |
| Rotor  | Funktionseinheit       | Dreht sich wenn Energiezufuhr passiert |

# Schnittstellen:

| **Requirements**                                                                          | **Sender**                                                    | **Empfänger**      | **Syntax**  | **Daten**                                                                      | **Testfall**                                                                          |
|---------------------|---------------|-----------|----------------------------------|-------------------------------|
| Req. 1.1 | Aus Knopf | Leistungsmodul | Asynchron | keine | TBD|
| Req. 1.2 | Kontrolleinheit | Leise Modus Knopf, Stufe 1 Knopf, Stufe 2 Knopf | Asynchron | keine | TBD|
| Req. 2.1 | An Knopf | Leistungsmodul | Asynchron | keine | TBD|
| Req. 2.2 | Kontrolleinheit | Leistungsmodul | Synchron | True/False | TBD|
| Req. 3.1 | Leistungsmodul | Leistungs | Synchron | True/False | TBD|
| Req. 3.2 | Leistungsmodul | Kontrolleinheit | Asynchron | True/False | TBD|
| Req. 4.1 | Kontrolleinheit | Leistungsmodul | Synchron | True/False | TBD|
| Req. 4.2 | Kontrolleinheit | Kontrolleinheit | Synchron | Aktiv-status | TBD|
| Req. 4.3 | Kontrolleinheit | Rotor | Asynchron | keine | TBD|
| Req. 4.4 | Kontrolleinheit | Rotor | Asynchron | keine | TBD|
| Req. 4.5 | Kontrolleinheit | Leise Modus Knopf / Stufe 1 Knopf / Stufe 2 Knopf | Asynchron | keine | TBD|
| Req. 4.7 | Leise Modus Knopf / Kontrolleinheit | Kontrolleinheit / Rotor | Asynchron | keine | TBD|
| Req. 4.8 | Stufe 1 Modus Knopf / Kontrolleinheit | Kontrolleinheit / Rotor | Asynchron | keine | TBD|
| Req. 4.9 | Stufe 2 Modus Knopf / Kontrolleinheit | Kontrolleinheit / Rotor | Asynchron | keine | TBD|
| Req. 5.1 | Kontrolleinheit | Kontrolleinheit | Synchron | Aktiv-status | TBD|
| Req. 5.2 | Kontrolleinheit | Kontrolleinheit | Synchron | True/False | TBD|
| Req. 5.3 | Kontrolleinheit | Kontrolleinheit | Asynchron | Überschneidungssignal | TBD|
