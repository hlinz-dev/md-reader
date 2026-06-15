# MD Reader

Ein schlanker unter Mithilfe von Claude Code erstellter, serverloser Markdown- und PDF-Viewer für den Browser. Keine Installation, keine Abhängigkeiten – einfach die HTML-Datei öffnen.

## Funktionen

- Markdown-Dateien rendern (GFM, Tabellen, Code-Highlighting, Task-Listen)
- Mermaid-Diagramme inline rendern (` ```mermaid ` – Flowchart, Sequenz, Gantt, ER, Mindmap)
- Charts inline rendern (` ```chart ` – Balken, Linien, Torte etc. via Chart.js JSON)
- PDF-Dateien anzeigen mit Zoom und Seitennavigation
- Automatisches Inhaltsverzeichnis in der Seitenleiste
- Drag & Drop, lokale Dateien und URL-Laden
- Farbthemen anpassbar
- Vollständig offline nutzbar

## Nutzung

1. `md-reader.html` im Browser öffnen
2. Markdown- oder PDF-Datei per Drag & Drop ablegen, Ordner-Button oder URL eingeben

## Lizenz

MIT License – Copyright © 2025 Holger Linz

---

## Changelog

### 0.9.3
- Mermaid.js 9 inline eingebettet: Diagramme via ` ```mermaid ` (Flowchart, Sequenz, Gantt, ER, Mindmap)
- Chart.js 4 inline eingebettet: Charts via ` ```chart ` (JSON-Konfiguration)

### 0.9.2
- Verwendete Bibliotheken mit Lizenzangaben im Info-Bereich ergänzt (marked, highlight.js, PDF.js, Tabler Icons)

### 0.9.1
- Inhaltsverzeichnis-Rendering korrigiert (marked v9 Kompatibilität)
- PDF-Zoom repariert (Zoom ändert jetzt sichtbare Seitengröße)
- Info-Button mit Hilfe, Haftungsausschluss, Lizenz und Kontakt hinzugefügt

### 0.9.0
- Initiale Version
