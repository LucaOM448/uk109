Was ist Container-Technologie oder Container-Virtualisierung?
# Container-Technologie ist ein Verfahren zur Virtualisierung auf Betriebssystemebene. Sie ermöglicht es, Anwendungen inklusive aller Abhängigkeiten (Bibliotheken, Konfigurationen etc.) isoliert und portabel in sogenannten Containern auszuführen.
Was sind die Vor- und Nachteile der Container-Technologie zu virtuellen Servern (VM)
# + Container sind ressourceneffizienter und mehr lightweight, da sie kein gebrauch für ein GUI und anderes haben. Sie haben mehr Portabilität und sind allgemein viel schneller. (Je nach Funktion)
# - Container verwenden den gleichen Kernel, was geringere Sicherheit mit sich bringt. (Weniger Isolation im Verglecich zu VMs)
Welche Produkte kennen Sie im Zusammenhang mit virtuellen Servern und Container?
# Für Virtuellen Servern gibt es Hypervisors (2 Typen) wie VMWare EXSi oder VirtualBox, für Container gibt es Podman, Docker, usw. Zudem kann man beide über Cloud Plattformen betrieben.
Wie unterscheiden sich die Technologien VM und Container in Bezug auf Bereitstellung, Speicherplatz, Portabilität, Effizienz und Betriebssystem (Kernel)?
# Container starten schneller, brauchen weniger Speicher und sind portabler. Sie teilen sich den Host-Kernel und sind effizienter. VMs starten langsamer, nutzen mehr Speicher, haben eigenen Kernel und sind schwerer zu portieren.
Können virtuelle Server immer durch Container ersetzt werden?
# Nein, nicht immer. Container bieten weniger Isolation und eignen sich nicht für alle Anwendungsfälle, z. B. bei verschiedenen Betriebssystemen oder komplexer Sicherheitsanforderung.
Was ist unterschied zwischen Self-Managed und Fully Managed? Notieren Sie sich die wichtigsten Merkmale und diskutieren Sie die Ergebnisse in der Gruppe.
# Self-Managed: -Benutzer verwaltet alles selbst (Updates, Sicherheit, Skalierung) -Volle Kontrolle, aber höherer Aufwand -Flexibel, aber fehleranfälliger
# Fully-Managed: -Anbieter übernimmt Betrieb, Wartung, Updates -Weniger Aufwand für Nutzer -Weniger Kontrolle, aber einfache Nutzung