---
description: Docker Compose
---

# Docker Compose

**Inhalt der Seite:**

* **Was ist Docker Compose?**
  * Docker Compose ist ein Tool zum Definieren und Ausführen von Multi-Container Docker-Anwendungen.
  * Mit einer einzigen YAML-Datei (`docker-compose.yml`) können mehrere Container konfiguriert und orchestriert werden.
* **Erstellen einer `docker-compose.yml`:**
  *   Beispiel für eine einfache Webanwendung mit einer Datenbank:

      ```
      version: '3'
      services:
        web:
          image: nginx
          ports:
            - "8080:80"
        db:
          image: mysql
          environment:
            MYSQL_ROOT_PASSWORD: example

      ```

**Docker Compose Befehle:**

* **`docker-compose up`** - Startet alle Container in der `docker-compose.yml`.
* **`docker-compose down`** - Stoppt und entfernt alle laufenden Container.
* **`docker-compose logs`** - Zeigt Logs aller Container an.
