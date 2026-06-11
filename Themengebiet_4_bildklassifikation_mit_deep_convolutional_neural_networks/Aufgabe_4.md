## Aufgabe 4:

**Veränderung von Messwerten erkennen**

Ein kleines Lager misst einmal pro Stunde die Temperatur in einem Kühlraum. Die Werte werden in einer Liste gespeichert. Die Lagerleitung möchte auffällige kurzfristige Veränderungen zwischen benachbarten Messwerten sichtbar machen.

Dazu soll eine Funktion geschrieben werden, die eine Liste von Temperaturwerten mit einem kurzen Filter verrechnet. Am Anfang und Ende der Liste sollen fehlende Nachbarwerte so behandelt werden, als hätten sie den Wert `0`, damit die Ergebnisliste genauso lang bleibt wie die ursprüngliche Messreihe.

Implementiere eine Funktion `analyze_temperature_changes`, die zwei Listen erhält:

- `temperatures`: die gemessenen Temperaturwerte
- `change_filter`: der zu verwendende Filter

Die Funktion soll die verrechneten Werte als Liste zurückgeben. Du kannst davon ausgehen, dass der Filter eine ungerade Länge hat.

Begründe zusätzlich kurz:

- warum Listen für die Messwerte und den Filter passend sind,
- warum am Rand zusätzliche Werte benötigt werden,
- warum die elementweise Multiplikation mit anschließender Summierung zur Fragestellung passt.

