### Was ist Container-Technologie oder Container-Virtualisierung?
<sub>Container-Technologie ist ein Verfahren zur Virtualisierung auf Betriebssystemebene. Sie ermöglicht es, Anwendungen inklusive aller Abhängigkeiten (Bibliotheken, Konfigurationen etc.) isoliert und portabel in sogenannten Containern auszuführen.</sub>

### Was sind die Vor- und Nachteile der Container-Technologie zu virtuellen Servern (VM)
<sub>+ Container sind ressourceneffizienter und mehr lightweight, da sie kein Gebrauch für ein GUI und anderes haben. Sie haben mehr Portabilität und sind allgemein viel schneller. (Je nach Funktion)  
- Container verwenden den gleichen Kernel, was geringere Sicherheit mit sich bringt. (Weniger Isolation im Vergleich zu VMs)</sub>

### Welche Produkte kennen Sie im Zusammenhang mit virtuellen Servern und Container?
<sub>Für Virtuelle Server gibt es Hypervisoren (2 Typen) wie VMWare ESXi oder VirtualBox, für Container gibt es Podman, Docker, usw. Zudem kann man beide über Cloud Plattformen betreiben.</sub>

### Wie unterscheiden sich die Technologien VM und Container in Bezug auf Bereitstellung, Speicherplatz, Portabilität, Effizienz und Betriebssystem (Kernel)?
<sub>Container starten schneller, brauchen weniger Speicher und sind portabler. Sie teilen sich den Host-Kernel und sind effizienter. VMs starten langsamer, nutzen mehr Speicher, haben eigenen Kernel und sind schwerer zu portieren.</sub>

### Können virtuelle Server immer durch Container ersetzt werden?
<sub>Nein, nicht immer. Container bieten weniger Isolation und eignen sich nicht für alle Anwendungsfälle, z. B. bei verschiedenen Betriebssystemen oder komplexer Sicherheitsanforderung.</sub>

### Was ist Unterschied zwischen Self-Managed und Fully Managed? Notieren Sie sich die wichtigsten Merkmale und diskutieren Sie die Ergebnisse in der Gruppe.
<sub>Self-Managed:  
- Benutzer verwaltet alles selbst (Updates, Sicherheit, Skalierung)  
- Volle Kontrolle, aber höherer Aufwand  
- Flexibel, aber fehleranfälliger  

Fully-Managed:  
- Anbieter übernimmt Betrieb, Wartung, Updates  
- Weniger Aufwand für Nutzer  
- Weniger Kontrolle, aber einfache Nutzung</sub>
