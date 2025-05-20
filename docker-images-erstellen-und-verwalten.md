# Docker Images erstellen und verwalten

#### 4. **Docker-Images erstellen und verwalten**

**Link zur Seite:** `04-docker-images-erstellen-und-verwalten.md`

**Inhalt der Seite:**

* **Das Dockerfile: Syntax und Best Practices**
  * **Einführung in das Dockerfile:** Das Dockerfile ist eine Textdatei, die alle Anweisungen enthält, um ein Docker-Image zu bauen.
  *   **Aufbau eines Dockerfiles:** Beispiel für ein einfaches Dockerfile:

      ```
      FROM node:14
      WORKDIR /app
      COPY . /app
      RUN npm install
      CMD ["node", "index.js"]

      ```
*
  * **Best Practices für Dockerfiles:**
    * Verwenden von offiziellen Images als Basis
    * Minimierung der Bildgröße durch Multi-Stage-Builds
    * Verwendung von `.dockerignore`, um unnötige Dateien auszuschließen
* **Docker-Images bauen und taggen:**
  * **Bauen eines Docker-Images:** Mit dem Befehl `docker build -t my-image:latest .` kann ein Image gebaut und mit einem Tag versehen werden.
  * **Tagging von Docker-Images:** Tags ermöglichen es, Versionen von Images zu verwalten. Beispiel: `my-image:v1.0`.
* **Docker-Images verwalten:**
  * **Liste der Docker-Images:** Mit `docker images` werden alle lokal gespeicherten Images angezeigt.
  * **Entfernen von Images:** Unnötige Images können mit `docker rmi` entfernt werden.
