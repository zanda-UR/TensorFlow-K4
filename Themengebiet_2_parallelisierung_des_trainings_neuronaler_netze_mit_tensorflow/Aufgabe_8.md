## Aufgabe 8:

**Verkaufsprognose auf Basis einfacher Beispieldaten**

Ein kleiner Online-Shop möchte untersuchen, ob es einen einfachen Zusammenhang zwischen dem täglichen Werbebudget und der Anzahl der verkauften Produkte gibt.

Für eine Übung sollen künstliche Beispieldaten erzeugt werden. Dabei soll angenommen werden, dass höhere Werbeausgaben tendenziell zu höheren Verkaufszahlen führen. Die Werte sollen aber nicht perfekt auf einer geraden Linie liegen, sondern zufällige Schwankungen enthalten.

Erstelle ein Python-Skript, das ein einfaches Modell trainiert, um diesen Zusammenhang zu lernen.

Bearbeite folgende Punkte:

a) Erzeuge mit NumPy 100 künstliche Datenpunkte. Die Eingabewerte sollen ein Werbebudget darstellen. Die Zielwerte sollen ungefähr einem linearen Zusammenhang folgen, zum Beispiel:

```
verkaufte Produkte = 4 * Werbebudget + 10
```

Füge zufälliges Rauschen hinzu.

b) Teile die Daten in 80 % Trainingsdaten und 20 % Testdaten auf.

c) Standardisiere die Eingabewerte.

d) Erstelle mit TensorFlow 2 und Keras ein lineares Regressionsmodell mit einer einzigen Dense-Schicht.

e) Kompiliere das Modell mit dem Optimierer `'sgd'` und der Verlustfunktion `'mean_squared_error'`.

f) Trainiere das Modell für 200 Epochen und evaluiere es mit den Trainings- und Testdaten.

g) Gib den Trainingsverlust und den Testverlust aus.

h) Begründe kurz:

- warum die verwendete Datenstruktur für diese Daten geeignet ist,
- warum die Standardisierung der Eingabewerte sinnvoll ist,
- warum lineare Regression zu dieser Fragestellung passt.

