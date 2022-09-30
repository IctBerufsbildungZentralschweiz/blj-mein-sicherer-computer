# Virtualisierung

Das Thema "Virtualisierung" hat an einigen Schnittstellen mit Sicherheit zu tun und wird deshalb hier kurz behandelt. Zudem muss man sagen, dass die Virtualisierung generell immer (noch) wichtiger wird.

## Verschiedene Arten der Virtualisierung

Es gibt viele verschiedene Arten der Virtualisierung. Wir schauen 3 wichtige Typen an:

![](<../09 Virtualisierung/res/arten-der-virtualisierung.jpg>)

### Anwendungsvirtualisierung

Bei der Emulation wird einem Wirtscomputer durch Software, dem so genannten Emulator, eine andere Hardware- und Befehlsumgebung vorgetäuscht, als tatsächlich physikalisch vorhanden ist. Dies wird oft eingesetzt um Programme auszuführen die für alte, nicht mehr verfügbare Hardware geschrieben worden ist. Es ist teilweise auch möglich Software zu emulieren, die nicht für den Einsatz auf einem PC gedacht ist, z.B. Spiele für den Nintendo N64, SNES, Gameboy und anderer Spielekonsolen.

Durch den Emulator wird jeder Befehl der von einer emulierten Software kommt so umgewandelt, dass das Wirtssystem diese interpretieren kann. Da das Wirtssystem aber andere Befehlssätze in die vorhandene Hardware integriert hat als von der emulierten Software benötigt wird um diese schnell abarbeiten zu können, wird ein großer Teil der Leistung der CPU für Um- und Rückwandlung dieser Befehle benötigt.

### Host-gestützte Virtualisierung

Bei der Host-gestützten Virtualisierung werden mehrere virtuelle Maschinen auf einem physikalischen Rechner zur Verfügung gestellt. Auf der physikalischen Hardware wird ein Betriebssystem, z.B. Windows 10, installiert. In dieses Betriebssystem wird eine Software, der so genannte [Hypervisor](https://de.wikipedia.org/wiki/Hypervisor), installiert der die Verbindung zwischen den virtuellen Maschinen und dem Betriebssystem herstellt. Im Hypervisor werden abgekapselte Betriebssysteme installiert die völlig unabhängig voneinander sind.

#### Beispiel

Max nutzt als Betriebssystem Windows 10 auf seinem PC. Er möchte nun eine Software installieren, die nur auf Linux läuft. Jetzt hat der Max die Möglichkeit eine zweite Partition auf seinem PC anzulegen und dort Linux zu installieren oder aber er installiert einen Hypervisor (z.B. [VMWare](https://www.vmware.com/) oder [VirtualBox](https://www.virtualbox.org/) in sein bestehendes Windows 10. Mit dem Hypervisor kann er nun eine virtuelle Maschine erstellen und dort Linux installieren. Somit kann Max jederzeit zwischen Windows und Linux wechseln ohne den PC neu starten zu müssen.

### Vollvirtualisierung

Bei der Vollvirtualisierung wird nicht wie bei der Emulation oder der Host-gestützten Virtualisierung ein Gastbetriebssystem vorausgesetzt, sondern der Hypervisor wird direkt anstatt eines Betriebssystems auf der Hardware installiert. Dieses Vorgehen nennt man BareMetal-Virtualisierung: direkt auf Metall(Hardware) Virtualisierung. Dabei wird auf die Schicht des Gastbetriebssystems verzichtet und die Befehle der einzelnen virtuellen Maschinen werden durch den Hypervisor direkt an die Hardware weitergeleitet. Dadurch, dass die Befehle direkt weitergeleitet und nicht zusätzlich verarbeitet werden müssen, ist die Bare-Metal-Virtualisierung sehr performant und wird deshalb von Unternehmen bevorzugt eingesetzt.
