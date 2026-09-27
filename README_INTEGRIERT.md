# JOBCENTER NACHWEISMAPPE · E-MAIL-INTEGRIERT

Diese Fassung übernimmt die vorhandene Dokumentenstruktur und ergänzt sie um einen vollständigen Offline-E-Mail-Nachweisbestand.

## Statistik

- Roh-Nachrichten: 225
- Eindeutige E-Mail-Beweisobjekte: 130
- Mailketten: 77
- Kategorien: 8
- E-Mails mit exakten Duplikatquellen: 95

## E-Mail als eigenständiges Nachweisobjekt

Jede eindeutige E-Mail hat:
- E-ID `E-xxxx`
- Originalkopie im EML-Format
- SHA-256-Prüfsumme
- Datum, Absender, Empfänger, CC, Betreff
- Kategorie und technische Beweisfunktion
- Mailketten-ID
- Prüfbeleg-Zuordnung B-01 bis B-10
- Angaben zu Anhängen
- lesbaren Dokumentbaustein

## Deduplizierung

`mbox(1)` bis `mbox(4)` enthalten teilweise identische Nachrichten. Identische Rohdaten werden über SHA-256 erkannt und nicht doppelt als eigenständiges Beweisobjekt gezählt. Die unterschiedlichen Quellstellen bleiben im Duplikatregister erhalten.

## Bestandsabgrenzung

Die vorhandene `Residea_service_OCR.pdf` verweist auf einen historischen Yahoo-Ordnerbestand von 155 E-Mails. Dieser historische Registerbestand wird nicht mit den aktuell eingelesenen mbox-Nachrichten gleichgesetzt.

## Fachliche Grenze

Automatische Kategorien und Zuordnungen sind Arbeitsindexierungen. Sie sind keine Sachverständigenfeststellungen und keine abschließende rechtliche Bewertung.
