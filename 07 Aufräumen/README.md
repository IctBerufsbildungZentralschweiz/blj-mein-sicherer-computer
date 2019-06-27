# Aufräumen

Sobald länger mit dem PC gearbeitet wird, sammeln sich irgendwo Dateien an, welche eigentlich nicht gebraucht werden aber trotzdem wertvolle Systemressourcen verbrauchen. Das Anlegen dieser Daten kann manuell beschränkt werden, solange man weiss an welchen Stellschrauben man drehen muss. Als Beispiel: Grösse des Caches bei einem Browser.

## Dateien löschen

Dateien zu löschen ist grundsätzlich ganz einfach: Du klickst eine nicht mehr benötigte Datei mit der rechten Maustaste an und entfernst sie per "Klick" auf Löschen von der Festplatte.

### Für immer gelöscht? Denkste!

 Aufgepasst: Löschst du Dateien, gibt Windows zwar den Speicherplatz (nach Leeren des Papierkorbs) frei, löscht aber den Dateiinhalt auf dem Laufwerk nicht. Mit anderen Worten: **Windows löscht Dateien nur oberflächlich**. Das Betriebssystem setzt in der MFT (Master File Table) ein Gelöscht-Flag, das auf den "Ist gelöscht"-Zustand der betr. Datei hinweist. Dadurch sind die entsprechenden Speicherbereiche zum Überschreiben mit neuen Daten freigegeben. Welche freigegebenen Speicherbereiche das Betriebssystem beim Speichern neuer Daten füllt, liegt allerdings ausserhalb unserer Kontrolle. Und solange es noch zu keinem Überschreiben gekommen ist, können Datenrettungstools wie z.B. [Recuva](https://de.wikipedia.org/wiki/Recuva) gelöschte Inhalte problemlos auslesen und wiederherstellen.

### Wipe

> Wipe (englisch für "wischen" oder "putzen") ist eine Eraser-Software, die zum sicheren Löschen von Dateien unter Linux und Windows dient.

Quelle: [Wikipedia](https://de.wikipedia.org/wiki/Wipe)

Beim Wipen wird eine Datei nicht einfach gelöscht, sondern der betroffene Speicherbereich wird mehrmals mit Nullen, speziellen Bit-Mustern und/oder Zufallsdaten überschrieben. Dadurch soll gewährleistet werden, dass die gelöschten Daten nicht mehr durch Datenrettungstools respektive forensische Analyse rekonstruiert werden können.

## CCLeaner

Das Löschen nicht mehr benötigter Dateien geht schnell und unkompliziert mit einem passenden Programm, z.B. mit _CCleaner_, dem weltweit populärsten PC-Cleaner. Mit ihm lässt sich dein PC beschleunigen und optimieren. Darüber hinaus kannst du mit dem integrierten Tool "Drive Wiper" Daten unwiderruflich löschen.

![Logo CCleaner](res/logo-ccleaner.jpg)

<https://www.ccleaner.com/>

## SequoiaView

_SequoiaView_ stellt den Inhalt deiner Festplatte grafisch dar und ordnet die Daten nach ihrer Grösse in farbigen Rechtecken an. Gelb umrandete Rechtecke stehen für Ordner, rot umrandete für Dateien. Zur besseren Übersicht versieht _SequoiaView_ die Dateitypen mit verschiedenen Farben. Alle dargestellten Elemente können geöffnet, aber nicht bearbeitet werden.

![Screen Sequoia View](res/sequoia-view.jpg)

<https://www.win.tue.nl/sequoiaview/>
