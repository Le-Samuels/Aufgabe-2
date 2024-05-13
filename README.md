# Aufgabe-2

UC 1.03 (Alarm bei zu hoher Herzfrequenz),
Name und Identifikationsnummer: UC 1.03 Alarm Herzfrequenz
Beschreibung: Falls die Herzfrequenz, bei einer Messung eine zu hohe Frequenz erreicht, wird ein Ton ausgegeben. Dieser signalisiert den Tester.
Beteiligte Akteure: Diagnostiker (Ton hören), Proband (Herzfrequenz)
Status: Passiv (nur bei zu hoher Frequenz aktiv)
Verwendete Anwendungsfälle: UC 1.00 Leistungsdiagnostik
Auslöser: Durchführung eines Leistungsdiagnostiktests + ein Proband mit zu hoher Herzfrequenz
Vorbedingungen: UC 1.01 (Proband anlegen), UC 1.02 (Leistungstest anlegen) + ein Proband mit zu hoher Herzfrequenz
Invarianten: Aufzeichnung bis zum Alarm und gegebenenfalls weiter, um zu hohe Herzfrequenz zu untersuchen
Nachbedingung/Ergebnis: Test ergibt Ergebnis einer zu hohen Herzfrequenz oder Abbruch zum Schutz des Probanden.
Standardablauf: Leistungstests werden nacheinander durchgeführt. Sobald ein Alarm auftritt, reagiert der Diagnostiker entsprechend.
Alternativablauf: Kein Alarm ertönt und Leistungstests werden normal durchgeführt.
Hinweis: Deutlichen Ton für den Alarm verwenden, entsprechend reagieren.
Änderungsgeschichte: 13.05.2024 Samuel Dabisch
