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

| **Requirements**                                                                          | **Sender**                                                                          | **Empfänger**        | **Daten**                                                                      | **Testfall**                                                                          |
|---------------------|---------------|-----------|----------------------------------|-------------------------------|
| Aus Knopf      | Req. 1.1, Req. 1.2 | Buttons | TBD |
| An Knopf      | Req. 1.2, Req. 2.1 | Buttons  | TBD |
| Leise Modus Knopf      | Req. 1.2, Req. 4.5, Req. 4.7 | Buttons | TBD |
| Stufe 1 Knopf      | Req. 1.2, Req. 4.5, Req. 4.8| Buttons  | TBD |
| Stufe 2 Knopf      | Req. 1.2, Req. 4.5,  Req. 4.9 | Buttons  | TBD |
| Leistungsmodul        | Req. 1.1, Req. 2.1, Req. 2.2, Req. 3.1, Req. 3.2 | Powerunit  | TBD |
| Kontrolleinheit | Req. 4.1, Req. 4.2, Req. 4.3, Req. 4.4, Req. 4.6, Req. 4.7, Req. 4.8, Req. 4.9, Req. 5.1, Req. 5.2, Req. 5.3, Req. 6 | Control  | TBD |
| Rotor  | Req. 1.3 | Rotor  | TBD |
