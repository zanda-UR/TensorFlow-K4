## Aufgabe 1:

Erstelle ein Python-Skript, das ein einfaches neuronales Netzwerk mit TensorFlow 2 und Keras erstellt, an einem synthetischen Datensatz trainiert und anschließend die Modellparameter speichert.

Das Netzwerk soll aus einem versteckten Layer mit 8 Neuronen und ReLU als Aktivierungsfunktion sowie einem Ausgangslayer für eine **binäre Klassifikation** bestehen. Verwende `numpy`, um 800 Datenpunkte mit jeweils 15 Features zu erzeugen. Die Zielvariable soll aus `0` und `1` bestehen und ebenfalls mit `numpy` erzeugt werden.

Nach dem Training sollen die Modellparameter in einer Datei namens `classification_model.weights.h5` gespeichert werden.

a) Definiere und trainiere das Modell.
b) Speichere die Modellparameter.

