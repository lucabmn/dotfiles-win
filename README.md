## dotfiles-win 🪟

Windows-Konfiguration mit Starship & Co. 😄  
Hier sammle ich meine persönlichen Config-Files für Windows-Terminals & Shells.

---

### 🔎 Überblick

- **Repo**: [`lucabmn/dotfiles-win`](https://github.com/lucabmn/dotfiles-win)
- **Maintainer**: `lucabmn`
- **Zweck**: Persönliche **Dotfiles & Konfigurationen** für:
  - klassische `cmd`
  - PowerShell
  - Starship Prompt

Wenn du magst, kannst du dieses Repo forken oder als Inspiration für deine eigene Windows-Shell-Konfiguration nutzen. 😊

---

### 📁 Verzeichnisstruktur

- **`.cmd`** – Konfigurationen für die klassische Windows-Eingabeaufforderung (`cmd.exe`)
- **`.config`** – Konfigurationsdateien wie z. B. **Starship**
- **`.powershell`** – PowerShell-Profile & -Konfigurationen

---

### ⚙️ Dateien im Detail

#### `.cmd/settings.json`

- **Beschreibung**: JSON-Konfiguration für `cmd`
- **Besonderheit**:  
  Diese Datei hat **keinen festen Pfad**.  
  Sie wird über die **cmd-/Terminal-Einstellungen** eingefügt:
  - Einstellungen öffnen (unten links auf **JSON** / Konfiguration als JSON öffnen)
  - Den Inhalt von `settings.json` aus diesem Repo dort einfügen / übernehmen

So kannst du schnell dein bevorzugtes `cmd`-Setup wiederherstellen. 😊

---

#### `.config/starship.toml`

- **Beschreibung**: Starship-Prompt-Konfiguration
- **Empfohlener Speicherort** (Beispiel, wie bei mir):

  ```text
  C:\Users\%USERNAME%\.config\starship.toml
  ```

- **Verwendung**:
  - Starship installieren (siehe offizielle Doku)
  - In deiner Shell (cmd, PowerShell, bash etc.) Starship als Prompt konfigurieren
  - Sicherstellen, dass auf `C:\Users\%USERNAME%\.config\starship.toml` verwiesen wird

Damit bekommst du überall denselben schönen Prompt. ✨

---

#### `.powershell/Microsoft.PowerShell_profile.ps1`

- **Beschreibung**: PowerShell-Profil
- In dieser Datei legst du z. B. fest:
  - Aliases
  - Prompt-Anpassungen
  - Module, die automatisch geladen werden sollen

Um die Konfiguration zu verwenden:

1. Ziel-Pfad deines PowerShell-Profils ermitteln:

   ```powershell
   $PROFILE
   ```

2. Die Datei `Microsoft.PowerShell_profile.ps1` aus diesem Repo an den angezeigten Pfad kopieren (oder den Inhalt übernehmen).

Danach PowerShell neu starten – deine Konfiguration ist aktiv. 🙌

---

### 🚀 Verwendung dieses Repos

- Repo clonen oder als ZIP herunterladen
- Die jeweiligen Dateien in die richtigen Orte kopieren (siehe oben)
- Terminal/Shell neu starten

Fertig – Windows fühlt sich gleich viel mehr nach „deiner“ Umgebung an. 💻✨

---

### 💡 Hinweise

- Dieses Repo ist in erster Linie für mich (`lucabmn`) gedacht, aber natürlich darfst du dir alles anschauen, anpassen und nach deinen Wünschen verändern.
- Änderungen an den Configs kannst du lokal machen und wieder zurück in dieses Repo committen, um dein Setup versioniert zu behalten.

Viel Spaß mit deinen Windows-Dotfiles! 😎

