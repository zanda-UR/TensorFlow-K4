## Aufgabe 3:

Implementiere ein einfaches Modell der logistischen Regression in Python mit TensorFlow, um eine binäre Klassifikation durchzuführen. Verwende dafür den folgenden fiktiven Datensatz, der die Anzahl der bearbeiteten Übungsaufgaben pro Woche `X` und das Bestehen einer kurzen Lernkontrolle `Y` darstellt. Der Wert `1` bedeutet bestanden, der Wert `0` bedeutet nicht bestanden.

Dein Ziel ist es, ein Modell zu trainieren, das vorhersagt, ob eine Person basierend auf der Anzahl bearbeiteter Übungsaufgaben die Lernkontrolle bestehen wird oder nicht.

a) Definiere den Datensatz in Python mit TensorFlow und bereite ihn für das Training vor.

b) Initialisiere die Modellparameter Gewicht und Bias zufällig.

c) Implementiere die logistische Regression mit der Sigmoid-Funktion, um die Wahrscheinlichkeit des Bestehens zu berechnen.

d) Verwende den Gradientenabstieg als Optimierungsalgorithmus, um die Modellparameter zu aktualisieren.

e) Trainiere das Modell mit dem Datensatz für eine angemessene Anzahl von Epochen.

f) Evaluiere das Modell, indem du die Genauigkeit auf dem Datensatz berechnest.

Datensatz

| Bearbeitete Übungsaufgaben (X) | Bestanden (Y) |
| ------------------------------ | ------------- |
| 2                              | 0             |
| 3                              | 0             |
| 4                              | 0             |
| 5                              | 1             |
| 6                              | 1             |
| 7                              | 1             |

