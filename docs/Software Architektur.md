## Komponentendiagram:

<img width="1314" height="631" alt="Bildschirmfoto vom 2025-10-23 19-09-53" src="https://github.com/user-attachments/assets/1de0a6eb-0c47-4b71-850d-608d530dabef" />


# Verantwortlichkeit der Komponenten:

| **Komponente**      | **Rolle**                  | **Verantwortlichkeiten**                                                 |
|---------------------|----------------------------|--------------------------------------------------------------------------|
| An Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Bereitschaftsmodus zu aktivieren |
| Aus Knopf       | User Interface       | Sendet Signal an Kontrolleinheit momentanen Modus und sich selbst aus zu schalten |
| Leise Modus Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Leise Modus des Rotors zu aktivieren |
| Stufe 1 Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Stufe 1 des Rotors zu aktivieren |
| Stufe 2 Knopf       | User Interface       | Sendet Signal an Kontrolleinheit Stufe 2 des Rotors zu aktivieren |
| Leistungsmodul        | Stromzufuhrkontrolle  | Zu- und Abstellen von Strom für den Rotor|
| Kontrolleinheit | Microcontroller | Kontrolliert abhängig von dem angegebenen Modus wie viel Energie zum Rotor weitergeleitet wird, um die Stärke zu regulieren                   |
| Rotor  | Funktionseinheit       | Dreht sich wenn Energiezufuhr passiert |
