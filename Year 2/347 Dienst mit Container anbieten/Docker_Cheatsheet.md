# Docker Cheatsheet

## Container vs. VMs:
Container und virtuelle Maschinen (VMs) sind beide Methoden zur Virtualisierung von Softwareumgebungen, aber sie unterscheiden sich in ihrer Architektur. VMs emulieren eine vollständige Hardwareumgebung und können verschiedene Betriebssysteme ausführen, während Container den Kernel des Host-Betriebssystems gemeinsam nutzen und isolierte, aber gemeinsam genutzte Umgebungen bereitstellen.

## Docker CLI:
Docker Command Line Interface (CLI) ist ein Tool zum Verwalten von Docker-Containern und -Images über die Befehlszeile. Es ermöglicht dem Benutzer, Container zu erstellen, zu starten und zu stoppen, Images zu erstellen und zu verwalten und viele andere Funktionen auszuführen.

## Dockerfile:
Ein Dockerfile ist eine Textdatei, die eine Anleitung zum Erstellen eines Docker-Images enthält. Es definiert die Umgebung und die auszuführenden Schritte, um ein Image zu erstellen, das in einen Container geladen werden kann. Dockerfiles können verwendet werden, um Docker-Images zu automatisieren und zu standardisieren.

## Docker Compose:
Docker Compose ist ein Tool zum Definieren und Ausführen von mehreren Docker-Containern als eine Anwendung. Es ermöglicht Benutzern, Container und Netzwerke zu konfigurieren und zu verwalten, um eine vollständige Anwendung mit mehreren Komponenten zu erstellen und auszuführen.

## Docker Volumes / Datenspeicherung:
Docker Volumes sind eine Möglichkeit, Daten zwischen Docker-Containern und dem Host-System auszutauschen und zu speichern. Sie ermöglichen es Benutzern, Daten dauerhaft zu speichern und zwischen Containern zu teilen, auch wenn die Container gestoppt und neu gestartet werden.

## Container Registries:
Container Registries sind Dienste, die Docker-Images hosten und bereitstellen. Sie ermöglichen es Benutzern, ihre eigenen Docker-Images zu speichern und zu teilen oder auf öffentliche Container-Images von anderen Benutzern zuzugreifen. Bekannte Container Registries sind Docker Hub, Google Container Registry und Amazon Elastic Container Registry.
