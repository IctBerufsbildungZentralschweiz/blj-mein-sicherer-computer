# Backup: Aufgaben

![Bild](res/nobackupplan.webp)

## Aufgabe 1

### Wie sicherst du deine Daten?

Erstelle in deiner Dokumentation ein neues Kapitel "Backup". Beschreibe dort, wie bei dir zuhause die Daten gesichert werden. Beantworte dabei mindestens die folgenden Fragen:

- Wie/mit welchem Tool werden die Daten gesichert?
- Wer ist zuständig für die Datensicherung(en)?
- Welche Daten werden gesichert?  
- Werden die Daten aller Familienmitglieder gesichert?
- Welches Speichermedium wird für die Datensicherung verwendet?
- Wann und wie regelmässig werden die Daten gesichert?

Notiere auch, was deiner Meinung nach die Vor- und Nachteile sind, wie ihr bei dir zu Hause die Daten sichert und begründe kurz.

## Aufgabe 2

### Dateiversionsverlauf einrichten

Richte in deiner Windows 10 VM den Dateiversionsverlauf ein, mit folgenden Vorgaben:

- Die Daten sollen auf eine externe USB-Festplatte gesichert werden.
- Die Daten sollen alle 6 Stunden gesichert werden.
- Die Datensicherungen sollen 1 Jahr aufbewahrt werden.

Starte die Datensicherrung, sobald du den Dateiversionsverlauf konfiguriert hast. Funktoniert alles wie gewünscht?

### Ein Verzeichnis sichern, das sich ausserhalb des Benutzerprofils befinden

Der Dateiversionsverlauf sichert nur Dateien, die in Verzeichnissen innerhalb deines Benutzerkontos gespeichert sind, respektive, die in einem Bibliotheksverzeichnis gespeichert sind (wenn du wissen möchtest, welche das sind, dann öffne den Windows-Explorer, klicke mit der rechten Maustaste in die linke Seitenleiste und wähle _"Zeige Bibliotheken"_).

Erstelle nun ein Verzeichnis "temp" direkt im Laufwerk C: (C:\temp) und speichere dort mindestens eine Datei, z.B. ein Textfile oder ein Foto.

![Bild](res/c-temp.jpg)

Deine Aufgabe ist es dafür zu sorgen, dass der Dateiversionsverlauf auch den Inhalt des Verzeichnisses _c:\temp_ sichert. Recherchiere im Internet, wie das bewerkstelligt werden kann.

[comment]:Um-Verzeichnisse-zu-sichern-die-sich.ausserhalb-deines-Benutzerprofils-befinden,-kannst-du-das-betreffende-Verzeichnis-mit-der-rechten-Maustaste-im-Explorer-anklicken-und-die-Funktion-_"In-Bibliothek-aufnehmen"_-wählen.-So-machst-du-den-Ordner-zum-Teil-einer-der-vorhandenen-oder-einer-neuen-Bibliothek.-So-wird-der-Ordner-künftig-vom-Dateiversionsverlauf-ebenfalls-gesichert.


## Aufgabe 3

### Backup-Strategien

Grosse Datenbestände wie z.B. Bildarchive mit mehreren hundert Gigabyte oder die Daten einer grossen Firma lassen sich nicht mal eben kurz nebenbei sichern. Eine Vollsicherung (Full Backup) kann einen Computer schon mal über mehrere Stunden ausser Gefecht setzen. Es gibt deshalb Backup-Strategien, die zuerst ein Full Backup machen, danach aber jeweils nur noch veränderte und neu hinzugekommene Dateien sichern. So kann Speicherplatz gespart werden.

In der Computerwelt gibt es 3 unterschiedliche Backup-Verfahren. Jedes Verfahren hat Vor- und Nachteile.

1. Vollbackup (Full Backup)
2. Inkrementelles Backup (Incremential Backup)
3. Differentielles Backup (Differential Backup)

#### Dokumentation ergänzen

Mach dich im Internet schlau zu den drei Backup-Verfahren und beschreibe/erkläre deren Funktionsweise in deiner Dokumentation mit eigenen Worten. Liste für jedes Verfahren auch dessen Vor- und Nachteile auf und gib eine Empfehlung ab, welches Verfahren deiner Meinung nach die optimale Backup-Methode ist.
