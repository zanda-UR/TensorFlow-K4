## Aufgabe 2:

**Automatische Sortierung handgeschriebener Formularnummern**

Ein Unternehmen digitalisiert einfache Papierformulare. Auf jedem Formular steht oben rechts eine einzelne handgeschriebene Ziffer von 0 bis 9. Diese Ziffer gibt an, zu welcher internen Kategorie das Formular gehört.

Damit die Formulare später automatisch vorsortiert werden können, soll ein Modell trainiert werden, das solche handgeschriebenen Ziffern erkennt. Für einen ersten Prototyp wird der MNIST-Datensatz verwendet, da er viele Beispiele handgeschriebener Ziffern enthält.

**Aufgabe**

Entwickle ein einfaches CNN in Python mit TensorFlow, das handgeschriebene Ziffern aus dem MNIST-Datensatz klassifiziert.

Das Modell soll folgende Bestandteile enthalten:

- eine Faltungsschicht mit 32 Filtern, einer Filtergröße von 3x3 und ReLU-Aktivierungsfunktion
- eine Max-Pooling-Schicht mit einer Poolgröße von 2x2
- eine Flatten-Schicht
- eine vollständig verbundene Schicht mit 128 Neuronen und ReLU-Aktivierungsfunktion
- eine Ausgabeschicht mit 10 Neuronen und Softmax-Aktivierungsfunktion

Trainiere das Modell mit einer Batch-Größe von 64 und 10 Epochen. Bewerte anschließend die Leistung des Modells mit den Testdaten.

Begründe zusätzlich kurz:

- warum die Bilddaten vor dem Training normalisiert werden,
- warum die zusätzliche Kanal-Dimension benötigt wird,
- warum die Ausgabeschicht 10 Neuronen besitzt,
- warum Softmax zur Fragestellung passt.

