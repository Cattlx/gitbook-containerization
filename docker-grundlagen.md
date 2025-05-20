---
description: Die Grundlagen von Docker
---

# Docker Grundlagen

**Inhalt der Seite:**

* **Was ist Docker?**
  * **Docker als Container-Plattform:** Docker ist eine Plattform zur Automatisierung der Bereitstellung von Anwendungen als Container. Es bietet Tools zum Erstellen, Ausführen und Verwalten von Containern.
  * **Docker Engine:** Die Hauptkomponente, die für das Erstellen, Starten und Verwalten von Containern verantwortlich ist. Docker Engine besteht aus einem Server (Docker Daemon), einem REST-API und einem CLI-Client.
* **Die Architektur von Docker:**
  * **Docker Images:** Ein Image ist ein unveränderliches Abbild einer Anwendung und ihrer Umgebung. Es enthält alles, was die Anwendung benötigt: Code, Bibliotheken, Systemtools und -abhängigkeiten.
  * **Docker Container:** Container sind laufende Instanzen eines Docker-Images. Container sind leichtgewichtig, isoliert und können auf jedem Docker-fähigen System ausgeführt werden.
  * **Docker Registry:** Eine Sammlung von Docker-Images. Docker Hub ist die öffentliche Registry, aber private Registries sind auch möglich.
* **Installation von Docker auf verschiedenen Betriebssystemen:**
  * **Linux:** Schritte zur Installation von Docker auf einer typischen Linux-Distribution (z. B. Ubuntu).
  * **Windows:** Docker Desktop für Windows, Verwendung von Windows-Containern.
  * **macOS:** Docker Desktop für macOS und Konfiguration auf Macs mit Apple Silicon und Intel-Chips.
* **Docker CLI und Docker Desktop:**
  * **Docker CLI:** Die Kommandozeilenwerkzeuge wie `docker run`, `docker build`, `docker ps`, etc.
  * **Docker Desktop:** Eine GUI für Docker, die auf Windows und macOS verfügbar ist und das Management von Containern und Images vereinfacht.
