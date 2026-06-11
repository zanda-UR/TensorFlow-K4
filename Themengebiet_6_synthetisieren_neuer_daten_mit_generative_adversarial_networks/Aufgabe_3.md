## Aufgabe 3:

**Gaussian Mixture für Ziffernbilder**

Implementiere ein Python-Skript, das mit einem Gaussian-Mixture-Modell neue ziffernähnliche Bilder erzeugt.

Verwende dafür den `digits`-Datensatz aus `sklearn.datasets`. Die Bilder liegen dort bereits als flache Vektoren mit 64 Werten vor und können als 8x8-Bilder dargestellt werden.

Das Skript soll folgende Anforderungen erfüllen:

a) Lade den `digits`-Datensatz.

b) Gib die Form der Bilddaten und der Labels aus.

c) Zeige ein einzelnes Beispielbild aus dem Datensatz als 8x8-Graustufenbild an.

d) Trainiere ein `GaussianMixture`-Modell mit 15 Komponenten auf den Bilddaten.

e) Erzeuge mit dem trainierten Modell 64 neue Bilder.

f) Forme die generierten Daten wieder in 8x8-Bilder um.

g) Visualisiere die generierten Bilder in einem 8x8-Raster.

