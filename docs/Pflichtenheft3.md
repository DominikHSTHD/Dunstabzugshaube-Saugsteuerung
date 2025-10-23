Domäne: Haushaltstechnik

Teilfunktionen:

    1. Abstell-Funktion
    2. Anschalt-Funktion
    3. Powermodus Prüfungs Funktion
    4. Saugmodus Aktivierungs Funktion
    5. Überschneidungen prüfen


Funktionale Requierements:

    R 1.1: Abstellen der Power

    R 2.1: Anschalten der Power

    R 3.1: Prüfen ob die Dunstagszugshaube aktiv angeschaltet ist
    R 3.2: Okay Signal zurückgeben, falls Power angeschalten

    R 4.1: Anfragen ob Power angeschaltet ist und 
    R 4.2: Überschneidung prüfen
    R 4.3: Bei Überschneidung keine Veränderung vornehmen
    R 4.4: Bisheriger Modus wird deaktiviert
    R 4.7: Bei Leise Modus, aktivieren der Dunstabzugshaube mit 25 Watt und Knopf einrasten lassen
    R 4.8: Bei Stufe 1, aktivieren der Dunstabzugshaube mit 50 Watt und Knopf einrasten lassen
    R 4.9: Bei Stufe 2, aktivieren der Dunstabzugshaube mit 75 Watt und Knopf einrasten lassen

    R 5.1: Angeben welcher Modus gerade aktiviert ist
    R 5.2: Vergleichen mit Modus der aktiviert werden soll
    R 5.3: Bei gleichen Modi, Überschneidungssignal zurückgeben

Nicht-Funktionale Requierements:

    R 1.2: Alle Knöpfe ausrasten

    R 4.5: Bisheriger Modus Knopf ausrasten
    R 4.6: Wechsel innerhalb von einer Sekunde

    R 6: Programmierung in C


Bedingungen:

    R 4.1 -> R 4.7/4.8/4.9 Power muss aktiv angeschaltet worden sein, damit ein Modus aktiviert wird


Konflikte:
Es existieren keine Konflikte zwischen den Requierements.
