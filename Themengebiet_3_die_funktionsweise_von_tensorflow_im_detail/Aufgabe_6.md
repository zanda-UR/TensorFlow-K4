## Aufgabe 6

**Verbrauchswerte für Gebrauchtwagen einschätzen**

Ein Gebrauchtwagenhändler möchte für ältere Fahrzeuge eine einfache Einschätzung des Kraftstoffverbrauchs erhalten. Für einige Fahrzeuge liegen bereits technische Angaben wie Motorgröße, Leistung und Gewicht sowie der bekannte Verbrauchswert in Miles per Gallon vor. Auf dieser Grundlage soll ein einfaches Modell trainiert werden, das für weitere Fahrzeuge eine Schätzung des MPG-Werts liefern kann.

Verwende die Auto-MPG-Datenmenge aus dem UCI Machine Learning Repository.

Erstelle ein Python-Programm, das die vorhandenen Fahrzeugdaten einliest, geeignete numerische Merkmale auswählt, die Daten in Trainings- und Testdaten aufteilt, die Eingabewerte normalisiert und anschließend mit TensorFlow ein einfaches lineares Regressionsmodell trainiert. Am Ende soll die durchschnittliche absolute Abweichung auf den Testdaten ausgegeben werden.

Verwende für die Vorhersage die Merkmale:

- Zylinder
- Hubraum
- PS
- Gewicht
- Beschleunigung

Begründe zusätzlich kurz:

- warum die Daten in einem DataFrame verarbeitet werden,
- warum fehlende Werte vor dem Training entfernt werden,
- warum die Merkmale normalisiert werden,
- warum die durchschnittliche absolute Abweichung zur Bewertung passt.

