# Beweislogik und Zuordnung für das Jobcenter

**Arbeitsdatei:** `beweislogik_jobcenter_zuordnung.md`  
**Leitrepository:** [`diewand-hue/wss`](https://github.com/diewand-hue/wss)  
**Zielsammlung:** [`diewand-hue/jobcenter-beweissammlung-gubener-53a`](https://github.com/diewand-hue/jobcenter-beweissammlung-gubener-53a)  
**Stand der Prüfung:** 20. September 2026  
**Bearbeitungsstatus:** Arbeitsgrundlage; noch keine abschließende Tatsachen- oder Rechtsprüfung

> **Wichtiger Hinweis:** Dieses Dokument ordnet die bisher im Repository behaupteten Tatsachen, Nachweise und offenen Fragen. Formulierungen wie „Fehler“, „Verantwortung“, „Manipulation“ oder „Verursachung“ sind, solange kein Originalbeleg oder Sachverständigennachweis vorliegt, als **Prüfbehauptung**, **Indiz** oder **offene Hypothese** zu behandeln. Eine gerichtliche oder rechtliche Verbindlichkeit wird nicht zugesichert.

---

## 1. Zweck und Prüfziel

Die Sammlung soll dem Jobcenter nachvollziehbar beantworten:

1. Welche konkreten Kosten- oder Abrechnungspositionen sind streitig?
2. Welche Originalunterlage belegt jeweils die Position?
3. Welche technische oder administrative Ursache wird behauptet?
4. Was spricht dafür, dass die Kosten nicht durch ein schuldhaftes Verhalten der leistungsberechtigten Person verursacht wurden?
5. Welche Stelle kann zu welchem Zeitpunkt Kenntnis gehabt oder eine Prüfung durchführen müssen?
6. Welche Unterlagen fehlen noch, damit eine belastbare Entscheidung möglich ist?
7. Welche konkrete Prüfung oder Entscheidung wird vom Jobcenter verlangt?

Die Beweisführung erfolgt getrennt nach **Tatsache**, **Beleg**, **Schlussfolgerung**, **Verantwortungsannahme** und **offener Gegenprüfung**. Dadurch werden Vermutungen nicht als bereits bewiesene Tatsachen ausgegeben.

---

## 2. Repositories und bereits festgestellte Inhalte

### 2.1 Leitrepository `diewand-hue/wss`

Im aktuellen Hauptzweig wurden unter anderem folgende Dateien festgestellt:

| Datei | Verwendungszweck in dieser Sammlung | Status |
|---|---|---|
| `Sammelmappe_Verteidigung_Widerklage_Schade_final.docx` | vorhandene Sammelmappe / Ausgangsentwurf | zu prüfen; Inhalt nicht automatisch als verifiziert übernehmen |
| `systematische-verknupfung-von-nachweiskette-und-beweislogik.docx` | Beweislogik und Nachweiskette | zu extrahieren |
| `DRUCK_Pruefbericht_mit_Jobcenter_Aufforderung.html` | Jobcenter-bezogener Prüfbericht | zu extrahieren |
| `DRUCK_Nur_Jobcenter_Aufforderung.html` | Aufforderungsentwurf | zu extrahieren |
| `01_TECHNISCHE_FEHLERKETTE.pdf` | technische Fehlerkette | Anlage / Referenz |
| `Foto-Feststellungen_und_Nachweiszuordnung...5.pdf` | Fotos und Zuordnung | Anlage / Referenz |
| `Video-Feststellungen und Nachweiszuordnung.pdf` | Videos und Zuordnung | Anlage / Referenz |
| `1aSchadensAusgaben(BK_WW_Heizkosten (2)).csv` | Kosten-, BK-, Warmwasser- und Heizkostendaten | Zahlenquelle; mit Originalabrechnungen abgleichen |
| `bk.py` | Berechnungs-/Auswertungsskript | Rechenweg prüfen und reproduzierbar dokumentieren |
| `bwematri.xlsm` | Tabellen-/Auswertungsdatei | Inhalt, Makros und Datenherkunft prüfen |
| `mon_sep_14_2026_umfassende_sammelmappe_fur_jobcenter_erstellen.json` | strukturierte Arbeitsdaten | Schema, Quellen und Vollständigkeit prüfen |
| `wed_sep_16_2026_umfassende_sammelmappe_fur_jobcenter_erstellen.zip` | Paket-/Arbeitsstand | entpacken und Dateiliste/Prüfsummen erfassen |
| `Einzelrechnungsbeträge_Adobe.rtfd.zip` und Variante mit abweichender Unicode-Schreibweise | Einzelbeträge / Rechnungsnotizen | Duplikatverdacht; nicht doppelt zählen |

Der vom Auftraggeber zuvor genannte Commit `641fb06b76928f165f63ed10cbd4675f0a85464e` konnte in der sichtbaren Historie von `diewand-hue/wss` nicht bestätigt werden. Er wird daher in dieser Datei **nicht als geprüfte Quelle** verwendet. Der genaue Commit kann später als Anlage mit vollständiger URL, Commitdatum und Datei-Hashes nachgereicht werden.

### 2.2 Zielrepository `diewand-hue/jobcenter-beweissammlung-gubener-53a`

Bereits vorhanden sind:

- `00_BEWEISLOGIK_GESAMTSTRUKTUR.md`
- `01_TECHNISCHE_FEHLERKETTE.md`
- `02_BEWEISDOKUMENTATION_JOBCENTER_VERURSACHUNG.md`
- Verzeichnis `Importiert`
- Verzeichnis `untitled folder` mit Duplikaten der beiden ersten Markdown-Dateien
- `.DS_Store` als nicht sachbezogene Metadatei

**Bereinigungshinweis:** Vor der Endfassung sind die doppelten Dateien und nicht sachbezogenen Metadaten zu inventarisieren. Die vorhandenen Markdown-Dateien enthalten teilweise starke rechtliche Schlussfolgerungen; sie werden in dieser Arbeitsdatei als Angaben aus dem Bestand, nicht als unabhängig bestätigte Tatsachen behandelt.

---

## 3. Kernthese der Sammlung – neutral formuliert

Nach dem derzeitigen Aktenbestand wird behauptet, dass bei einer Wohnung in der **Gubener Straße 53a, 10243 Berlin**, über mehrere Jahre technische Mängel, unklare Messwerte und Abrechnungsauffälligkeiten zusammenwirkten. Daraus sollen Nachzahlungen bzw. Unterkunftskosten entstanden sein, deren Ursache nicht im Verhalten der leistungsberechtigten Person, sondern in der Gebäudetechnik, der Verwaltung, dem Messdienst oder der Abrechnung liegen könne.

Diese These ist in folgende prüfbare Teilthesen zu zerlegen:

- **T1 – Technischer Mangel:** Die Heizungs- oder Warmwasseranlage arbeitete zeitweise nicht ordnungsgemäß.
- **T2 – Messabweichung:** Heizkostenverteiler oder Warmwasserzähler lieferten Werte, die mit den tatsächlichen Betriebsbedingungen nicht plausibel zusammenpassen.
- **T3 – Abrechnungsabweichung:** Einzelne Jahresabrechnungen weichen erheblich von Vorjahren ab oder enthalten unklare Zuordnungen.
- **T4 – Kenntnis/Anzeige:** Verwaltung oder Eigentümerin wurden über Mängel informiert und reagierten möglicherweise nicht ausreichend.
- **T5 – Kein Mieter-Verschulden:** Die strittigen Mehrkosten waren durch die betroffene Person nicht steuerbar oder vermeidbar.
- **T6 – Jobcenter-Prüfung:** Das Jobcenter soll offenlegen, auf welcher Grundlage die strittigen Kosten berücksichtigt, übernommen oder bewertet wurden.

---

## 4. Beweiskette: Tatsache → Beleg → Schlussfolgerung → Adressat

| ID | Zu beweisende Tatsache | Primärbeleg | Ergänzender Beleg | Vorläufige Schlussfolgerung | Adressat / Prüfauftrag |
|---|---|---|---|---|---|
| B-01 | Mängel an Heizung/Schimmel wurden früh angezeigt | Originalbericht Otto Richter GmbH vom 07.03.2017; Mängelanzeige vom 25.11.2016 | E-Mail-/Mängelchronologie | Kenntnis eines technischen Problems seit spätestens 2016/2017 | Verwaltung/Eigentümerin: Originalbericht und Reparaturakte vorlegen |
| B-02 | Heizungsausfälle bestanden über längere Zeit | Chronologie „Heizung M1 H5.csv“ bzw. Originalkommunikation | Temperaturprotokolle, Rechnungen für Zusatzheizung | Nutzung der Zentralheizung war möglicherweise eingeschränkt | Verwaltung: Reparaturaufträge, Termine, Abschlussberichte vorlegen |
| B-03 | Eigene Zusatzheizung wurde genutzt | Originalrechnungen, Zahlungsnachweise, Verbrauchsdaten | Temperaturmessungen | Mehrkosten können eine Folge des Mangels statt freiwilliger Mehrnutzung sein | Jobcenter: Kausalität und Erforderlichkeit prüfen |
| B-04 | Thermostat-/Stellventilereignis am 27.02.2023 | Original-E-Mail von Michelle Genrich | Vorher-/Nachher-Fotos, Handwerkerrechnung | Regelbarkeit der Heizung könnte verändert worden sein | Verwaltung/Handwerker: Auftrag, Leistungsbeschreibung und Abnahme vorlegen |
| B-05 | Heizkostenverteilerwerte stiegen nach 2017 stark an | Originalabrechnungen und Ableseprotokolle 2014–2021 | `1aSchadensAusgaben...csv`, Tabellen | Auffälligkeit; allein noch kein Beweis für Defekt oder Fehlabrechnung | Messdienst: Geräte-ID, Bewertungsfaktor, Ableseweg und Plausibilisierung vorlegen |
| B-06 | Warmwasserposition 2024 beträgt laut Bestand 1.352,52 € beim Mieter | Originalabrechnung 2024 | Vergleich 2018–2023; Video-/Fotoprotokolle | erhebliche Abweichung vom behaupteten Vergleichswert | Abrechnung auf Kostenart, Umlageschlüssel, Zählerstand und Zeitraum prüfen |
| B-07 | Im Gebäudegesamt werden 2024 29.447,14 € Warmwasser und 0,00 € Heizung behauptet | vollständige Gebäudeabrechnung 2024 | Einzelabrechnung, Wirtschafts-/Messdaten | starke Plausibilitätsauffälligkeit; Zahlen müssen zuerst aus Originalen bestätigt werden | Verwaltung/Messdienst: korrigierte Gesamtabrechnung und Rohdaten anfordern |
| B-08 | Für 2022 wird eine Gesamtzahl von 11.350.252,00 € behauptet | Originalabrechnung 2022 | 2021-/2023-Abrechnung, Konten-/Umlagekreisunterlagen | offensichtliche Auffälligkeit, aber Quelle und Bezugsgröße müssen geklärt werden | Jobcenter: keine Übernahme ohne Original- und Plausibilitätsprüfung |
| B-09 | Mieteranteil und Gebäudegesamt werden möglicherweise vermischt | Einzelabrechnung, Gebäudeabrechnung, Wohn-/Gesamtfläche | CSV, XLSM, Berechnungsskript | mehrere Zahlen im Bestand sind nicht ohne Weiteres vergleichbar | Rechenblatt mit Einheiten, Flächen, Zeitraum und Umlageschlüssel erstellen |
| B-10 | Jobcenter erhielt oder verarbeitete strittige Abrechnungen | Jobcenterakte, Bescheide, Zahlungsnachweise | Schriftverkehr/Anträge | erst nach Akteneinsicht lässt sich eine Behördenprüfung bewerten | Jobcenter: Aktenauszug, Prüfvermerke und Berechnungsgrundlage anfordern |

---

## 5. Zahlen- und Plausibilitätsregister

Die nachfolgenden Werte stammen aus den vorhandenen Markdown-Arbeitsständen und sind **noch nicht als Originalzahlen bestätigt**:

| Wert / Aussage | Quelle im Arbeitsbestand | Erforderliche Bestätigung |
|---|---|---|
| 5.394 HKV-Einheiten 2014 | `01_TECHNISCHE_FEHLERKETTE.md` | Originalabrechnung/Ablesebeleg 2014 |
| 5.198 HKV-Einheiten 2015 | dort | Originalabrechnung/Ablesebeleg 2015 |
| 8.457 HKV-Einheiten 2017 | dort | Gerätewechsel-, Bewertungs- und Ablesedaten |
| 10.942 HKV-Einheiten 2018 | dort | Originalabrechnung und Verbrauchsaufstellung |
| 10.684 HKV-Einheiten 2019 | dort | Originalabrechnung und Ableseprotokoll |
| 8.407 HKV-Einheiten 2020 | dort | Originalabrechnung und Ableseprotokoll |
| 13.448 HKV-Einheiten 2021 | dort | Originalabrechnung und Ableseprotokoll |
| 29.447,14 € Warmwasser Gebäude 2024 | dort / `02...md` | Gebäudeabrechnung 2024 im Original |
| 1.352,52 € Warmwasser Mieter 2024 | dort / `02...md` | Einzelabrechnung 2024 und Umlageschlüssel |
| 0,00 € Heizkosten 2024 | dort | vollständige Abrechnung und Messdienstbestätigung |
| 5.675.126,00 € + 5.675.126,00 € für 2022 | `00...md`, `01...md` | Originalabrechnung 2022; Klärung, ob Gebäude-, Kosten- oder OCR-Wert |
| 106.800,00 € Vorauszahlung 2022 | `01...md` | Mietkonto und Originalabrechnung |
| ca. 58,44 m² Wohnfläche | `01...md` | Mietvertrag oder aktuelle Flächenberechnung |
| ca. 3.500 m² Gesamtfläche | `01...md` | Aufteilungs-/Wirtschaftseinheit-Nachweis |

### Rechenregeln für die weitere Bearbeitung

- Jeden Geldbetrag mit **Jahr, Abrechnungszeitraum, Ebene (Gebäude/Wohnung), Kostenart und Quelle** speichern.
- Dezimaltrennzeichen, Währung und Einheit ausdrücklich dokumentieren.
- OCR- oder Übertragungsfehler nicht stillschweigend korrigieren; Originalwert und korrigierter Prüfwert nebeneinander ausweisen.
- Prozentangaben nur mit der zugrunde liegenden Formel übernehmen.
- „+545 %“ muss anhand von Ausgangswert und Vergleichsjahr nachgerechnet werden.
- Ein Gebäude-Gesamtbetrag darf nicht unmittelbar als individueller Leistungs- oder Schadensbetrag verwendet werden.

---

## 6. Foto- und Videobeweise: Aufnahme- und Integritätsstandard

Für jedes Bild oder Video wird eine eigene Kennung benötigt:

`MED-YYYY-NNN` → z. B. `MED-2026-001`

Zu erfassen sind:

- Originaldateiname und Repository-Pfad
- Dateityp und Dateigröße
- SHA-256-Prüfsumme der Originaldatei
- Aufnahmezeitpunkt aus Metadaten und, falls abweichend, behaupteter Zeitpunkt
- Aufnahmeort und dargestelltes Objekt
- aufnehmende Person und Verwahrungskette
- unverändertes Original sowie Bearbeitungskopie
- kurze sachliche Beschreibung ohne technische Schlussfolgerung
- Bezug zu B-02, B-04, B-06 oder einer anderen Beweis-ID
- mögliche alternative Erklärung
- erforderliche fachkundige Prüfung

**Vorläufige Zuordnung aus dem Bestand:**

- Fotos zum Thermostat-/Stellventilbereich → B-04
- Videos zur Dauerrotation bzw. Entlüftung → B-05/B-06, jedoch nur als Beobachtungsbeleg
- Temperaturmessungen → B-02/B-03
- Video- oder Bildmaterial allein beweist noch nicht Ursache, Messfehler, Verantwortlichkeit oder Vorsatz. Dafür sind Messdaten, Geräteprüfung oder ein Sachverständigenbefund erforderlich.

---

## 7. Verantwortlichkeitsmatrix – vorsichtig formuliert

| Stelle | Im Bestand zugeschriebene Rolle | Zu prüfender Pflichtbereich | Noch erforderlicher Nachweis |
|---|---|---|---|
| Taekker Immobilienverwaltung GmbH | frühere Verwaltung bis ca. 2016 | Umgang mit Schimmel-/Heizungsmeldungen und Übergabe an Nachfolge | Verwaltungsakte, Aufträge, Übergabeprotokoll |
| RESIDEA Immobilien Management GmbH | Verwaltung ab ca. 2016 | Mängelbearbeitung, Abrechnungskontrolle, Beauftragung/Abnahme | vollständiger Schriftverkehr, Aufträge, Prüf-/Abnahmeprotokolle |
| White Tulip S.à r.l. | Eigentümerin laut Bestand | Eigentümerkenntnis und Organisation der Instandhaltung | Vertrag/Vertretung, Meldungen, interne Entscheidungen |
| Minol bzw. Messdienstleister | Messung/Abrechnung laut Zeitraum | Geräte, Ablesungen, Bewertungsfaktoren, Plausibilitätsprüfung | Geräte-IDs, Rohdaten, Eich-/Service-/Kalibrierbelege |
| Firma Paschke / weitere Fachfirmen | mögliche Reparaturausführung | konkrete Arbeiten am Stellventil/Heizung | Auftrag, Rechnung, Arbeitsbericht, Fotos, Abnahme |
| Jobcenter | Leistungs- und Aktenentscheidung | Kenntnis, Akteninhalt, Berechnung, Sachverhaltsaufklärung | Verwaltungsakte, Prüfvermerke, Bescheide, Berechnungsblätter |

Die Matrix weist keine Schuld verbindlich zu. Sie bestimmt nur, bei welcher Stelle die jeweiligen Originalunterlagen am ehesten zu erfragen sind.

---

## 8. Konkreter Prüfauftrag an das Jobcenter

Es soll schriftlich um folgende Auskünfte gebeten werden:

1. Welche Abrechnungen und Nachforderungen lagen der jeweiligen Leistungsentscheidung zugrunde?
2. Wurden Gebäude- und Wohnungswerte voneinander getrennt geprüft?
3. Welche Beträge wurden tatsächlich als Unterkunfts- oder Heizkosten berücksichtigt?
4. Gibt es Plausibilitäts-, Rückfrage- oder Prüfvermerke zu den auffälligen Zahlen für 2022 und 2024?
5. Wurde die Verwaltung oder der Messdienst zur Stellungnahme aufgefordert?
6. Welche Unterlagen fehlen aus Sicht des Jobcenters noch?
7. Auf welcher Rechts- und Tatsachengrundlage soll eine Zahlung, Kürzung, Rückforderung oder Berücksichtigung erfolgen?
8. Wird eine vorläufige Entscheidung bis zur Klärung der Originalabrechnungen ausgesetzt oder angepasst?
9. Kann Akteneinsicht bzw. eine Kopie der entscheidungserheblichen Berechnungsblätter gewährt werden?
10. Welche Frist gilt für eine ergänzende Stellungnahme?

Die Anfrage sollte konkrete Bescheide, Aktenzeichen und Zeiträume nennen. Allgemeine Vorwürfe gegen Behörden oder Unternehmen sind durch konkrete Dokumente und überprüfbare Fragen zu ersetzen.

---

## 9. Fehlende Nachweise und Importplan

### Priorität 1 – zwingend für die Zahlenprüfung

- Original-Betriebskostenabrechnungen 2014–2024
- Einzelabrechnungen der Wohnung für jedes streitige Jahr
- Ablese- und Geräteprotokolle inklusive Geräte-/Zählernummern
- Mietvertrag bzw. Flächen- und Umlageschlüsselunterlagen
- Jobcenter-Bescheide, Berechnungsbögen und Zahlungsnachweise

### Priorität 2 – für die technische Kausalität

- Otto-Richter-Bericht vom 07.03.2017
- vollständige Mängel- und E-Mail-Chronologie
- Reparaturaufträge, Rechnungen und Arbeitsberichte
- Temperaturmessprotokolle mit Messgerätangabe
- Originalfotos und Originalvideos mit Metadaten
- Wartungs-, Eich-, Kalibrier- und Prüfprotokolle

### Priorität 3 – für Verantwortlichkeit und Verfahrensablauf

- Belegeinsichtsanfragen und Antworten
- Schriftverkehr mit RESIDEA, White Tulip, Minol und Fachfirmen
- Nachweise zu Zusatzstrom, Gas oder Elektroheizgeräten
- sämtliche Korrekturabrechnungen und Versionen
- relevante Jobcenter-Aktenauszüge und Rechtsbehelfsentscheidungen

Beim Hochladen in dieses Zielrepository sollten die Dateien möglichst in folgende Verzeichnisse eingeordnet werden:

```text
Importiert/
  00_originale_unverändert/
  01_abrechnungen/
  02_jobcenter/
  03_schriftverkehr/
  04_fotos/
  05_videos/
  06_technik_gutachten/
  07_kosten_und_berechnungen/
  99_ungeklärt_oder_duplikate/
```

Zusätzlich soll eine `DATEI_REGISTER.csv` mit Pfad, Originalname, Datum, Dateityp, SHA-256, Beschreibung und Beweis-ID geführt werden.

---

## 10. Qualitäts- und Abnahmekriterien der späteren Endfassung

Die Dokumentenmappe ist erst für eine Übergabeprüfung bereit, wenn:

- jeder behauptete Betrag auf eine konkrete Originalseite verweist;
- jede Anlage eine eindeutige Kennung besitzt;
- Originale und Bearbeitungskopien getrennt sind;
- Rechenwege reproduzierbar sind;
- Widersprüche und Unsicherheiten offen markiert sind;
- keine Hypothese als erwiesener Vorsatz, Betrug oder Haftung formuliert wird;
- Gebäude-, Wohnungs- und Jobcenterbeträge getrennt bleiben;
- die Chronologie keine nicht belegten Zwischenereignisse ergänzt;
- das Jobcenter einen klaren, begrenzten Prüfauftrag erhält;
- personenbezogene Daten nur im erforderlichen Umfang veröffentlicht werden;
- vor einer gerichtlichen Einreichung eine fachkundige rechtliche Prüfung erfolgt.

---

## 11. Vorläufige Zusammenfassung

Der bisherige Bestand enthält eine umfangreiche Arbeitsgrundlage mit technischen Beobachtungen, Zahlenvergleichen, Fotos, Videos, Kostenaufstellungen und Entwürfen für das Jobcenter. Die stärksten prüfbaren Anknüpfungspunkte sind:

1. Vergleich der jährlichen Abrechnungs- und Ablesewerte;
2. Abgleich von Einzelabrechnung, Gebäudeabrechnung und Umlageschlüssel;
3. Originalnachweis der behaupteten 2022er Extremwerte;
4. Originalnachweis der 2024er Warmwasser-/Heizkostenaufteilung;
5. Reparatur- und Kommunikationschronologie;
6. Integrität und technische Aussagekraft von Foto-/Videodateien;
7. Jobcenter-Akte mit der tatsächlichen Berechnung und Prüfung.

Bis diese Punkte mit Originalen, Dateiregistern und nachvollziehbaren Berechnungen belegt sind, lautet die sachlich belastbare Formulierung:

> **Es bestehen erhebliche, dokumentationsbedürftige Auffälligkeiten in Technik, Messung und Abrechnung. Die Sammlung beantragt eine nachvollziehbare Prüfung und stellt die vorhandenen Belege geordnet zur Verfügung. Eine abschließende Verantwortungs- oder Rechtsfolgenbewertung bleibt der Prüfung der Originalunterlagen und gegebenenfalls einer fachkundigen Begutachtung vorbehalten.**
