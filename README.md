[README.md](https://github.com/user-attachments/files/27321153/README.md)
# Viewcount Guessr 🎮

Schätze die Zuschauerzahl zufälliger deutscher Twitch-Livestreams!

---

## Deployment auf GitHub Pages (einmalig, ~3 Minuten)

### Schritt 1 – GitHub Repository anlegen

1. Gehe auf [github.com/signup](https://github.com/signup) und erstelle einen Account (falls noch nicht vorhanden)
2. Gehe auf [github.com/new](https://github.com/new)
3. **Repository name:** `viewcount-guessr`
4. **Visibility:** Public ✓
5. Klicke **Create repository**

---

### Schritt 2 – index.html hochladen

1. Im leeren Repository auf **"uploading an existing file"** klicken
2. Die `index.html` aus diesem ZIP per Drag & Drop hochladen
3. **Commit changes** klicken

---

### Schritt 3 – GitHub Pages aktivieren

1. Im Repository auf **Settings** klicken
2. Links in der Sidebar: **Pages**
3. Unter *Source*: **Deploy from a branch**
4. Branch: **main** | Ordner: **/ (root)**
5. **Save** klicken

Nach ~60 Sekunden ist das Spiel erreichbar unter:
```
https://DEIN-GITHUB-NAME.github.io/viewcount-guessr
```

---

### Schritt 4 – Twitch Developer App erstellen

1. Gehe auf [dev.twitch.tv/console/apps/create](https://dev.twitch.tv/console/apps/create)
2. Logge dich mit deinem Twitch-Account ein
3. Formular ausfüllen:
   - **Name:** Viewcount Guessr
   - **OAuth Redirect URL:** `https://DEIN-GITHUB-NAME.github.io`
   - **Kategorie:** Website Integration
4. **Erstellen** klicken
5. App → **Verwalten** → **Client-ID** kopieren
6. **Neues Secret** generieren → **Client-Secret** kopieren

---

### Schritt 5 – Spielen

1. Öffne `https://DEIN-GITHUB-NAME.github.io/viewcount-guessr`
2. Client-ID und Client-Secret eintragen
3. **Verbinden & Spielen** klicken — fertig!

Die Zugangsdaten werden im Browser gespeichert, du musst sie nur einmal eingeben.

---

made by kieskauer
