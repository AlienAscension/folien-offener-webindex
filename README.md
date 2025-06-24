# Folien für den Offenen Webindex

Dies ist ein kollaborativer Workspace zur Erstellung von Vortragsfolien mit [Marp](https://marp.app/), einem Framework zur Erstellung von Präsentationen im Markdown-Format.

## 📁 Projektstruktur

```
├── README.md             # Diese Anleitung
├── themes/               # Design (nicht verändern!)
│   ├── webindex.css
│   ├── webindex.css.map
│   └── webindex.scss
├── vorlage.html          # Exportierte HTML-Präsentation (Beispiel)
└── vorlage.md            # Deine Markdown-Folien
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
   npx @marp-team/marp-cli vorlage.md --html --theme themes/webindex.css
   ```

   Danach findest du die fertige Präsentation als `vorlage.html` im Projektordner.

3. **Präsentation anzeigen**

   Öffne `vorlage.html` im Browser – fertig!

---

## 🔁 Live-Vorschau (optional)

Wenn du beim Bearbeiten der Folien automatisch eine Vorschau erzeugen möchtest:

```bash
npx @marp-team/marp-cli vorlage.md --html --theme themes/webindex.css --watch
```

---

## ❗ Hinweise

* **Designanpassungen sind nicht vorgesehen.** Bitte verwende ausschließlich die bereitgestellten Dateien.
* Du kannst beliebig viele neue Markdown-Dateien anlegen – nutze aber immer `themes/webindex.css` als Theme beim Export.

---

Bei Fragen oder Feedback melde dich gern per Issue oder Pull Request.

---
