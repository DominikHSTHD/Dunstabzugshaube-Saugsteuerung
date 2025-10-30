## Komponentendiagram:

<img width="1314" height="631" alt="Bildschirmfoto vom 2025-10-23 19-09-53" src="https://github.com/user-attachments/assets/1de0a6eb-0c47-4b71-850d-608d530dabef" />


# Verantwortlichkeit der Komponenten:

| **Komponente**      | **Rolle**                  | **Verantwortlichkeiten**                                                 |
|---------------------|----------------------------|--------------------------------------------------------------------------|
| Knöpfe       | Interaktions-Hardware       | Interaktionsbereich für User und bestimmtes Signal je betätogten Knopfes an Kontrolleinheit geben |
| Leistungsmodul        | Stromzufuhrkontrolle  | Zu- und Abstellen von Strom für den Rotor|
| Kontrolleinheit | Microcontroller | Kontrolliert abhängig von dem angegebenen Modus wie viel Energie zum Rotor weitergeleitet wird, um die Stärke zu regulieren                   |
| Rotor  | Funktionseinheit       | Dreht sich wenn Energiezufuhr passiert |
