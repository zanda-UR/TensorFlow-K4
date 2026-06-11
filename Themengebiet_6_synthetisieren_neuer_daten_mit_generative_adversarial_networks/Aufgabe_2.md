## Aufgabe 2:

**Komprimierung einfacher Produktbilder**

Ein kleines Versandlager speichert viele einfache Graustufenbilder von Produkten, zum Beispiel Schuhe, Pullover oder Taschen. Um Speicherplatz zu sparen und trotzdem prüfen zu können, ob die wichtigsten Bildinformationen erhalten bleiben, soll ein Modell trainiert werden, das solche Bilder zuerst verdichtet und anschließend wieder rekonstruiert.

Verwende dafür den Fashion-MNIST-Datensatz als vereinfachte Bildsammlung. Entwickle ein Autoencoder-Modell mit TensorFlow und Keras, das die Bilder komprimiert und anschließend wiederherstellt.

Das Modell soll die Bilder in einen latenten Raum der Dimension 32 komprimieren und danach wieder Bilder der ursprünglichen Größe erzeugen.

Bearbeite die Aufgabe in Python.

Zusätzlich sollst du kurz begründen:

- warum die Bildwerte vor dem Training normalisiert werden,
- warum der Autoencoder dieselben Daten als Eingabe und Zielwert verwendet,
- warum die Ausgabe wieder auf die Form 28x28x1 gebracht wird,
- warum der Vergleich von Originalbildern und rekonstruierten Bildern zur Fragestellung passt.

