# 🧭 ABC-Expedition — Das Alphabet kennen & Wörter richtig ordnen

Interaktives Lernspiel für **Klasse 1–3 (Förderunterricht, Sprachförderung, DaZ)** aus der Reihe *Förderfreude Games*.
Die Kinder reisen mit einem kleinen Expeditionsbus über eine gemalte Buchstabenroute. Auf der Reise üben sie das Alphabet und das **richtige Ordnen nach dem ABC** – von einzelnen Buchstaben bis zu Wörtern mit gleichem Anfang.

## 🗺️ Die sieben Stationen
1. **Die Buchstabenstrecke** – „Bring das ABC in Ordnung!“ Durcheinander liegende Buchstaben ordnen.
2. **Die verlorene Wegmarke** – „Welcher Buchstabe fehlt?“ Ein oder mehrere Buchstaben im ABC-Abschnitt ergänzen.
3. **Die Buchstaben-Nachbarn** – „Wer kommt davor und danach?“ Vorgänger und Nachfolger finden.
4. **Die Gepäcksortierung** – „Sortiere die Wörter nach dem ABC!“ Gepäckanhänger mit Wörtern ordnen.
5. **Der Genau-Hinschau-Posten** – „Schau auf den nächsten Buchstaben!“ Wörter mit gleichem Anfang vergleichen.
6. **Der freie Platz** – „Wo gehört das Wort hin?“ Ein neues Wort in eine ABC-Reihe einordnen.
7. **Die große ABC-Expedition** – alle sechs Aufgabenarten im Wechsel, nie dieselbe Art zweimal hintereinander.

Ablauf: Station wählen → Stufe (leicht / mittel / schwer) → spielen.
Alle Aufgaben lassen sich **ziehen (Maus oder Finger) oder antippen**; zusätzlich ist alles per **Tastatur** bedienbar.

## 🚌 Fortschritt
Eine Runde endet nach **8 richtig gelösten Aufgaben** (nicht nach 8 Versuchen). Für jede richtige Aufgabe fährt der Bus zur nächsten von 8 Haltestellen. Am Ziel: **„Expedition geschafft!“** mit „Noch eine Runde“ und „Zurück zur Auswahl“.
Kein Zeitlimit, keine Punkte, kein Punktabzug, keine Leben, kein Game Over, kein Highscore, kein Wettbewerb.
Falsche Antworten geben einen kurzen, freundlichen Tipp („Welcher Buchstabe kommt direkt nach M?“, „Beide Wörter beginnen mit H. Welcher zweite Buchstabe kommt im ABC zuerst?“), **verraten die Lösung nicht** und bringen keinen Fortschritt.

## 🎚️ Stufen
| | Leicht | Mittel | Schwer |
|---|---|---|---|
| Buchstabenstrecke | 3–4 Buchstaben, nah beieinander | 4–6, ganzes ABC | 5–7, große Abstände |
| Wegmarke | 1 Lücke, 3 Antworten | 1–2 Lücken | 2–3 Lücken, längere Wege |
| Nachbarn | nur davor **oder** danach | davor und danach | davor und danach, mehr Auswahl |
| Gepäcksortierung | 3–4 vertraute Wörter, alle mit anderem Anfang | 4–5 Wörter, 2 beginnen gleich | 5–6 Wörter, mehrere beginnen gleich |
| Genau-Hinschau | 3 Wörter, 2. Buchstabe | 3–4 Wörter, 2. Buchstabe | 4–5 Wörter, auch 3. Buchstabe |
| Freier Platz | alle Wörter beginnen verschieden | teils gleicher Anfang | 2. oder 3. Buchstabe entscheidet |

**ABC-Leiste:** in der leichten Stufe an (abschaltbar), in der mittleren über die Hilfe zuschaltbar, in der schweren nie sichtbar.

## 🔤 Material und Sortierung
- **388 kindgerechte Wörter** in 13 Themenbereichen (Tiere, Schule, Familie, Zuhause, Essen, Kleidung, Natur, Wetter, Spielzeug, Freizeit, Fahrzeuge, Körper, Alltag); 121 davon sind „sehr vertraut“ und werden in der leichten Stufe genutzt.
- Das Alphabet besteht aus **A–Z**. Ä, Ö, Ü und ß werden **nicht** als Zusatzbuchstaben einsortiert; in allen Sortieraufgaben kommen keine Wörter mit Umlauten oder ß vor.
- Sortierung: Buchstabe für Buchstabe, das kürzere Wort zuerst. Wörter, die der Anfang eines anderen Wortes sind (z. B. *Haus* / *Hausaufgabe*), werden nie kombiniert.
- **Jede erzeugte Aufgabe wird automatisch geprüft**: Lösung sortiert, unabhängige Gegenprobe mit der Browser-Sortierung, genau eine Lösung (Wegmarke: genau eine zusammenhängende Belegung; Freier Platz: genau eine Einfügeposition).
- Rundenplan: keine identischen Aufgaben, keine auffälligen Wortwiederholungen, Alphabetbereiche ausgewogen, richtige Antwort nie zweimal an derselben Stelle hintereinander.

## 🔊 Sprachausgabe
Optional über die Browser-Sprachausgabe (de-DE): Aufgabenstellungen und Wörter. **Buchstaben werden bewusst nicht vorgelesen**, weil Browserstimmen sie oft missverständlich sprechen. Ohne Sprachausgabe im Browser werden alle Lautsprecher-Knöpfe ausgeblendet; das Spiel bleibt vollständig spielbar.

## 📱 Geräte & Barrierefreiheit
Smartboard, PC, Laptop, Tablet, Smartphone; Maus, Touch, Tastatur; Hoch- und Querformat (von 360 × 640 bis 2560 × 1440). Auf Laptops ab ca. 600 px Höhe braucht die Spieloberfläche kein vertikales Scrollen. Auf sehr kleinen Smartphones im Querformat erscheint ein freundlicher Hinweis, dass das Hochformat besser passt.
Touch-Ziele ≥ 44 px, sichtbare Fokusrahmen, Kontraste nach WCAG AA, Information nie nur durch Farbe, `prefers-reduced-motion` wird beachtet.

## 🛠️ Technik
Eine einzige `index.html` (HTML, CSS, Vanilla JavaScript). Keine Frameworks, keine externen Bilder, Schriften oder APIs, keine Cookies, kein Tracking, keine Datenspeicherung. Alle Illustrationen (Karte, Bus, Kinder, Stationssymbole) sind eigene SVGs.
**Netlify:** Ordner per Drag & Drop (Build command leer, Publish directory `.`).
**GitHub:** `index.html`, `README.md`, `.gitignore` (+ optional `arbeitsblaetter/`, `pruefung/`).

## 🖨️ Arbeitsmaterialien (`arbeitsblaetter/`, HTML + PDF)
- `teilnehmeruebersicht` – A4 quer, 30 Kinder × 10 Expeditionen
- `arbeitsblatt-unterwegs-im-abc` – Fehlende Buchstaben, Nachbarn, Buchstaben ordnen, Welcher Buchstabe zuerst?
- `arbeitsblatt-woerter-ordnen` – Gepäckstücke sortieren, gleicher Anfang, Wo gehört das Wort hin?, Welches Wort zuerst?
- jeweils zusätzlich `-loesung` (für Lehrkräfte)

## ✅ Prüfmaterial (`pruefung/`)
`materialuebersicht.html`, `.pdf`, `.csv` – Wortpool mit Kategorie, Anfangsbuchstabe und Vertrautheit, Stationen/Stufen, Sortierprüfung, Beispielaufgaben mit Lösungen, Lösungen der Arbeitsblätter und Testergebnisse.

## 🧪 Qualitätssicherung
Daten- und Pool-Audit (0 Fehler) · Simulation von über 25.000 Runden mit mehr als 200.000 Aufgaben (0 Fehler) · alle 7 Stationen × 3 Stufen als volle Runden über die Oberfläche inkl. falscher Antworten und Hinweisen · Maus-Ziehen, Touch-Ziehen, Tippen, Tastatur · Betrieb mit und ohne Sprachausgabe · Reduced Motion · 12 Bildschirmgrößen · Konsole ohne Fehler.
