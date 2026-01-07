# m05_rust_text_dateianalyse

2.3 Text- und Dateianalyse
In dieser Aufgabe soll ein Kommandozeilenwerkzeug zur Analyse von Text- und
Logdateien entwickelt werden. Ziel ist es, Textdateien strukturiert einzulesen,
auszuwerten und die Ergebnisse in übersichtlicher Form auszugeben. Dabei steht
die Verarbeitung realitätsnaher Dateien sowie der sichere Umgang mit
fehlerhaften oder unvollständigen Eingaben im Vordergrund.

Das Programm soll eine oder mehrere Dateien einlesen können und unterschiedliche
Analysefunktionen bereitstellen. Dazu gehören unter anderem das Zählen von Zeilen,
Wörtern und Zeichen, das Suchen nach bestimmten Begriffen sowie das Filtern von
Textzeilen anhand definierter Kriterien.

Die Steuerung erfolgt vollständig über Kommandozeilenparameter, die auch
miteinander kombiniert werden können.

Bei der Verarbeitung soll darauf geachtet werden, dass auch größere Dateien
effizient bearbeitet werden k¨onnen, ohne diese vollständig in den Speicher
zu laden.

Die Auswertungsergebnisse sollen strukturiert und nachvollziehbar dargestellt
werden.

Der Schwerpunkt dieser Aufgabe liegt auf der sauberen Verarbeitung von
Eingabedaten, der klaren Strukturierung des Programms sowie auf einer
verständlichen und robusten Fehlerbehandlung.

Das Projekt soll so aufgebaut sein, dass weitere Analysefunktionen ohne
größere Umbauten integriert werden können.
• Unterstützung regulärer Ausdrücke zur Suche und Filterung
• Verarbeitung sehr großer Dateien im Streaming-Modus
• Ausgabe der Analyseergebnisse in verschiedenen Formaten (z. B. Tabelle, CSV, JSON)
• Vergleich mehrerer Dateien und Hervorhebung von Unterschieden
• Konfigurationsdateien f¨ur wiederkehrende Analyseaufgaben

Hinweis: Diese Aufgabe ist leicht bis mittel.
Folgende Crates könnten sich als hilfreich erweisen:
• regex
• clap
• csv
