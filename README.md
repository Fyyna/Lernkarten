# Lernkarten — Code Track 2.0

Minimalistische Lernkarten-App für den DTP-Unterricht an der Digital Talents Academy.

Kein Server. Kein Framework. Kein Bullshit. Eine einzige HTML-Datei, läuft offline.

---

## Setup

```bash
git clone https://github.com/Fyyna/Lernkarten.git
```

Datei `lernkarten.html` im Browser öffnen. Fertig.

---

## Bedienung

| Taste         | Funktion             |
|---------------|----------------------|
| Leertaste     | Karte umdrehen       |
| Pfeil rechts  | Nächste Karte        |
| Pfeil links   | Vorherige Karte      |
| Escape        | Zurück zur Übersicht |

Auf Mobile: Karte antippen zum Umdrehen, Buttons zum Navigieren.

---

## Eigenes Deck hinzufügen

Öffne `lernkarten.html` in einem Texteditor und suche das `decks`-Array. Neues Objekt rein, fertig:

```javascript
{
  title: "Dein Thema",
  description: "Kurze Beschreibung",
  cards: [
    { q: "Frage?", a: "Antwort." },
    { q: "Noch eine Frage?", a: "Noch eine Antwort." }
  ]
}
```

HTML-Tags in den Antworten sind erlaubt — `<br>` für Zeilenumbrüche, `<code>` für Code, `<strong>` für Fettdruck.

---

## Vorhandene Decks

- Hamming-Code — Fehlerkorrektur, Paritätsbits, Hammingdistanz
- Floating Point Numbers — Binäre Kommazahlen, IEEE 754, Epsilon-Vergleich

---

## Lizenz

Nimm's, lern damit, mach's besser.