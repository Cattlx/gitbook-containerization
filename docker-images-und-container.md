---
description: Images und Container
---

# Docker Images und Container

**Inhalt der Seite:**

* **Was ist ein Docker-Image?**
  * **Definition von Docker-Images:** Ein Docker-Image ist eine schreibgeschützte Vorlage, aus der Docker-Container erstellt werden. Es enthält alles, was benötigt wird, um eine Anwendung auszuführen.
  * **Image-Schichten (Layers):** Images bestehen aus mehreren Schichten, die aufeinander gestapelt sind, um ein vollständiges Image zu erstellen. Jede Schicht ist unveränderlich und speichert nur die Unterschiede zu vorherigen Schichten.
  * **Erstellung eines Docker-Images:** Der Befehl `docker build` wird verwendet, um ein Image aus einem Dockerfile zu erstellen.
* **Was ist ein Docker-Container?**
  * **Definition von Containern:** Container sind isolierte Instanzen eines Docker-Images. Sie sind leichtgewichtig und bieten eine abgeschlossene Umgebung, in der die Anwendung ausgeführt wird.
  * **Container-Start und -Stopp:**
    * **Starten eines Containers:** Mit dem Befehl `docker run` wird ein Container aus einem Image erstellt und gestartet.
    * **Stoppen eines Containers:** Container können mit dem Befehl `docker stop` gestoppt werden, und mit `docker rm` können sie entfernt werden.
* **Grundlegende Docker-Befehle:**
  * **`docker build`** - Bau eines Docker-Images aus einem Dockerfile.
  * **`docker run`** - Starten eines Containers aus einem Image.
  * **`docker ps`** - Anzeigen der aktuell laufenden Container.
  * **`docker stop`** - Stoppen eines laufenden Containers.
  * **`docker logs`** - Anzeigen der Logs eines Containers.
