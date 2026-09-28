# Website-Leads Nürnberg

Anrufliste mit lokalen Betrieben, die keine eigene Website haben: Zielgruppe für den Verkauf von Websites.

- **App:** [`app/leads.html`](app/leads.html), veröffentlicht als claude.ai-Artifact „Website-Leads Nürnberg“.
  Status (Offen, Nicht erreicht, Rückruf, Interesse, Termin, Kunde, Kein Interesse), Notizen und Wiedervorlage
  werden in der Datenbank des Artifacts gespeichert. Export als CSV direkt aus der App.
- **Pro Betrieb:** ausführliche Beschreibung, Leistungen, Bewertungen, bisheriger Online-Auftritt, ein Gesprächsansatz
  und Hinweise, was vor dem Anruf zu prüfen ist.
- **Anrufen:** Der Knopf öffnet die Telefon-App (`tel:`-Link) und kopiert die Nummer zusätzlich. Am Computer zeigt „QR“
  einen QR-Code, den du mit der Handy-Kamera scannst, dann wählt das Handy die Nummer.
- **Daten:** je Stadt als JSON und CSV (Semikolon, UTF-8 mit BOM, öffnet direkt in Excel):
  - Nürnberg, 34 Leads: [`data/leads-nuernberg.json`](data/leads-nuernberg.json), [`data/leads-nuernberg.csv`](data/leads-nuernberg.csv)
  - München, 28 Leads: [`data/leads-muenchen.json`](data/leads-muenchen.json), [`data/leads-muenchen.csv`](data/leads-muenchen.csv)

## Wie die Liste entstanden ist

1. Branchen mit vielen kleinen Betrieben in öffentlichen Branchenbüchern gesucht (11880, Gelbe Seiten, Das Örtliche,
   Yelp, Cylex): Friseur, Schneiderei, Kfz, Maler, Fliesen, Fußpflege, Imbiss, Blumen, Metzgerei u. a.
2. Für jeden Treffer eine eigene Websuche nach dem Namen gemacht. Wer eine eigene Domain hat, ist rausgeflogen
   (etwa die Hälfte).
3. Übrig: 34 Betriebe in Nürnberg und 28 in München, alle mit Telefonnummer, Stand 28.09.2026. `website: "unklar"` heißt, dass es Hinweise auf eine
   alte Website gibt.

Die Daten stammen aus Suchergebnissen. Nummer und Adresse vor dem Anruf kurz gegenprüfen (Link „Google prüfen“
in der App).

## Rechtliches

Werbeanrufe bei Firmen sind nur mit mutmaßlicher Einwilligung erlaubt (§ 7 UWG). Werbe-E-Mails brauchen eine
vorherige ausdrückliche Einwilligung, also am Telefon fragen, ob ein Angebot per Mail geschickt werden darf.
