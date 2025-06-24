---
marp: true
theme: webinex
size: 16:9
paginate: true
header: 'OpenSearch Foundation | Titel des Workshops'
footer: '© 2025 Team Workshop | Vertraulich'
---

<!-- 
Dies ist Ihr Vorlagen-Baukasten für das 'webindex'-Theme.
Jede Folie unten ist eine Vorlage. Kopieren Sie den gesamten Block von `---` bis zum nächsten `---`
und fügen Sie ihn in Ihre eigene Präsentation ein.
-->

# Marp Vorlagen-Baukasten
### Theme: webindex

**Anleitung:**
- Jede Folie dient als Kopiervorlage.
- Ersetzen Sie einfach die Texte und Bilder.
- Nutzen Sie die Kommentare im Code als Hilfestellung.

---

<!-- _class: invert -->
<!-- Die Klasse 'invert' kehrt die Farben um – ideal für Titel und Abschlussfolien. -->

# Titel der Präsentation

### Ein aussagekräftiger Untertitel

**Ihr Name**
*Ihre Abteilung / Ihr Team*
*Datum*

---

<!-- Dies ist eine Standard-Inhaltsfolie. Der Inhalt wird automatisch zentriert. -->

## 🧭 Agenda / Was Sie erwartet

- **Einstieg & Kennenlernen:** Wir starten mit einer kurzen Vorstellungsrunde.
- **Thema 1:** Eine Einführung in die Grundlagen.
- **Thema 2:** Vertiefung mit praktischen Beispielen.
- **Workshop-Phase:** Jetzt sind Sie an der Reihe!
- **Zusammenfassung & Ausblick:** Die wichtigsten Erkenntnisse und nächste Schritte.

---

## Standard-Inhaltsfolie

Dies ist eine Vorlage für eine Folie mit normalem Text. Der Inhalt wird automatisch vertikal und horizontal zentriert, während der Text selbst für eine bessere Lesbarkeit linksbündig bleibt.

Hier können Sie Absätze, **fettgedruckten Text** und *kursiven Text* verwenden. Alles passt sich nahtlos in das Design ein.

---

## Folie mit einer Aufzählung

- Erster Punkt in der Liste. Listen sind ideal, um Informationen klar und übersichtlich zu strukturieren.
- Zweiter Punkt mit **wichtigen** Details.
    - Eingerückte Unterpunkte sind ebenfalls möglich.
    - Sie helfen dabei, komplexe Themen zu gliedern.
- Dritter und letzter Punkt in dieser Beispiel-Liste.

---

## 🗣️ Zitat oder wichtiger Hinweis

> "Das ist ein aussagekräftiges Zitat, das eine wichtige Botschaft hervorhebt. Blockquotes eignen sich hervorragend, um eine Aussage zu betonen."
>
> — Name der zitierten Person

---
<!-- Marp unterstützt ein 2-Spalten-Layout nativ mit der "bg left/right" Syntax. -->

## Bild und Text nebeneinander

![bg left:40% width:400px](https://dashboard.ows.eu/images/openwebindex.png)

### Titel neben dem Bild

- Hier können Sie die wichtigsten Punkte zum Bild erläutern.
- Die prozentuale Aufteilung der Spalten ist flexibel anpassbar.
- Ideal für die Vorstellung von Personen, Produkten oder Konzepten.

---

## Folie mit zentriertem Bild

Hier ist etwas Text, der ein Bild einleitet.

![center h:450 width:250px height:250px](https://dashboard.ows.eu/images/openwebindex.png)
<!-- 'center' kommt von unserer CSS-Utility. 'h:450' ist Marp-Syntax, um die Höhe zu steuern. -->

Ein kurzer Beschreibungstext unter dem Bild ist ebenfalls möglich.

---

## 💻 Folie mit einem Code-Block

Das `webindex`-Theme hat ein spezielles Syntax-Highlighting. Vergessen Sie nicht, die Sprache nach den drei Backticks anzugeben (z.B. `js`, `css`, `python`).

```js
// Beispiel-Code, um das Highlighting zu zeigen
function greet(name) {
  const message = `Hello, ${name}!`; // String-Highlighting
  const PI = 3.14; // Number-Highlighting

  // Ein Kommentar wird dezent dargestellt
  if (name) {
    console.log(message);
    return true;
  }
}