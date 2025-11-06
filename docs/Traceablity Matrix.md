# Traceability Matrix:

| **Requierements**   |   **Komponente**  | **Klasee** | **Testfall** |
|-------|--------|-------|-------|
| **Sprint 1:**  |   |   |   | 
| Req. 1.1  |  Aus-Knopf/Leistungsmodul  | KNÖPFE/LEISTUNGSMODUL  |  TBD  | 
| Req. 1.3  |  Rotor  |  ROTOR  |  TBD  | 
| Req. 2.1  |  An-Knopf/Leistungmodul  |  KNÖPFE/LEISTUNGSMODUL  |  TBD  | 
| Req. 2.2  |  Leistungsmodul  |  LEISTUNGSMODUL  |  TBD  | 
| Req. 3.1  | Leistungsmodul   |  LEISTUNGSMODUL  |  TBD  | 
| Req. 3.2  |  Leistungsmodul  |  LEISTUNGSMODUL  |  TBD  |
| | | |
| **Sprint 2:**  | | | | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    |
|  |  |  |  |
| **Sprint 3:**  |   |  |  | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    | 
| Req.   |    |    |    |



| **Komponente**      | **Requirements**                                       | **Klassen**                                       |
|---------------------|--------------------------|-----------------------------------------------------------------|
| Aus Knopf      | Req. 1.1, Req. 1.2 | Buttons |
| An Knopf      | Req. 1.2, Req. 2.1 | Buttons  |
| Leise Modus Knopf      | Req. 1.2, Req. 4.5, Req. 4.7 | Buttons |
| Stufe 1 Knopf      | Req. 1.2, Req. 4.5, Req. 4.8| Buttons  |
| Stufe 2 Knopf      | Req. 1.2, Req. 4.5,  Req. 4.9 | Buttons  |
| Leistungsmodul        | Req. 1.1, Req. 2.1, Req. 2.2, Req. 3.1, Req. 3.2 | Powerunit  |
| Kontrolleinheit | Req. 4.1, Req. 4.2, Req. 4.3, Req. 4.4, Req. 4.6, Req. 4.7, Req. 4.8, Req. 4.9, Req. 5.1, Req. 5.2, Req. 5.3, Req. 6 | Control  |
| Rotor  | Req. 1.3 | Rotor  |

# Schnittstellen:

| **Requirements**                                                                          | **Sender**                                                    | **Empfänger**      | **Syntax**  | **Daten**                                                                      | **Testfall**                                                                          |
|---------------------|---------------|-----------|---------------------------|-------|-------------------------------|
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



# Sprint 1:
Requierements:
- R 1.1
- R 1.3
- R 2.1
- R 2.2
- R 3.1
- R 3.2
