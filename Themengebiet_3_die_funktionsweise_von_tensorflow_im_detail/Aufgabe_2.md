## Aufgabe 2:

Ein Unternehmen möchte testweise ein kleines Modell trainieren, das anhand mehrerer numerischer Merkmale einer Kundenanfrage einschätzt, ob die Anfrage vermutlich schnell bearbeitet werden kann oder nicht. Für einen ersten technischen Prototyp liegen noch keine echten Daten vor. Deshalb sollen künstliche Beispieldaten erzeugt werden.

Jede Anfrage wird durch 20 numerische Merkmale beschrieben. Für den Prototyp sollen 1000 Beispielanfragen erzeugt werden. Die Zielvariable soll angeben, ob eine Anfrage als schnell bearbeitbar eingestuft wird (`1`) oder nicht (`0`).

Erstelle ein Python-Skript, das ein einfaches neuronales Netzwerk mit TensorFlow 2 und Keras erstellt, mit diesen künstlichen Daten trainiert und anschließend die trainierten Modellparameter in der Datei `request_model.weights.h5` speichert.

Das Modell soll aus einem versteckten Layer mit 10 Neuronen und ReLU als Aktivierungsfunktion sowie einem Ausgangslayer für eine binäre Entscheidung bestehen.

Begründe kurz:

- warum die Eingabedaten als zweidimensionales Array aufgebaut werden,
- warum der Ausgangslayer eine Sigmoid-Aktivierung verwendet,
- warum die Modellparameter nach dem Training gespeichert werden.

a) Definiere und trainiere das Modell.
b) Speichere die Modellparameter.
c) Begründe deine Entscheidungen kurz.

