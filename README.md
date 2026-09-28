# Website-Leads Nürnberg

Anrufliste mit lokalen Betrieben, die keine eigene Website haben: Zielgruppe für den Verkauf von Websites.

- **App:** [`app/leads.html`](app/leads.html), veröffentlicht als claude.ai-Artifact „Website-Leads Nürnberg“.
  Status (Offen, Nicht erreicht, Rückruf, Interesse, Termin, Kunde, Kein Interesse), Notizen und Wiedervorlage
  werden in der Datenbank des Artifacts gespeichert. Export als CSV direkt aus der App.
- **Daten:** [`data/leads-nuernberg.json`](data/leads-nuernberg.json) und
  [`data/leads-nuernberg.csv`](data/leads-nuernberg.csv) (Semikolon, UTF-8 mit BOM, öffnet direkt in Excel).

## Wie die Liste entstanden ist

1. Branchen mit vielen kleinen Betrieben in öffentlichen Branchenbüchern gesucht (11880, Gelbe Seiten, Das Örtliche,
   Yelp, Cylex): Friseur, Schneiderei, Kfz, Maler, Fliesen, Fußpflege, Imbiss, Blumen, Metzgerei u. a.
2. Für jeden Treffer eine eigene Websuche nach dem Namen gemacht. Wer eine eigene Domain hat, ist rausgeflogen
   (etwa die Hälfte).
3. Übrig: 34 Betriebe mit Telefonnummer, Stand 28.09.2026. `website: "unklar"` heißt, dass es Hinweise auf eine
   alte Website gibt.

Die Daten stammen aus Suchergebnissen. Nummer und Adresse vor dem Anruf kurz gegenprüfen (Link „Google prüfen“
in der App).

## Rechtliches

Werbeanrufe bei Firmen sind nur mit mutmaßlicher Einwilligung erlaubt (§ 7 UWG). Werbe-E-Mails brauchen eine
vorherige ausdrückliche Einwilligung, also am Telefon fragen, ob ein Angebot per Mail geschickt werden darf.
