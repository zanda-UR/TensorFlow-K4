## Aufgabe 3:

Implementiere ein einfaches Recurrent Neural Network mit TensorFlow, das Filmkritiken aus dem IMDb-Datensatz als **positiv** oder **negativ** klassifiziert.

Der IMDb-Datensatz enthält bereits nummerisch kodierte Filmkritiken und passende Zielwerte. Die Zielwerte geben an, ob eine Kritik positiv oder negativ bewertet wurde.

Führe folgende Schritte durch:

a) Lade den IMDb-Datensatz mit `tensorflow.keras.datasets.imdb`. Begrenze den Wortschatz auf die 10.000 häufigsten Wörter.

b) Bereite die Eingabedaten so vor, dass alle Filmkritiken dieselbe Länge besitzen. Verwende dafür Padding mit einer maximalen Sequenzlänge von 500.

c) Erstelle ein RNN-Modell mit TensorFlow/Keras. Das Modell soll mindestens folgende Schichten enthalten:

- eine `Embedding`-Schicht,
- eine `LSTM`-Schicht,
- eine Ausgabeschicht mit einem Neuron und Sigmoid-Aktivierung.

d) Kompiliere das Modell mit einem passenden Optimierer, einer passenden Verlustfunktion und der Metrik `accuracy`.

e) Trainiere das Modell mit den Trainingsdaten.

f) Evaluiere das Modell mit den Testdaten und gib die Testgenauigkeit aus.

