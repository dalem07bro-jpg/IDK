# Website-Leads Bayern

Anrufliste mit lokalen Betrieben in Bayern, die keine eigene Website haben: Zielgruppe für den Verkauf von Websites.
Insgesamt **200 Leads in 22 Städten**, sortiert nach Stadt.

- **App:** [`app/leads.html`](app/leads.html), veröffentlicht als claude.ai-Artifact „Website-Leads Nürnberg“.
  Oben wählst du die Stadt oder „Alle Städte“. Bei „Sortiert: Stadt“ ist die Liste nach Städten gruppiert.
  Status (Offen, Nicht erreicht, Rückruf, Interesse, Termin, Kunde, Kein Interesse), Notizen und Wiedervorlage
  werden in der Datenbank des Artifacts gespeichert. Export als CSV direkt aus der App (aktuelle Stadt oder alle).
- **Pro Betrieb:** ausführliche Beschreibung, Leistungen, Bewertungen, Öffnungszeiten, bisheriger Online-Auftritt,
  ein Gesprächsansatz und Hinweise, was vor dem Anruf zu prüfen ist.
- **Anrufen:** Der Knopf öffnet die Telefon-App (`tel:`-Link) und kopiert die Nummer zusätzlich. Am Computer zeigt „QR“
  einen QR-Code, den du mit der Handy-Kamera scannst, dann wählt das Handy die Nummer.

## Daten

Alle Dateien sind CSV mit Semikolon und UTF-8 mit BOM, sie öffnen direkt in Excel.

- Alle Städte: [`data/leads-bayern.csv`](data/leads-bayern.csv) und [`data/leads-bayern.json`](data/leads-bayern.json)
  (sortiert nach Stadt, dann Name)
- Nur Nürnberg: [`data/leads-nuernberg.csv`](data/leads-nuernberg.csv), [`data/leads-nuernberg.json`](data/leads-nuernberg.json)
- Nur München: [`data/leads-muenchen.csv`](data/leads-muenchen.csv), [`data/leads-muenchen.json`](data/leads-muenchen.json)

| Stadt | Leads |
|---|---:|
| Amberg | 4 |
| Aschaffenburg | 9 |
| Augsburg | 14 |
| Bamberg | 6 |
| Bayreuth | 5 |
| Coburg | 4 |
| Erlangen | 6 |
| Fürth | 3 |
| Hof | 6 |
| Ingolstadt | 6 |
| Kempten | 12 |
| Landshut | 4 |
| München | 31 |
| Neu-Ulm | 3 |
| Nürnberg | 40 |
| Passau | 6 |
| Regensburg | 10 |
| Rosenheim | 6 |
| Schweinfurt | 12 |
| Straubing | 3 |
| Weiden | 4 |
| Würzburg | 6 |

Feld `website`:

- `keine`: Für den Betrieb wurde einzeln gesucht, es tauchte keine eigene Domain auf (162 Leads).
- `unklar`: Es gibt Hinweise auf eine Seite, z. B. eine alte Google-Seite, einen Baukasten oder eine automatisch
  erzeugte Seite (8 Leads).
- `ungeprüft`: Aus einem Branchenbuch übernommen, aber noch nicht einzeln gesucht (30 Leads). Vor dem Anruf kurz googeln.

## Wie die Liste entstanden ist

1. In jeder Stadt Branchen mit vielen kleinen Betrieben in öffentlichen Branchenbüchern gesucht (11880, Gelbe Seiten,
   Das Örtliche, Yelp, Cylex): vor allem Änderungsschneiderei, Döner und Imbiss, Fußpflege, Schuhmacher, Metzgerei,
   in Nürnberg und München auch Friseur, Kfz, Maler, Fliesen, Blumen u. a.
2. Für jeden Treffer eine eigene Websuche nach dem Namen gemacht. Wer eine eigene Domain oder eine eigene Bestellseite
   hat, ist rausgeflogen (etwa die Hälfte).
3. Stand 28.09.2026. Die Daten stammen aus Suchergebnissen. Nummer und Adresse vor dem Anruf kurz gegenprüfen
   (Link „Google prüfen“ in der App).

## Rechtliches

Werbeanrufe bei Firmen sind nur mit mutmaßlicher Einwilligung erlaubt (§ 7 UWG). Werbe-E-Mails brauchen eine
vorherige ausdrückliche Einwilligung, also am Telefon fragen, ob ein Angebot per Mail geschickt werden darf.
