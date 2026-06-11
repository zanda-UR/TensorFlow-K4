## Aufgabe 2:

Ein kleines Geschäft dokumentiert über mehrere aufeinanderfolgende Tage hinweg die Anzahl der Besucher. Die Zahlen steigen jeden Tag ungefähr gleichmäßig an, weil eine Werbeaktion immer mehr Aufmerksamkeit erzeugt.

Die gemessenen Besucherzahlen lauten:

```python
[20, 21, 22, 23, 24, 25, 26, 27, 28, 29]
```

Entwickle ein Python-Skript, das auf Basis dieser Daten ein einfaches Modell trainiert, um aus der Besucherzahl eines Tages die Besucherzahl des nächsten Tages vorherzusagen.

Bearbeite folgende Teilaufgaben:

a) Lege die Besucherzahlen als Sequenz an und teile sie in Eingabedaten und Zielwerte auf.

b) Erstelle ein einfaches rekurrentes neuronales Netzwerk mit TensorFlow. Das Modell soll mindestens eine LSTM-Schicht und eine Dense-Ausgabeschicht enthalten.

c) Trainiere das Modell mit den vorbereiteten Daten.

d) Teste das Modell mit den Besucherzahlen `[25, 26, 27]` und gib die vorhergesagten Werte für den jeweils nächsten Tag aus.

e) Begründe kurz, warum die Daten als Reihenfolge betrachtet werden, warum die Eingabedaten für das Modell umgeformt werden müssen und warum die Vorhersage des nächsten Werts zur Fragestellung passt.

