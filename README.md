# Gynäkologische Praxis Musterfrau - Website

Willkommen bei der Website der Gynäkologischen Praxis Musterfrau. Diese Website wurde mit Hugo erstellt und wird automatisch auf GitHub Pages veröffentlicht.

## 📋 Website-Adresse

Die Website ist erreichbar unter: **https://jakobschumacher.github.io/praxisbeispiel/**

## ✏️ Inhalte bearbeiten - Einfache Anleitung

Sie können die Inhalte Ihrer Website ganz einfach über GitHub bearbeiten, ohne technische Kenntnisse. Hier ist eine Schritt-für-Schritt-Anleitung:

### Schritt 1: Datei zum Bearbeiten finden

1. Gehen Sie auf die GitHub-Seite dieses Projekts
2. Klicken Sie auf den Ordner **`content`**
3. Wählen Sie die Seite aus, die Sie bearbeiten möchten:
   - `_index.md` = Startseite
   - `team.md` = Team-Seite
   - `leistungen.md` = Leistungen-Seite
   - `kontakt.md` = Kontakt-Seite
   - `impressum.md` = Impressum
   - `datenschutz.md` = Datenschutzerklärung

### Schritt 2: Datei bearbeiten

1. Klicken Sie auf den Dateinamen (z.B. `team.md`)
2. Klicken Sie oben rechts auf das **Stift-Symbol** (✏️) mit der Beschriftung "Edit this file"
3. Bearbeiten Sie den Text nach Ihren Wünschen
4. **Wichtig:** Ändern Sie NICHT die ersten Zeilen zwischen den `---` Strichen (das ist der Metadaten-Bereich)

### Schritt 3: Änderungen speichern

1. Scrollen Sie nach unten zum Bereich "Commit changes"
2. Geben Sie eine kurze Beschreibung ein, z.B. "Team-Seite aktualisiert"
3. Klicken Sie auf den grünen Button **"Commit changes"**

### Schritt 4: Website wird automatisch aktualisiert

- Die Website wird automatisch neu gebaut und veröffentlicht
- Das dauert ca. 2-3 Minuten
- Sie können den Fortschritt unter "Actions" (oben im Menü) verfolgen
- Wenn ein grüner Haken erscheint, ist Ihre Änderung online!

## 🔧 Praxis-Stammdaten ändern

Die zentralen Daten Ihrer Praxis (Name, Adresse, Telefon, Öffnungszeiten) stehen in der Datei **`hugo.toml`** im Hauptverzeichnis.

**So ändern Sie die Stammdaten:**

1. Klicken Sie auf die Datei `hugo.toml`
2. Klicken Sie auf das Stift-Symbol ✏️
3. Ändern Sie die gewünschten Daten (z.B. Telefonnummer, Öffnungszeiten)
4. Speichern Sie wie oben beschrieben

**Vorteil:** Wenn Sie z.B. Ihre Telefonnummer hier ändern, wird sie automatisch auf allen Seiten aktualisiert!

## 📱 Wichtige Dateien und Ordner

```
praxisbeispiel/
├── content/              ← Hier sind alle Inhalte Ihrer Seiten
│   ├── _index.md        ← Startseite
│   ├── team.md          ← Team-Seite
│   ├── leistungen.md    ← Leistungen
│   ├── kontakt.md       ← Kontakt
│   ├── impressum.md     ← Impressum
│   └── datenschutz.md   ← Datenschutz
├── hugo.toml            ← Zentrale Konfiguration und Stammdaten
├── layouts/             ← HTML-Templates (nur für Entwickler)
└── static/              ← CSS und andere Dateien
```

## 🎨 Design anpassen

Das Design der Website ist in der Datei **`static/css/style.css`** definiert.

**Farben ändern:**
- Die Hauptfarbe der Website ist `#2c5f7c` (ein dunkles Blau)
- Sie können diese Farbe in der CSS-Datei suchen und durch eine andere ersetzen

## ⚙️ GitHub Pages einrichten (Einmalig erforderlich)

Falls GitHub Pages noch nicht aktiviert ist:

1. Gehen Sie zu **Settings** (Einstellungen) in Ihrem Repository
2. Klicken Sie links auf **Pages**
3. Unter "Source" wählen Sie: **GitHub Actions**
4. Speichern Sie die Einstellung

Die Website wird dann automatisch unter `https://jakobschumacher.github.io/praxisbeispiel/` veröffentlicht.

## 📝 Markdown-Formatierung

Die Inhalte sind in Markdown geschrieben. Hier sind die wichtigsten Formatierungen:

```markdown
# Überschrift 1
## Überschrift 2
### Überschrift 3

**Fetter Text**
*Kursiver Text*

- Listenpunkt 1
- Listenpunkt 2

1. Nummerierte Liste
2. Punkt zwei

[Link-Text](https://beispiel.de)
```

## 🆘 Hilfe und Support

- **Fehler rückgängig machen:** Jede Änderung wird in der Historie gespeichert. Sie können frühere Versionen unter "History" wiederherstellen.
- **Technische Probleme:** Schauen Sie unter "Actions", ob der Build erfolgreich war (grüner Haken).
- **Fragen:** Erstellen Sie ein "Issue" im GitHub-Repository.

## 📄 Rechtliche Hinweise

- Das **Impressum** und die **Datenschutzerklärung** sind rechtlich verpflichtend für deutsche Websites
- Passen Sie diese Seiten an Ihre tatsächlichen Daten an
- Bei Unsicherheiten konsultieren Sie einen Rechtsanwalt

## 🚀 Lokale Entwicklung (für Entwickler)

Falls Sie Hugo lokal installiert haben:

```bash
# Development-Server starten
hugo server -D

# Website bauen
hugo

# Mit Minifizierung bauen
hugo --minify
```

---

**Viel Erfolg mit Ihrer Website!** 🎉
