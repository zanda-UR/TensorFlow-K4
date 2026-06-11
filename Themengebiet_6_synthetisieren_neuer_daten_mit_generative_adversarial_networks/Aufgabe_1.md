## Aufgabe 1:

**Autoencoder für Fashion-MNIST**

Entwickle ein Autoencoder-Modell in Python mit TensorFlow und Keras, das einfache Kleidungsbilder aus dem Fashion-MNIST-Datensatz komprimiert und anschließend rekonstruiert. Der Autoencoder soll aus einem Encoder bestehen, der die Bilder in einen latenten Raum der Dimension 32 überführt, und einem Decoder, der daraus wieder Bilder der ursprünglichen Größe erzeugt.

a) Lade den Fashion-MNIST-Datensatz und teile ihn in Trainings- und Testdaten auf.

b) Erstelle den Encoder-Teil des Autoencoders. Die Eingabebilder sollen in einen latenten Raum der Dimension 32 komprimiert werden.

c) Erstelle den Decoder-Teil des Autoencoders. Die komprimierten Daten sollen wieder in Bilder der Größe 28x28 zurückgeführt werden.

d) Trainiere das Autoencoder-Modell mit den Trainingsdaten und verwende die Testdaten zur Validierung.

e) Zeige nach dem Training zwei Beispielbilder aus den Testdaten und die jeweils rekonstruierten Bilder des Autoencoders.

