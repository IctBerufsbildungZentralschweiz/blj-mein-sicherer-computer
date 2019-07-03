# Aufräumen: Aufgaben

![Bild](res/cleanup.gif)

## Aufgabe 1

### Recuva

Es hat sich herumgesprochen, dass Windows beim Löschen einer Datei nur den Speicherplatz frei gibt, den Inhalt der Datei aber auf dem Laufwerk behält. Das macht es Datenrettungstools einfach, die unsichtbaren Inhalte gelöschter Dateien von der Festplatte zu kratzen. Probiere das jetzt mal aus. Befolge dazu die folgenden Schritte:

1. Hol dir das Tool Recuva und installiere es in deiner VM: <https://www.ccleaner.com/recuva/download>

2. Lade im Internet ein Bild herunter, z.B. dieses hier: <https://isleofwightzoo.com/assets/images/general/Aysha-2-Isle-of-Wight-Zoo-%C2%A9-Karen-Jane-Dudley.jpg>  

3. Wechsle in den Ordner, in den du das Bild gespeichert hast und lösche das Bild **unwiderruflich** mit der Tastenkombination {Shift} + {Delete} (Umschalttaste und Delete-Taste gleichzeitig betätigen), so dass das gelöschte Bild nicht im Papierkorb landet.

4. Das Bild ist nun weg. Ist es wirklich weg? Starte _Recuva_ und versuche mit Hilfe dieses Datenrettungstools das Bild wieder herzustellen. 

Hat es geklappt?

## Aufgabe 2

### CCleaner

In deiner VM: Installiere und starte CCLeaner. Download der Gratis-Version [hier](https://www.ccleaner.com/de-de/ccleaner/download). 

Nach dem Start von CCLeaner Free sollte der Pinsel "Easy Clean" aktiviert sein.

![Screenprint CCleaner](res/start-ccleaner.jpg)

Lasse den "Easy Clean" einmal durchlaufen, indem du den Button _Analyze_ anklickst. Bestätige mit dem Button _Clean all_ um die gefundenen, nicht mehr benötigten Dateien von deinem System zu löschen.

Nimm dir als nächstes ein bisschen Zeit und schaue dir an, was CCLeaner sonst noch alles zu bieten hat. 

#### Unnötige Registry-Einträge löschen?

Achtung. Lösche die "unnötigen" Registry-Einträge **nicht**! Auch wenn CCleaner dein System nicht zerstören wird, werden u.U. wichtige Sachen gelöscht. Die Registry nur bearbeitet werden, wenn du genau weisst, was du tust.

#### Drive Wiper

Bei CCleaner gibt es ein Tool namens "Drive Wiper". Du kannst mit dieser Funktion die gesammte Festplatte löschen ("schreddern"). Oder aber nur den freien Speicherplatz auf dem ausgewählten Laufwerk. Ich empfehle - aus nachvollziehbaren Gründen - nur letzteres zu machen. 

![Screenprint Drive Wiper](res/start-ccleaner.jpg)

Der "Drive Wiper" wird die bereits gelöschten, aber immer noch vorhandenen, Daten entgültig löschen, so dass sie auch mit speziellen Datenrettungstools nicht wieder hergestellt werden können. Dies ist sinnvoll, bei sensitiven oder geheimen Daten, die niemanden etwas angehen, oder wenn man seine gebrauchte Festplatte verkauft. Denn wer will schon, das ein anderer die gelöscht geglaubten Daten wieder herstellt?

Probiere das jetzt mal aus. Befolge dazu die folgenden Schritte:

1. Lade im Internet ein Bild herunter, z.B. dieses hier: <https://isleofwightzoo.com/assets/images/general/Aysha-2-Isle-of-Wight-Zoo-%C2%A9-Karen-Jane-Dudley.jpg>  

2. Wechsle in den Ordner, in den du das Bild gespeichert hast und lösche das Bild **unwiderruflich** mit der Tastenkombination {Shift} + {Delete} (Umschalttaste und Delete-Taste gleichzeitig betätigen), so dass das gelöschte Bild nicht im Papierkorb landet.

3. Starte _CCLeaner_ und wechsle zum Tool "Drive Wiper" (siehe Bild oben). Wähle die Option "Free Space Only" und führe den Wipe danach für das Laufwerk C: aus. _Hinweis: Das Löschen einer Datei mit Wipe dauert länger als das "normale" Löschen, da der freie Speicherplatz mehrmals komplett überschrieben wird._

4. Das Bild ist nun weg. Ist es wirklich weg? Starte _Recuva_ und versuche mit Hilfe dieses Datenrettungstools das Bild wieder herzustellen.

Hat es geklappt?

## Aufgabe 3

### Windows "Boardmittel"

Welche Tools stellt Windows von sich aus zur Verfügung, um unerwünschte Dateien von der Festplatte zu entfernen?

Finde mindestens zwei Windows-Werkzeuge zum Entfernen von Daten (nein, nicht die {Delete}-Taste) und schreibe in deine Dokumentation, wo man diese Werzkeuge findet, was sie tun und wie sie funktionieren.

[comment]: Datenträgerbereinigung_Programme-deinstallieren_Festplatte-formatieren.

## Aufgabe 4

### Fragen

Beantworte die beiden Fragen - natürlich wie immer schriftlich. Recherchiere dazu selbständig im Internet. Du kannst dich auch mit deinen BLJ-Kollegen austauschen, um Antworten zu finden.

- Was passiert beim Formatieren einer Festplatte?
- Was bringt das Formatieren einer Festplatte?

[comment]: Beim-Festplatte-formatieren-werden-alle-Daten-auf-der-ausgewählten-Festplatte,-einer-Speicherkarte-(SD-Karte,-CompactFlash-oder-MMC-Karte)-oder-dem-USB-Stick-unwiderruflich-gelöscht:-Das-Festplatte-formatieren-wird-daher-auch-als-Festplatte-löschen-bezeichnet.-Anders-als-bei-dem-einfachen-Daten-löschen-über-den-Windows-Papierkorb-kann-man-das-Formatieren-danach-auch-nicht-mehr-ganz-so-einfach-und-ohne-Spezialprogramme-rückgängig-machen,-und-auch-mit-solchen-Tools-werden-in-der-Regeln-nicht-mehr-alle-gelöschten-Daten-wiederhergestellt.

[comment]: Vorteile:_Datenmüll-wird-entsorgt_evtl.-vorhandene-schädliche-Software-wird-entsorgt_Fragmentierung-wird-behoben,-wodurch-der-PC-auch-wieder-schneller-wird
