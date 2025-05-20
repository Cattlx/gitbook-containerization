---
description: Netwerke und Volumes
---

# Docker Netzwerke und volumes

**Inhalt der Seite:**

* **Docker-Netzwerke:**
  * **Was sind Netzwerke in Docker?** Docker verwendet Netzwerke, um Container miteinander zu verbinden und den Datenaustausch zu ermöglichen.
  * **Standardnetzwerke:** Docker bietet standardmäßig drei Netzwerke: `bridge`, `host` und `none`.
  * **Benutzerdefinierte Netzwerke:** Mit `docker network create` kann man benutzerdefinierte Netzwerke erstellen, um Container in isolierten Umgebungen zu verbinden.
* **Docker-Volumes:**
  * **Was sind Volumes?** Volumes sind persistent Speicherlösungen, die Container über verschiedene Starts hinweg behalten können.
  *   **Erstellen und Verwenden von Volumes:** Beispiel:

      ```
      docker volume create my-volume
      docker run -d -v my-volume:/data my-image
      ```

**Unterschied zu Bind-Mounts:** Volumes sind von Docker verwaltete Speicherorte, während Bind-Mounts auf das Dateisystem des Hosts verweisen.
