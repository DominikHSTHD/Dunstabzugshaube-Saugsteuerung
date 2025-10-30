Domäne: Haushaltstechnik

Teilfunktionen:

    1. Abstell-Funktion
    2. Anschalt-Funktion
    3. Bereitschaftsmodus Prüfungs Funktion
    4. Saugmodus Aktivierungs Funktion
    5. Überschneidungstest Funktion


Funktionale Requierements:

    R 1.1: Die Power der Dunstabzugshaube muss abgestellt werden

    R 2.1: Die Power der Dunstabzugshaube muss angeschalten werden und der Bereitschaftsmodus wird aktiviert

    R 3.1: Es muss geprüft werden ob die Dunstagszugshaube aktiv angeschaltet ist
    R 3.2: Ein "Okay" Signal muss zurückgeben werden, falls der Bereitschaftsmodus  aktiv angeschalten ist

    R 4.1: Es muss geprüft werden ob der Bereitschaftsmodus aktiviert ist, falls nein passiert nichts
    R 4.2: Es muss auf Überschneidung geprüft werden
    R 4.4: Der bisher aktivierte Modus muss deaktiviert werden
    R 4.7: Bei Aktivieren des Leise Modus, muss der Rotor mit 25 Watt aktiviert werden und der Leise Modus Knopf einrasten
    R 4.8: Bei Aktivieren der Stufe 1, muss der Rotor mit 50 Watt aktiviert werden und der Stufe 1 Knopf einrasten
    R 4.9: Bei Aktivieren der Stufe 2, muss der Rotor mit 75 Watt aktiviert werden und der Stufe 2 Knopf einrasten

    R 5.1: Es muss geprüft werden welcher Modus bisher aktiviert ist
    R 5.2: Bisheriger Modus muss mit Modus der aktiviert werden soll verglichen werden
    R 5.3: Bei gleichen Modi, muss ein Überschneidungssignal zurückgeben werden

Nicht-Funktionale Requierements:

    R 1.2: Alle Knöpfe sollen ausrasten
    R 1.3: Der Rotor soll von selbst langsam abbremsen

    R 2.2: Falls der Bereitschaftsmodus schon aktiviert ist soll nichts anderes passieren

    R 4.3: Bei Überschneidung soll keine Veränderung vorgenehmen werden
    R 4.5: Der Knopf des bisher aktiven Modus soll ausrasten
    R 4.6: Der Moduswechsel soll innerhalb von einer Sekunde passieren

    R 6: Die Programmierung soll in C passieren


Bedingungen:

    R 4.1 -> R 4.7/4.8/4.9 Power muss aktiv angeschaltet worden sein, damit ein Modus aktiviert wird


Konflikte:
Es existieren keine Konflikte zwischen den Requierements.
