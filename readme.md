# Lern-Periode 4

Milan Jankovic

20.2 bis 2.4.2024

## Grob-Planung

1. Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark; in welchen sind die ungenügend? Welche davon sind besonders wichtig?
   
   Meine Noten in den Modulen 431 und 162 sind beide über einem 5er, was für mich von grosser Bedeutung ist. In den Modulen 117 und 164 bin ich an der LB auch gut dran und hoffe bei beiden für gute Noten.

2. Was hatten Sie sich am Ende von LP3 vorgenommen? Was war Ihr VBV? Wie könnten Sie diesen besonders gut üben?
   
   Mein Verbesserungsvorschlag war es, in der Freizeit mehr zu programmieren. Dies konnte ich nur zum Teil erreichen, da wir in der letzten Zeit viele Prüfungen hatten. 

3. **Neu**: Was möchten Sie Neues lernen?
   
   Ich möchte in C# neue Funktionen lernen wie z. B. dictionaries; API (async, await).

4. Was wäre ein geeignetes Projekt für diese LP4?
   
   Ich möchte meine Kalenderanwendung aus LP3 verbessern. Damit meine ich, dass die Daten in einer Datei gespeichert werden und wenn man die Applikation wieder aufmacht, dass die Daten gespeichert bleiben. Eventuell könnte ich noch einen UI machen (WinForms).

## 20.2.2024

✍️ Heute habe ich die Grob-Planung fertiggeschrieben. Ich habe dazu auf YouTube noch ein paar Tutorials angeschaut, wie mann Daten in eine Datei in C# speichert. Ich konnte noch die Arbeitspakete für die nächste Woche planen. Ich habe auch noch den fertigen Projekt (aus LP3) angeschaut und überlegt, wie ich es in WinForms umwandeln kann. (54 Wörter)

## 27.2.2024

- [ ]  WinForms GUI erstellen
- [x]  Logik für Datenverwaltung erstellen 
- [ ]  Verbindung zwischen GUI und Datenverwaltung herstellen
- [x]  Dateispeicherung implementieren

| Testfall-Nummer | Ausgangslage (Given)                     | Eingabe (When)      | Ausgabe (Then)             | Erfüllt? |
| --------------- | ---------------------------------------- | ------------------- | -------------------------- | -------- |
| 1               | WinForms GUI erstellen                   | -                   | -                          |          |
| 2               | Datenverwaltungslogik                    | -                   | -                          |    x     |
| 3               | GUI & Datenverwaltung herstellen         | Eingabe GUI Element | erwünschte Ausgabe         |          |
| 4               | Termin hinzufügen / löschen / bearbeiten | Eingabe GUI Element | Speicherung in .json Datei |    x     |

✍️ Heute habe ich die Datenverwaltung fertiggemacht. Jetzt werden die Termine in einer Datei gespeichert, also d.h. wenn man den Programm schliesst und dann wieder aufmacht, sind die vorher eingegebenen Termine vorhanden. Ich konnte leider mit WinForms noch nicht anfangen, da ich zuerst die Datenspeicherung gemacht habe und am Ende nicht mehr genug Zeit hatte, dies anzufangen. (56 Wörter)

## 05.3.2024

- [x]  WinForms GUI erstellen
- [x]  Verbindung zwischen GUI und Datenverwaltung herstellen
- [x]  Startbildschirm mit Zeit und Datum (aktualisierend) erstellen
- [x]  Buttons mit Funktionen erstellen

| Testfall-Nummer | Ausgangslage (Given)                     | Eingabe (When)      | Ausgabe (Then)             | Erfüllt? |
| --------------- | ---------------------------------------- | ------------------- | -------------------------- | -------- |
| 1               | WinForms GUI erstellen                   | -                   | -                          |    x     |
| 2               | GUI & Datenverwaltung herstellen         | Eingabe GUI Element | erwünschte Ausgabe         |    x     |
| 3               | Programm gestartet / Startbildschrim programmiert | -                   | Willkommensbildschirm mit Zeit/Datum  |    x     |
| 4               | Buttons mit Funktionen erstellt | erwünschte Eingabe (z. B. Termine abrufen)    | erwünschte Ausgabe (Termine werden angezeigt) |    x     |

✍️ Heute habe ich alle meine Arbeitspakete fertig machen können. Ich habe eine neue WinForms Datei erstellt und als erstes ein Menü erstellt mit all den nötigen Funktionen. Die Funktionen konnte ich aber nicht vollständig beendet, jedoch sieht der GUI schon mal gut aus. Die Datenverwaltung funktioniert auch wie erwünscht. Ich habe WinForms auch repetiert, also ist es mir jetzt viel klarer, wie es aufgebaut ist. (65 Wörter)

## 12.3.2024

- [ ]  Funktion 'Termine erstellen' tz WinForms übernehmen
- [ ]  Funktion 'Termine löschen' zu WinForms übernehmen
- [ ]  Funktion 'Termine verändern' zu WinForms übernehmen
- [ ]  Einzelne Forms für Funktionen verändern (nicht alles in einem Fenster)

| Testfall-Nummer | Ausgangslage (Given)                     | Eingabe (When)      | Ausgabe (Then)             | Erfüllt? |
| --------------- | ---------------------------------------- | ------------------- | -------------------------- | -------- |
| 1               | Funktion Termine erstellen fertig        | Button Termine erstellen drücken | Neues Fenster mit Eingabefeld |        |
| 2               | Funktion Termine löschen fertig         | Button Termine löschen drücken | Neues Fenster mit Eingabefeld |          |
| 3               | Funktion Termine verändern fertig | Button Termine verändern drücken | Neues Fenster mit Eingabefeld |          |
| 4               | Buttons mit Funktionen fertigerstellt | -     | -   |         |

✍️ Heute habe ich...

## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).
