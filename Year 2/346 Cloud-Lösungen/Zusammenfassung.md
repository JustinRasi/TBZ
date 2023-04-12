# Zusammenfassung Lernziele
## Cloud-init
Cloud-init ist ein Tool zur Initialisierung von virtuellen Instanzen in der Cloud. Hier sind die Antworten auf die gestellten Lernziele:

1. YAML-Grundelemente in Cloud-init-Dateien: 
YAML ist eine menschenlesbare Datenstruktur, die häufig für Konfigurationsdateien verwendet wird. In Cloud-init-Dateien finden sich Elemente wie "cloud-config", "runcmd", "users", "packages", "write_files" und "bootcmd".

2. Vorteile von Cloud-init: 
Cloud-init ermöglicht eine schnelle und konsistente Konfiguration von virtuellen Instanzen. Es automatisiert viele Schritte, die normalerweise manuell durchgeführt werden müssen, was die Bereitstellung von Instanzen beschleunigt und menschliche Fehler minimiert.

3. Wichtige Elemente von Cloud-init: 
Zu den wichtigsten Elementen von Cloud-init gehören "cloud-config", "runcmd", "users", "packages", "write_files" und "bootcmd". Diese Elemente ermöglichen die Konfiguration von Netzwerk, Benutzern, Diensten und vielen anderen Aspekten von virtuellen Instanzen.

4. Verwendung der offiziellen Referenz: 
Die offizielle Referenz für Cloud-init ist gut strukturiert und leicht zu durchsuchen. Sie enthält eine umfassende Liste von Elementen und deren Verwendung.

5. Installation von virtuellen Instanzen mit Cloud-init: 
Cloud-init ist in vielen Cloud-Plattformen integriert, darunter Amazon Web Services, Google Cloud Platform und Microsoft Azure. Sie können ein Cloud-init-Image auswählen und damit eine neue Instanz erstellen, die automatisch konfiguriert wird.

6. Infrastructure As Code (IaC): 
IaC ist eine Methode zur Verwaltung von IT-Infrastrukturen durch die Verwendung von Code. Dies ermöglicht die Automatisierung von Bereitstellungen und die Verwaltung von Änderungen in einer effizienten und konsistenten Weise.

7. Produkte für Infrastructure As Code:
Es gibt viele Produkte, die IaC-Unterstützung bieten, darunter Terraform, AWS CloudFormation, Google Cloud Deployment Manager und Ansible.

## Virtualisierung
1. Virtualisierung: 
Virtualisierung ist eine Technologie, die es ermöglicht, mehrere Betriebssysteme auf einer einzigen physischen Hardware-Plattform auszuführen. Dadurch können Ressourcen wie CPU, Speicher und Netzwerk effizienter genutzt werden, was zu einer höheren Auslastung der Hardware führt.

2. Hypervisor-Rolle in der Virtualisierung: 
Ein Hypervisor ist eine Software-Schicht, die es ermöglicht, mehrere virtuelle Maschinen auf einer einzigen physischen Hardware-Plattform auszuführen. Der Hypervisor stellt die Hardware-Ressourcen den virtuellen Maschinen zur Verfügung und isoliert sie voneinander, so dass jede VM unabhängig von den anderen betrieben werden kann.

3. Typ 1 und Typ 2 Hypervisors: 
Typ 1 Hypervisors, auch bekannt als "Bare-Metal-Hypervisors", laufen direkt auf der physischen Hardware und stellen eine Plattform für virtuelle Maschinen zur Verfügung. Typ 2 Hypervisors laufen auf einem Host-Betriebssystem und ermöglichen die Erstellung und Verwaltung von virtuellen Maschinen als Anwendungen innerhalb des Host-Betriebssystems. Der Hauptunterschied besteht darin, dass Typ 1 Hypervisors direkten Zugriff auf die Hardware haben und daher eine höhere Leistung bieten, während Typ 2 Hypervisors mehr Flexibilität bieten und einfacher zu verwalten sind.

4. Hyperscaler: 
Hyperscaler sind Unternehmen, die sehr große Cloud-Infrastrukturen betreiben und skalierbare Cloud-Services anbieten, wie z.B. Amazon Web Services, Microsoft Azure oder Google Cloud Platform.

5. Schichten von Cloud-Systemen: 
Cloud-Systeme bestehen aus mehreren Schichten, von der physischen Infrastruktur bis hin zu Anwendungen und Diensten. Die Schichten umfassen in der Regel die physische Infrastruktur, die Virtualisierungsschicht, die Plattform- und Anwendungsschichten und die Cloud-Services-Schicht. Die unterste Schicht besteht aus der physischen Hardware, auf der die Virtualisierungsschicht aufgebaut ist. Die Plattform- und Anwendungsschichten umfassen verschiedene Dienste und APIs, die auf der Virtualisierungsschicht aufbauen und es Anwendungen ermöglichen, auf der Cloud-Infrastruktur ausgeführt zu werden. Die oberste Schicht umfasst Cloud-Services, die von den Cloud-Anbietern angeboten werden, wie z.B. Speicher- und Netzwerkdienste oder Datenanalyse-Tools.

## Betriebsmodelle
1. Betriebsmodelle: 
Es gibt drei Betriebsmodelle für Cloud-Computing: Infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS) und Software-as-a-Service (SaaS).

* IaaS: Hierbei stellt der Cloud-Provider eine Infrastruktur zur Verfügung, die es dem Nutzer ermöglicht, virtuelle Maschinen und Ressourcen wie Speicher und Netzwerk zu nutzen. Der Nutzer ist selbst verantwortlich für das Betriebssystem, die Anwendungen und Daten.
* PaaS: Hierbei stellt der Cloud-Provider eine Plattform zur Verfügung, auf der Anwendungen entwickelt, getestet und bereitgestellt werden können. Der Nutzer ist für die Entwicklung und den Betrieb der Anwendungen verantwortlich, während die Infrastruktur vom Provider verwaltet wird.
* SaaS: Hierbei stellt der Cloud-Provider eine fertige Anwendung oder Software zur Verfügung, die der Nutzer direkt nutzen kann, ohne sich um die zugrunde liegende Infrastruktur oder Plattform kümmern zu müssen.

2. Public und Private Cloud: 
Die Unterteilung zwischen Public und Private Cloud bezieht sich auf die Verfügbarkeit und den Zugriff auf die Cloud-Infrastruktur.
* Public Cloud: Hierbei handelt es sich um eine Cloud-Infrastruktur, die öffentlich zugänglich ist und von einem Cloud-Provider betrieben wird. Mehrere Nutzer teilen sich die Infrastruktur, was zu einer höheren Skalierbarkeit und niedrigeren Kosten führt.
* Private Cloud: Hierbei handelt es sich um eine Cloud-Infrastruktur, die exklusiv für einen einzelnen Nutzer oder ein Unternehmen bereitgestellt wird. Die Infrastruktur kann entweder von einem eigenen IT-Team verwaltet oder von einem Cloud-Provider bereitgestellt werden, der die Infrastruktur ausschließlich für einen einzelnen Kunden bereitstellt.

3. Beispiele für Betriebsmodelle: 
Ein Beispiel für IaaS ist Amazon Web Services (AWS), das virtuelle Maschinen, Speicher und Netzwerkressourcen bereitstellt. Ein Beispiel für PaaS ist Microsoft Azure, das eine Plattform für die Entwicklung, den Test und die Bereitstellung von Anwendungen bereitstellt. Ein Beispiel für SaaS ist Salesforce, das eine fertige CRM-Software bereitstellt, die direkt genutzt werden kann, ohne dass sich der Nutzer um die zugrunde liegende Infrastruktur kümmern muss.

## Servicemodelle
1. Servicemodelle: 
Es gibt vier Servicemodelle für Cloud-Computing:
* Infrastructure-as-a-Service (IaaS): Hierbei stellt der Cloud-Provider eine Infrastruktur zur Verfügung, die es dem Nutzer ermöglicht, virtuelle Maschinen, Speicher und Netzwerkressourcen zu nutzen.
* Platform-as-a-Service (PaaS): Hierbei stellt der Cloud-Provider eine Plattform zur Verfügung, auf der Anwendungen entwickelt, getestet und bereitgestellt werden können.
* Software-as-a-Service (SaaS): Hierbei stellt der Cloud-Provider eine fertige Anwendung oder Software zur Verfügung, die der Nutzer direkt nutzen kann, ohne sich um die zugrunde liegende Infrastruktur oder Plattform kümmern zu müssen.
* Function-as-a-Service (FaaS): Hierbei stellt der Cloud-Provider eine Umgebung zur Verfügung, in der Nutzer einzelne Funktionen ausführen können, ohne sich um die zugrunde liegende Infrastruktur oder Plattform kümmern zu müssen.

2. Aufbau der Servicemodelle: 
PaaS baut auf IaaS auf, da eine Plattform nur genutzt werden kann, wenn die zugrunde liegende Infrastruktur vorhanden ist. SaaS kann sowohl auf PaaS als auch auf IaaS aufbauen.

3. Beispielprodukte für Servicemodelle:

IaaS: Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP)
PaaS: Heroku, Google App Engine, Microsoft Azure App Service
SaaS: Salesforce, Dropbox, Office 365
FaaS: AWS Lambda, Google Cloud Functions, Microsoft Azure Functions

## (Cloud-) Migrationsmodelle
1. Die Migration in die Cloud bezieht sich auf den Prozess der Übertragung von Anwendungen, Daten und IT-Ressourcen von einem lokalen Rechenzentrum auf eine Cloud-Infrastruktur. Es gibt verschiedene Migrationsmodelle, die dabei helfen können, diesen Prozess zu planen und zu verwalten. 

2. Hier sind einige der wichtigsten Migrationsmodelle:

* Rehosting: Auch als "Lift and Shift" bezeichnet, bezieht sich auf das Übertragen von Anwendungen und Daten aus einem lokalen Rechenzentrum in die Cloud, ohne dabei größere Änderungen an der Anwendungsarchitektur vorzunehmen. Ziel ist es, die Anwendungen auf der Cloud-Infrastruktur auszuführen, ohne die Codebasis oder das Design der Anwendung zu ändern. Die Zielplattform für das Rehosting sind meist IaaS-Systeme wie Amazon EC2, Microsoft Azure VMs oder Google Compute Engine.

* Refactoring: Auch als "Replatforming" bezeichnet, bezieht sich auf das Übertragen von Anwendungen in die Cloud, während gleichzeitig Anpassungen an der Architektur der Anwendung vorgenommen werden, um die Vorteile der Cloud besser nutzen zu können. Dies kann beispielsweise bedeuten, dass Teile der Anwendung in Container verpackt und auf einer Container-Plattform wie Kubernetes ausgeführt werden oder dass die Anwendung in eine Serverless-Architektur überführt wird. Die Zielplattform für Refactoring sind meist PaaS-Systeme wie Google App Engine, Heroku oder Microsoft Azure App Service.

* Rearchitecting: Auch als "Rebuilding" bezeichnet, bezieht sich auf die Neugestaltung der Anwendung von Grund auf, um die Vorteile der Cloud besser nutzen zu können. Dies kann bedeuten, dass die Anwendung in eine Microservice-Architektur umgebaut wird oder dass die Anwendung in Cloud-native Technologien wie AWS Lambda oder Azure Functions umgesetzt wird. Zielplattformen für Rearchitecting sind in der Regel FaaS- oder Serverless-Systeme.

3. Die Wahl des Migrationsmodells hängt von vielen Faktoren ab, wie beispielsweise dem Umfang der Anwendung, der Komplexität der Anwendungsarchitektur, dem erforderlichen Zeitaufwand und den Kosten. In der Regel ist Rehosting die schnellste und einfachste Option, während Rearchitecting das umfangreichste und komplexeste Modell ist. Es ist wichtig, eine gründliche Analyse der Anwendungen und Systeme durchzuführen, um das beste Migrationsmodell für ein bestimmtes Szenario zu bestimmen.

## Speichermodelle
1. Die vier Speichermodelle in der Cloud sind:

* Block Storage: Bei diesem Speichermodell werden Daten in Blöcken auf separaten Speichergeräten abgelegt. Diese Blöcke können dann von virtuellen Instanzen genutzt werden. Block Storage eignet sich besonders für Speicherung von großen Datenmengen oder Datenbanken, die eine hohe Leistung benötigen.

* Object Storage: Hierbei handelt es sich um ein skalierbares Speichermodell, bei dem Daten als Objekte in einem gemeinsamen Pool abgelegt werden. Jedes Objekt enthält Metadaten und eine ID zur eindeutigen Identifizierung. Object Storage eignet sich besonders für die Speicherung von unstrukturierten Daten wie Bilder, Videos oder Dokumenten.

* File Storage: Dieses Speichermodell bietet einen gemeinsamen Dateispeicher, auf den mehrere virtuelle Instanzen gleichzeitig zugreifen können. Dadurch kann eine gemeinsame Datenbasis für Anwendungen und Services bereitgestellt werden. File Storage ist insbesondere für Anwendungen geeignet, die mehrere Instanzen mit gemeinsamen Daten benötigen.

* Archival Storage: Hierbei handelt es sich um ein kostengünstiges Speichermodell für die langfristige Aufbewahrung von Daten, die nicht häufig abgerufen werden müssen. Archival Storage bietet eine niedrigere Zugriffsgeschwindigkeit und höhere Latenzzeit im Vergleich zu den anderen Speichermodellen, ist aber aufgrund der niedrigeren Kosten geeignet für Daten, die selten oder nie benötigt werden.

2. Der Unterschied zwischen persistentem und flüchtigem Speicher besteht darin, dass persistenter Speicher Daten auch nach dem Ausschalten oder Neustart der virtuellen Instanz speichert, während flüchtiger Speicher nur temporär und nur während der Laufzeit der Instanz existiert. Im Kontext von virtuellen Instanzen wird der persistente Speicher typischerweise für die Speicherung von Betriebssystemen und Anwendungen verwendet, während flüchtiger Speicher als temporärer Arbeitsspeicher genutzt wird.

3. Die Lese- und Schreibgeschwindigkeiten der verschiedenen Speichermodelle sind sehr unterschiedlich und hängen von verschiedenen Faktoren wie der Technologie und der Konfiguration ab. Im Allgemeinen bietet Block Storage eine höhere Leistung als Object Storage, während File Storage eine höhere Flexibilität bietet, da mehrere Instanzen gleichzeitig auf die gleichen Dateien zugreifen können. Archival Storage ist aufgrund seiner niedrigeren Kosten und geringeren Leistung für die Speicherung von Daten geeignet, die nicht häufig abgerufen werden müssen.