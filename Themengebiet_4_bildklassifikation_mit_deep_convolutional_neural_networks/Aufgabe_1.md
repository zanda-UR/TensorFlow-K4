## Aufgabe 1:

Entwickle ein einfaches Convolutional Neural Network in Python mit TensorFlow, das Kleidungsstücke aus dem Fashion-MNIST-Datensatz klassifizieren kann. Das Modell soll aus mindestens einer Faltungsschicht, einer Pooling-Schicht und einer vollständig verbundenen Schicht bestehen.

Verwende den Fashion-MNIST-Datensatz für Training und Test.

a) Lade den Fashion-MNIST-Datensatz und teile ihn in Trainings- und Testdaten auf.

b) Erstelle ein CNN-Modell mit folgender Architektur:

- eine Faltungsschicht mit 32 Filtern, einer Filtergröße von 3x3 und ReLU-Aktivierungsfunktion
- eine Max-Pooling-Schicht mit einer Poolgröße von 2x2
- eine Flatten-Schicht
- eine vollständig verbundene Schicht mit 128 Neuronen und ReLU-Aktivierungsfunktion
- eine Ausgabeschicht mit 10 Neuronen und Softmax-Aktivierungsfunktion

c) Kompiliere das Modell mit dem Adam-Optimierer, Kreuzentropie als Verlustfunktion und Genauigkeit als Metrik.

d) Trainiere das Modell mit 10 Epochen und einer Batch-Größe von 64.

e) Bewerte die Leistung des Modells mit dem Testdatensatz.

