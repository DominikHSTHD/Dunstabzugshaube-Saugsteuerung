## Komponentendiagram:

<img width="1314" height="631" alt="Bildschirmfoto vom 2025-10-23 19-09-53" src="https://github.com/user-attachments/assets/1de0a6eb-0c47-4b71-850d-608d530dabef" />


| **Komponente**      | **Requirements**                                                                          |
|---------------------|-------------------------------------------------------------------------------------------|
| Knöpfe      | Req. 1.2, Req. 4.5, Req. 4.7, Req. 4.8, Req. 4.9 |
| Leistungsmodul        | Req. 1.1, Req. 2.1, Req. 2.2, Req. 3.1, Req. 3.2 |
| Kontrolleinheit | Req. 4.1, Req. 4.2, Req. 4.3, Req. 4.4, Req. 4.6, Req. 4.7, Req. 4.8, Req. 4.9, Req. 5.1, Req. 5.2, Req. 5.3, Req. 6 |
| Rotor  | Req. 1.3 |

# Verantwortlichkeit der Komponenten:

| **Komponente**      | **Rolle**                  | **Verantwortlichkeiten**                                                 |
|---------------------|----------------------------|--------------------------------------------------------------------------|
| Knöpfe       | Interaktions-Hardware       | Reagieren auf Anweisung der User und Signal an Kontrolleinheit geben |
| Leistungsmodul        | Stromkontrolle  | Zu- und Abstellen von Strom |
| Kontrolleinheit | Kontrolleinheit | Moduskontrollierung, Regulierung der genauen Energiezufuhr zum Rotor                   |
| Rotor  | Funktionseinheit       | Reagieren auf Anweisung der Kontrolleinheit |
