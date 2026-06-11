## Aufgabe 1:

**RNN zur Vorhersage einer Zahlenfolge**

Entwickle ein Python-Skript, das ein einfaches rekurrentes neuronales Netzwerk mit TensorFlow erstellt, um die nächste Zahl in einer Zahlenfolge vorherzusagen.

Verwende dafür eine Zahlenfolge mit einem linearen Trend, zum Beispiel:

```python
[10, 11, 12, 13, 14, 15, 16, 17, 18, 19]
```

Das Modell soll lernen, aus einem Wert den jeweils nächsten Wert vorherzusagen.

Bearbeite folgende Teilaufgaben:

a) Definiere die Sequenz und teile sie in Eingabedaten und Zielwerte auf.

b) Forme die Eingabedaten so um, dass sie von einer LSTM-Schicht verarbeitet werden können.

c) Erstelle ein RNN-Modell mit TensorFlow, das mindestens eine LSTM-Schicht und eine Dense-Ausgabeschicht enthält.

d) Trainiere das Modell mit den vorbereiteten Daten.

e) Teste das Modell mit mehreren Eingabewerten, zum Beispiel `[14, 15, 16]`, und gib die Vorhersagen aus.

