# Gynäkologische Praxis Musterfrau - Website

Willkommen bei der Website der Gynäkologischen Praxis Musterfrau. Diese Website wurde mit Quarto erstellt und wird automatisch auf GitHub Pages veröffentlicht.

## 📋 Website-Adresse

Die Website ist erreichbar unter: **https://jakobschumacher.github.io/praxisbeispiel/**

## ✏️ Inhalte bearbeiten - Einfache Anleitung

Sie können die Inhalte Ihrer Website ganz einfach über GitHub bearbeiten, ohne technische Kenntnisse. Hier ist eine Schritt-für-Schritt-Anleitung:

### Schritt 1: Datei zum Bearbeiten finden

1. Gehen Sie auf die GitHub-Seite dieses Projekts
2. Wählen Sie die Seite aus, die Sie bearbeiten möchten (alle Dateien enden auf `.qmd`):
   - `index.qmd` = Startseite
   - `team.qmd` = Team-Seite
   - `leistungen.qmd` = Leistungen-Seite
   - `kontakt.qmd` = Kontakt-Seite
   - `impressum.qmd` = Impressum
   - `datenschutz.qmd` = Datenschutzerklärung

### Schritt 2: Datei bearbeiten

1. Klicken Sie auf den Dateinamen (z.B. `team.qmd`)
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

Die zentralen Daten Ihrer Praxis (Name, Adresse, Telefon, Öffnungszeiten) stehen in der Datei **`_metadata.yml`** im Hauptverzeichnis.

**So ändern Sie die Stammdaten:**

1. Klicken Sie auf die Datei `_metadata.yml`
2. Klicken Sie auf das Stift-Symbol ✏️
3. Ändern Sie die gewünschten Daten (z.B. Telefonnummer, Öffnungszeiten)
4. Speichern Sie wie oben beschrieben

**Vorteil:** Diese Daten können in allen `.qmd` Dateien verwendet werden!

## 📱 Wichtige Dateien und Ordner

```
praxisbeispiel/
├── index.qmd            ← Startseite
├── team.qmd             ← Team-Seite
├── leistungen.qmd       ← Leistungen
├── kontakt.qmd          ← Kontakt
├── impressum.qmd        ← Impressum
├── datenschutz.qmd      ← Datenschutz
├── _quarto.yml          ← Hauptkonfiguration der Website
├── _metadata.yml        ← Zentrale Praxis-Stammdaten
├── custom.scss          ← Design-Anpassungen (SCSS)
├── styles.css           ← Zusätzliche CSS-Styles
└── .github/workflows/   ← GitHub Actions für automatisches Deployment
```

## 🎨 Design anpassen

### Farben ändern

Die Farben der Website sind in der Datei **`custom.scss`** definiert:

- Die Hauptfarbe ist `#2c5f7c` (ein dunkles Blau)
- Suchen Sie nach `$primary:` und ändern Sie die Farbe

### Navigation anpassen

Die Navigation können Sie in **`_quarto.yml`** unter `website:` → `navbar:` anpassen.

## ⚙️ GitHub Pages einrichten (Einmalig erforderlich)

Falls GitHub Pages noch nicht aktiviert ist:

1. Gehen Sie zu **Settings** (Einstellungen) in Ihrem Repository
2. Klicken Sie links auf **Pages**
3. Unter "Source" wählen Sie: **GitHub Actions**
4. Speichern Sie die Einstellung

Die Website wird dann automatisch unter `https://jakobschumacher.github.io/praxisbeispiel/` veröffentlicht.

## 📝 Markdown-Formatierung in Quarto

Die Inhalte sind in Quarto Markdown geschrieben. Hier sind die wichtigsten Formatierungen:

### Basis-Formatierung

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

### Quarto-spezifische Features

**Callout-Boxen** (Hinweis-Kästen):

```markdown
::: {.callout-note}
## Hinweis
Dies ist ein Hinweis
:::

::: {.callout-tip}
## Tipp
Dies ist ein Tipp
:::

::: {.callout-warning}
## Warnung
Dies ist eine Warnung
:::

::: {.callout-important}
## Wichtig
Dies ist wichtig
:::
```

**Tabellen:**

```markdown
| Spalte 1 | Spalte 2 |
|----------|----------|
| Wert 1   | Wert 2   |
| Wert 3   | Wert 4   |
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

Falls Sie Quarto lokal installiert haben:

### Installation

Quarto herunterladen und installieren von: https://quarto.org/docs/get-started/

### Befehle

```bash
# Vorschau im Browser (mit Live-Reload)
quarto preview

# Website rendern
quarto render

# Nur eine Seite rendern
quarto render index.qmd
```

## 🔍 Was ist Quarto?

Quarto ist ein modernes, wissenschaftliches Publishing-System, das auf Markdown basiert. Es bietet:

- **Einfache Syntax:** Wie normales Markdown, aber mit erweiterten Funktionen
- **Professionelle Layouts:** Vorgefertigte, responsive Themes
- **Flexibilität:** Unterstützt verschiedene Output-Formate (HTML, PDF, etc.)
- **Callout-Boxen:** Schöne Hervorhebungen für wichtige Informationen
- **Keine Programmierkenntnisse nötig:** Inhalte können direkt bearbeitet werden

## 📚 Weiterführende Links

- [Quarto Dokumentation](https://quarto.org/)
- [Quarto Markdown Grundlagen](https://quarto.org/docs/authoring/markdown-basics.html)
- [Quarto Website Guide](https://quarto.org/docs/websites/)
- [GitHub Pages Dokumentation](https://docs.github.com/pages)

---

**Viel Erfolg mit Ihrer Website!** 🎉
