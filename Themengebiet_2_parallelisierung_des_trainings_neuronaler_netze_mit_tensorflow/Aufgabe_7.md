## Aufgabe 7

**Aufgabe: Lineare Regression mit TensorFlow und Keras**

Erstelle ein Python-Skript, das ein einfaches lineares Regressionsmodell mit TensorFlow 2 und Keras trainiert. Verwende dafür synthetische Daten, die du selbst mit NumPy generierst. Die Daten sollen aus einer linearen Funktion mit zufälligem Rauschen stammen.

Bearbeite folgende Punkte:

a) Generiere eine synthetische Datenmenge mit 100 Datenpunkten. Die Daten sollen ungefähr der linearen Funktion

```
y = 3x - 2
```

folgen. Füge zufälliges Rauschen hinzu.

b) Teile die Daten in 80 % Trainingsdaten und 20 % Testdaten auf.

c) Standardisiere die Merkmale der Daten.

d) Definiere und instanziiere ein lineares Regressionsmodell mit TensorFlow 2 und Keras. Das Modell soll aus einer einzigen Dense-Schicht bestehen.

e) Kompiliere das Modell mit dem Optimierer `'sgd'` und der Verlustfunktion `'mean_squared_error'`.

f) Trainiere das Modell mit den Trainingsdaten für 200 Epochen und evaluiere es anschließend mit den Trainings- und Testdaten.

g) Gib den Trainingsverlust und den Testverlust aus.

