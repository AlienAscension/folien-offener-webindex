# Folien für den Offenen Webindex

Dies ist ein kollaborativer Workspace zur Erstellung von Vortragsfolien mit [Marp](https://marp.app/), einem Framework zur Erstellung von Präsentationen im Markdown-Format.

## 🛠️ Voraussetzungen

Um die Markdown-Dateien in Präsentationen umwandeln zu können, wird **Marp CLI** benötigt. Stelle sicher, dass du [Node.js](https://nodejs.org/) (inkl. npm) installiert hast.

Anschließend installierst du Marp CLI global auf deinem System mit folgendem Befehl im Terminal:

```bash
npm install -g @marp-team/marp-cli
```

---

## 📁 Projektstruktur

```
├── media/ # Bilder zur Verwendung in Präsentationen
    └── Ein paar Bilddateien
├── themes/ # Zentrales Design (nicht verändern!)
│   ├── webindex.css
│   ├── webindex.css.map
│   └── webindex.scss
├── owi-workshop.md # Markdown-Datei für OWI-Workshop-Folien
├── owi-workshop.html # Exportierte HTML-Version des OWI-Workshops
├── owi-workshop.pdf # Exportierte PDF-Version des OWI-Workshops
├── vorlage.md # Beispiel-Markdown-Folien
├── vorlage.html # Beispiel-Export als HTML
└── README.md # Diese Anleitung
```

> **Wichtig:** Die Dateien im Ordner `themes/` enthalten das zentrale Design der Präsentationen und **dürfen nicht verändert werden**.

---

## 📝 Eigene Folien erstellen

1. **Markdown-Datei bearbeiten**

   Schreibe deine Präsentation in der Datei `vorlage.md`.
   Eine Folie wird durch `---` getrennt.

   Beispiel:

   ```markdown
   # Titel der Präsentation

   ---

   ## Agenda

   - Punkt 1  
   - Punkt 2
   ```

   👉 Syntaxhilfe: [Marp Markdown Guide](https://marpit.marp.app/image-syntax)

2. **Präsentation exportieren**

   Mit folgendem Befehl wandelst du die Markdown-Datei in eine HTML-Präsentation um:

   ```bash
   marp vorlage.md --html --theme themes/webindex.css
   ```

   Danach findest du die fertige Präsentation als `vorlage.html` im Projektordner.

3. **Präsentation anzeigen**

   Öffne `vorlage.html` im Browser – fertig!

---

## 🔁 Live-Vorschau (optional)

Wenn du beim Bearbeiten der Folien automatisch eine Vorschau erzeugen möchtest:

```bash
marp vorlage.md --html --theme themes/webindex.css --watch
```

---

## ❗ Hinweise

* **Designanpassungen sind nicht vorgesehen.** Bitte verwende ausschließlich die bereitgestellten Dateien.
* Du kannst beliebig viele neue Markdown-Dateien anlegen – nutze aber immer `themes/webindex.css` als Theme beim Export.

---

Bei Fragen oder Feedback melde dich gern per Issue oder Pull Request.

---
