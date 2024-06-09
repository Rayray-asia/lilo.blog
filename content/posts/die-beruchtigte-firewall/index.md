+++
title = "Die Firewall"
date = "2024-06-09"
draft = false
pinned = false
image = "https://www.itomic.com.au/wp-content/uploads/2016/05/firewall.jpg"
footnotes = "Quellen:\nhttps://www.cisco.com/c/de_de/products/security/firewalls/what-is-a-firewall.html\nhttps://geekflare.com/de/types-of-firewalls/\nhttps://de.wikipedia.org/wiki/Firewall\n"
+++
# Die bekannte Firewall

{{<lead>}}
Ich habe mich bei diesem Projekt mit der sogenannten Firewall befasst. Das Projekt hatte zum Ziel, mir ein höheres Maß an Grundwissen und Allgemeinwissen darüber zu vermitteln. Ich werde euch zu einem späteren Zeitpunkt im Blog erklären, warum ich mich genau auf dieses Thema gewandt habe.
{{</lead>}}
Ein Blog von Raiarii Waber

Sicherlich ist jeder, der bereits Erfahrungen mit der Sicherheit von Netzwerken gesammelt hat, mit diesem Begriff vertraut geworden. Aber was verbirgt sich wirklich hinter einer Firewall? Wozu braucht man sie und wie arbeitet sie eigentlich? Diese und andere Fragen werde ich in diesem Artikel beantworten.
Als jemand, der schon seit vielen Jahren im Bereich von IT tätig ist und auch Familienmitglieder hat, welche schon seit über 10 Jahren mit IT Erfahrungen haben, habe ich immer wieder die Bedeutung einer gut eingestellten Firewall für den Schutz von Systemen und Daten erlebt. Die erste Verteidigungslinie gegen Cyberangriffe ist eine Firewall, die den Unterschied zwischen einem Erfolg und einem Misserfolg ausmachen kann.

## Was ist überhaupt eine Firewall?

Eine Firewall ist ein Sicherheitsvorrichtung für Netzwerke. Sie überwacht den eingehenden und ausgehenden Netzwerkverkehr und entscheidet anhand bestimmter Sicherheitsregeln darüber, ob bestimmte Datenübertragungen erlaubt oder untersagt werden. Seit mehr als 25 Jahren sind Firewalls die wichtigste Verteidigungsmethode für den Schutz von Netzwerken. Sie stellen eine Barriere zwischen nicht vertrauenswürdigen, externen Netzwerken wie dem Internet und geschützten und kontrollierten Bereichen des internen, vertrauenswürdigen Netzwerks dar. Eine Firewall kann als Hardware, Software, Software-as-a-Service (SaaS) oder eine Public Cloud (virtuell) verwendet werden.

{{<box title="Arten von Firewalls">}}
Proxy-Firewalls:
Eine etablierte Art von Firewalls sind Proxy-Firewalls. Diese dienen für eine bestimmte Anwendung als Gateway von einem Netzwerk zu einem anderen. Proxy-Server können zudem zusätzliche Funktionen bereitstellen, etwa Content-Caching und -Sicherheit. Diese verhindern dann direkte Verbindungen von außen auf das Netzwerk. Dies kann sich jedoch auch auf den Durchsatz auswirken und welche Anwendungen darauf ausgeführt werden können.

Paketfilternde Firewalls:
Paketfilternde Firewalls sind die ältesten Firewalls, die ein- und ausgehende Daten überwachen und kontrollieren können, während sie durch ein Netzwerk fließen. Sie erstellt einen Kontrollpunkt oder Filter an einem Netzwerk-Switch oder Verkehrsrouter. Sie filtert Daten auf der Grundlage einiger vordefinierter Regeln und arbeitet auf der Netzwerkebene. Diese Art von Firewall prüft jedes einzelne Datenpaket, das im Netzwerk eingeht oder es verlässt. Sie prüft Daten wie Quell- und Ziel-IP-Adresse, Portnummer, Art des Pakets, Netzwerkprotokoll usw., ohne das Datenpaket zu öffnen. Wenn das Datenpaket die Prüfung besteht und nichts Verdächtiges enthält, lässt die Paketfilter-Firewall das Paket passieren. Wenn jedoch festgestellt wird, dass das Datenpaket verdächtige Inhalte enthält, lässt die Firewall das Paket fallen oder verhindert, dass es in das Netzwerk gelangt.

Software-basierte Firewalls:
Software-basierte Firewalls sind diejenigen, die Sie auf Ihrem lokalen Gerät installieren und nicht auf einem Cloud-Server oder einer einzelnen Hardware-Komponente. Sie isoliert die einzelnen Netzwerkendpunkte voneinander und ist damit ein effektives Instrument zur Schaffung einer tiefen Sicherheit.
Software-basierte Firewalls werden auf einem anderen Gerät oder auf einem Server ausgeführt, auf dem die Daten geschützt werden müssen. Dafür verbraucht sie eine gewisse Menge an Rechenressourcen wie RAM und CPU. Sie überwacht Softwareprogramme, die auf dem Host-Computer ausgeführt werden, und filtert den ein- und ausgehenden Datenverkehr. Diese Firewall ist effizient bei der Arbeit mit Anwendungen auf einem System, der Verwaltung von Benutzern, dem Blockieren von Anwendungen, der Überwachung von Benutzern innerhalb Ihres Netzwerks, der Erstellung von Protokollen und vielem mehr.

NGFW:
Eine typische Next-Generation Firewall (NGFW) kombiniert Paketinspektion mit Stateful Inspection und integriert Deep Packet Inspection (DPI). Das heißt, sie untersucht nicht nur das verwendete Protokoll und den eingesetzten Port, sondern nimmt auch den Inhalt des Datenstroms unter die Lupe, erkennt ungewöhnliches Verhalten oder filtert infizierte Dateien aus. In der Regel erkennen NGFWs auch die Aktivitäten der im Netz tätigen Nutzer und entscheiden auf Basis von Richtlinien, was diese dürfen und was nicht.
Was mit Deep Packet Inspection gemeint ist, hängt sehr stark vom jeweiligen Anbieter ab. Der Kern der Sache ist, dass die Paketinspektion bei traditionellen Firewalls ausschließlich den Header des Pakets betrachtet, während die Deep Packet Inspection die tatsächlichen Daten untersucht, die das Paket enthält. So kann eine solche Firewall den Fortschritt einer Web-Browsing-Sitzung verfolgen und feststellen, dass ein Paket nicht legitim ist und damit blockiert wird, wenn es mit anderen Paketen zu einer HTTP-Server-Antwort zusammengestellt wird.
Gleichgültig, für welche Art von Firewall sich Unternehmen entscheiden: Eine falsch konfigurierte Firewall kann in gewisser Weise schlimmer sein als eine fehlende Firewall, weil sie den gefährlichen Eindruck von Sicherheit vermittelt, während sie wenig oder gar keine bietet.
{{</box>}}

#### Hier geht es zur vollständigen Erklärung über die Firewall:
[copy_86AF4D59-F273-48A2-8761-8CE8B6C309AB.mov](https://muristalden-my.sharepoint.com/:v:/g/personal/raiarii_waber_stud_muristalden_ch/ERWYTZnRtoFGmYe3yo0AGvsBsEELOtDAk4NzmAwQnwsYCA)