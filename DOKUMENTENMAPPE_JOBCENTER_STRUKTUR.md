# DOKUMENTENMAPPE JOBCENTER – STRUKTUR UND REGISTER

**Objekt:** Gubener Straße 53a, 10243 Berlin  
**Bezugszeitraum:** 2014–2024, ergänzt um dokumentierte Vorgänge 2025–2026  
**Arbeitsstand:** 23. September 2026  
**Status:** Prüf- und Arbeitsmappe

## Führende Struktur

1. `00_DECKBLATT_DOKUMENTENMAPPE.md`
2. `00_BEWEISLOGIK_GESAMTSTRUKTUR.md`
3. `01_Akten_und_Sachstandsuebersicht.md`
4. `01_TECHNISCHE_FEHLERKETTE.md`
5. `02_Anschreiben_und_Pruefauftrag.md`
6. `02_BEWEISDOKUMENTATION_JOBCENTER_VERURSACHUNG.md`
7. `02_VERWALTUNGSVERANTWORTUNG.md`
8. `03_Beweisverzeichnis_und_Register.md`
9. `03_VORSATZNACHWEIS.md`
10. `04_JOBCENTER_HAFTUNG.md`
11. `05_REGRESS_FORDERUNGEN.md`
12. `06_PERSONEN_ZUORDNUNG.md`
13. `07_Schadensausgaben_BK_WW_Heizkosten.md`
14. `08_Rechnungen_und_Einzelbetraege.md`
15. `09_Beweislogik_und_Kausalzusammenhang.md`
16. `10_ANLAGENVERZEICHNIS_DIREKTLINKS.md`
17. `11_Abschluss_und_offene_Pruefpunkte.md`
18. `12_EMAIL_NACHWEISREGISTER.md`
19. `13_EMAIL_BEWEISZUORDNUNG.md`

## E-Mail-Nachweisarchitektur

- `EMAIL_NACHWEISE/` → je eindeutige E-Mail ein EML-Objekt
- `EMAIL_DOKUMENTBAUSTEINE/` → lesbarer Einzelbaustein je E-Mail
- `EMAIL_MASTER_INDEX.csv` → Vollregister
- `EMAIL_THREAD_INDEX.csv` → Mailketten
- `EMAIL_CATEGORY_INDEX.csv` → Kategorien
- `EMAIL_DUPLIKATE.csv` → SHA-256-Duplikate
- `QUELLEN_UND_INTEGRITAET/SOURCE_MANIFEST.csv` → Quellhashes

## Leitformel

```text
Originalquelle → E-Mail-ID / Beweis-ID
→ Feststellung → Rechen-/Technikprüfung
→ Beweisfrage → Gegenprüfung → konkreter Prüfauftrag
```
