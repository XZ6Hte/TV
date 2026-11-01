---
title: Glossare Versicherung – Quellenrecherche
project: satzart
date: 2026-11-01
tags: [satzart, glossar, terminologie, technische-versicherung, quellen]
status: recherche
---

# Glossare Versicherung – Quellenrecherche

## Ergebnis

- **Ein einziges internationales Glossar, das technische Versicherung (TV) abdeckt, gibt es nicht.**
- Internationale Glossare sind **aufsichtsrechtlich** (IAIS, OECD, EIOPA) oder **datenstandard-orientiert** (ACORD) und enthalten TV-Sparten höchstens am Rand.
- TV-Terminologie liegt verteilt bei **Rückversicherern** (Munich Re), **Fachverbänden** (IMIA, SVV), **Maklern/Erstversicherern** und in **AVB-Texten**.
- Folge für satzart: Begriffe in **Schichten** trennen (siehe [[#Vorschlag Begriffsschichten]]).

## Legende

| Feld | Werte |
|---|---|
| Zugang | `frei` · `Mitglied/Lizenz` · `kostenpflichtig` · `Buch` |
| TV | `ja` = Sparten definiert · `teilw.` = einzelne Begriffe · `nein` · `?` = nicht geprüft |
| Ebene | `core` allgemein · `re` Rückversicherung · `tv` technische Versicherung · `i18n` Übersetzung |

---

## 1. International – Aufsicht / Regulierung

| Quelle | Link | Sprache | Zugang | TV | Ebene | Bemerkung |
|---|---|---|---|---|---|---|
| IAIS Glossary (Web) | https://iaisweb.org/glossary | EN | frei | nein | core | Begriffe aus ICPs/ComFrame; allgemeine Finanzbegriffe bewusst ausgelassen |
| IAIS Glossary (PDF, Stand 01/2026) | https://iais.org/uploads/2026/01/IAIS-Glossary.pdf | EN | frei | nein | core | aktuellste Fassung |
| IAIS Glossary (PDF, 12/2024) | https://iaisweb.org/uploads/2024/12/IAIS-Glossary.pdf | EN | frei | nein | core | Vorversion |
| OECD Glossary of Insurance Policy Terms (1999) | https://oecd.org/en/publications/glossary-of-insurance-policy-terms_9789264173217-en | EN | frei | ? | core | Policy/Regulierung, Schaden, Prämie, Rückstellungen |
| EIOPA – Solvency II Single Rulebook | https://www.eiopa.europa.eu/rulebook/solvency-ii-single-rulebook/article-2414_nl | EU-Sprachen | frei | nein | core | kein eigenständiges Glossar gefunden; Definitionen stehen in den Rechtstexten |
| NAIC Glossary of Insurance Terms | https://content.naic.org/glossary-insurance-terms | EN (US) | frei | nein | core | US-Aufsicht, verbraucherorientiert |

## 2. International – Datenstandard (für Datenmodell relevant)

| Quelle | Link | Sprache | Zugang | TV | Ebene | Bemerkung |
|---|---|---|---|---|---|---|
| ACORD Business Glossary V2.12 | https://www.acord.org/marketplace-pages/product-detail/business-glossary | EN | Mitglied/Lizenz | ? | core | >6.000 Begriffe, Teil der ACORD Reference Architecture |
| ACORD Data Standards (Übersicht) | https://www.acord.org/standards-architecture/acord-data-standards | EN | teils frei | ? | core | P&C, L&A, Reinsurance |
| ACORD GRLC Data Standards | https://acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards | EN | Mitglied | teilw. | re | Reinsurance & Large Commercial; Online Data Dictionary + Codelisten → **nächster Kandidat für TV/Großrisiken** |
| ACORD GRLC Online Data Dictionary (News 07/2024) | https://www.acord.org/news-detail/2024/07/09/acord-grlc-online-data-dictionary-available-via-acord-standards-online | EN | Mitglied | teilw. | re | Zugang über ACORD Standards Online |

## 2a. DE – Datenstandard GDV-Datensatz VU-Vermittler (gdv-online.de)

Für satzart die **zweite Leitquelle neben ACORD**: Satzarten, Spartenschlüssel und Wertelisten sind de facto das deutsche Begriffs- und Codesystem.

| Quelle | Link | Zugang | TV | Bemerkung |
|---|---|---|---|---|
| GDV-Online (Startseite) | https://gdv-online.de | frei | – | Portal: VU-Vermittler, Schaden-Service, eVB u. a. |
| Datenkommunikation VU–Vermittler | https://gdv-online.de/vuvm/ | frei | ja | Einstieg GDV-Datensatz |
| Download: Bestand, Inkasso, Schaden, Kfz-Antrag | https://gdv-online.de/vuvm/best_download.htm | frei | ja | Releases 1998–2023; ab 2005 auch XML-Dokument, ab 2007 XML-Datei |
| Versions- und Releaseverzeichnis | https://gdv-online.de/vuvm/bestand/Versionsverzeichnis.pdf | frei | – | Release-Historie |
| Broschüre „Der GDV-Datensatz VU-Vermittler“ (4. Aufl., 02/2016) | https://gdv-online.de/vuvm/bestand/Broschuere_gdv-datensatz_vu-vermittler.pdf | frei | – | Einsatz, Aufbau, Umsetzung |
| FAQ aktuelles Release | https://gdv-online.de/vuvm/bestand/faq.html | frei | – | – |
| GDV eNorm-Reader + signierte Releases | https://gdv-online.de/vuvm/bestand/download.htm | frei | – | Viewer für die Schnittstellenbeschreibung |
| Beispieldaten | https://gdv-online.de/vuvm/beispiel_download.htm | frei | – | Musterdateien |
| Vermittlerabrechnung | https://gdv-online.de/vuvm/abrech_download.htm | frei | – | Provisionsdaten |
| VU-Nummern | https://gdv-online.de/vuvm/vunummern.htm | frei | – | zusätzlich zum BaFin-Verzeichnis vergebene VU-Nummern |

**Für satzart relevante Satzarten** (lt. Sekundärquelle [softguide/ezGDV](https://www.softguide.de/programm/gdv-viewer-ezgdv), gegen Original prüfen):
- 0100/0102 Kunde, 0200 Vertragsteil allgemein
- 0210/0211, 0220/0221 Spartenteile – für **alle TV-Sparten** belegt
- **0300 Beteiligungen** → Mitversicherung/Führung
- **0350 Klauseln** → Klausel-Katalog (Anbindung TK-Nummern)
- 0400–0450 Inkasso, 0500/0550 Schaden

> [!tip] Bezug zu satzart
> Der Projektname deutet bereits darauf hin: Spartenschlüssel und Wertelisten des GDV-Datensatzes sollten die `key`-Werte im Glossar ergänzen (Mapping `key` ↔ GDV-Code ↔ ACORD-Code).

## 3. Mehrsprachig / Terminologie / Thesauri

| Quelle | Link | Sprache | Zugang | TV | Ebene | Bemerkung |
|---|---|---|---|---|---|---|
| IATE – EU Terminologiedatenbank | https://iate.europa.eu | 24 EU-Sprachen | frei | teilw. | i18n | größte multilinguale Termbank; Download möglich |
| IATE Handbook | https://iate.europa.eu/assets/IATE_Handbook_public.pdf | EN | frei | – | i18n | Zitierweise, Permalinks |
| ZBW STW Thesaurus Wirtschaft – „Unternehmensversicherung“ | https://www.zbw.eu/stw/version/9.0/descriptor/13808-1/about.en.html | DE/EN | frei | **ja** | tv | SKOS, **maschinenlesbar**; enthält Technische Versicherung, Maschinen-, Bauleistungs-, Maschinen-BU-, Garantie-, Computerversicherung |
| EuroVoc (z. B. „reinsurance“) | https://light.onki.fi/eurovoc/en/page/2906 | EU-Sprachen | frei | nein | i18n | EU-Thesaurus, SKOS |
| Mr Honey's Insurance Dictionary DE→EN | https://www.gutenberg.org/ebooks/3214 | DE/EN | frei | teilw. | i18n | Stand 2011 |
| Mr Honey's Insurance Dictionary EN→DE | https://m.gutenberg.org/ebooks/3215 | EN/DE | frei | teilw. | i18n | dito |
| ProZ KudoZ – Insurance DE↔EN | https://slk.proz.com/glossary-translations/german-to-english-translations/insurance | DE/EN | frei | teilw. | i18n | Community, Qualität schwankend |
| Sarouyeh Dictionary of Insurance Terms | https://tm-town.com/terminology-marketplace/sarouyeh-dictionary-of-insurance-terms-english-german-LsSgPQ0TZ3U4nwZZ | EN/DE | kostenpflichtig (1 €) | ? | i18n | 2.436 Konzepte, CAT-Format |
| Müller-Lutz: Insurance Dictionary (DE/EN/FR/FI) | https://catalog.lib.kyushu-u.ac.jp/ja/recordID/1000070861 | 4 Sprachen | Buch | ? | i18n | ISBN 3884872656 |
| Rubin: Fachbegriffe Versicherungswesen (US, EN-DE) | https://econbiz.de/Record/fachbegriffe-versicherungswesen-%C3%BCber-3000-fachbegriffe-des-us-amerikanischen-marktes-englisch-deutsch-rubin-harvey/10000879337 | EN/DE | Buch | ? | i18n | >3.000 Begriffe |

## 4. Rückversicherung

| Quelle | Link | Sprache | Zugang | TV | Ebene | Bemerkung |
|---|---|---|---|---|---|---|
| Pearce: Glossary of Reinsurance Terms (1977) | https://erudit.org/en/revue/assurances/1977/v44/n4/1103916ar.pdf | EN/FR | frei | nein | re | historisch, zweisprachig |
| RAA Glossary of Reinsurance Terms (1973) | https://erudit.org/en/revue/assurances/1973/v41/n1/1103770ar.pdf | EN | frei | nein | re | historisch |
| Hannover Re – Glossar | https://annual-report.hannover-re.com/reports/hannoverre/annual/2021/gb/English/9060/glossar.html | EN | frei | nein | re | Finanz-/RV-Begriffe |
| Swiss Re – Glossary (Financial Report 2013) | https://reports.swissre.com/2013/financial-report/information/glossary.html | EN | frei | nein | re | Bilanz-/Spartenbegriffe |
| NIBA Glossary A–Z (AU) | https://niba.com.au/sites/default/files/content-files/Glossary_of_Insurance_Terms-A-Z-4_21-1.pdf | EN | frei | ? | core/re | Maklerverband Australien |

## 5. Technische Versicherung (Engineering)

| Quelle | Link | Sprache | Zugang | TV | Bemerkung |
|---|---|---|---|---|---|
| IMIA – International Association of Engineering Insurers | http://www.imia.com/ | EN | frei (Papers) | ja | **kein öffentliches Glossar gefunden**; Working Papers als Fachquelle |
| Munich Re – Covers for construction projects | https://munichre.com/en/solutions/for-industry-clients/covers-and-services-for-construction-projects.html | EN | frei | ja | Abkürzungen CECR, MLoP, ALoP/DSU, CAR, EAR, CPI |
| Munich Re US – Facultative Engineering | https://munichre.com/us-non-life/en/solutions/reinsurance/facultative-engineering.html | EN | frei | ja | CAR, ALoP, Operational All Risks, CECR |
| Munich Re Specialty UK – Construction Insurance (FAQ) | https://munichre.com/specialty/global-markets-uk/en/solutions/construction-engineering-insurance/construction-insurance.html | EN | frei | ja | CAR/EAR, DE3 vs. DE4 (Design-Klauseln) |
| Axco – Glossary (Contractors All Risks) | https://www.axcoinfo.com/glossary/contractors-all-risks/ | EN | frei | ja | international vergleichend, Marktinfo |
| Insurer Brain – CAR | https://www.insurerbrain.com/wiki/Definition:Contractors%27_all_risks_(CAR)_insurance | EN | frei | ja | Wiki, Tertiärquelle |
| Insurer Brain – EAR | https://www.insurerbrain.com/wiki/Definition:Erection_all-risk_insurance_(EAR) | EN | frei | ja | verweist auf Munich-Re-Musterwording als De-facto-Standard |
| Insurer Brain – Engineering insurance | https://www.insurerbrain.com/wiki/Definition:Engineering_insurance | EN | frei | ja | Überblick |
| Chaucer – Engineering classes | https://www.chaucergroup.com/classes/engineering | EN | frei | ja | Lloyd's-Sicht: CAR, EAR, DSU, CPE, MB, MLOP, DOS |
| Victor – Builders Risk Glossary | https://www.victorinsurance.com/us/solutions/builders-risk/resources/builders-risk-insurance-explained-glossary-of-terms.html | EN (US) | frei (Anfrage) | ja | US-Pendant zu CAR |
| USAssure/Zurich – Builders Risk Glossary 2024 | https://go.usassure.com/rs/381-ISO-510/images/Builders-Risk-Glossary-2024.pdf | EN (US) | frei | ja | PDF |
| HUB – Builders risk | https://www.hubinternational.com/en-us/insurance-glossary/b/builders-risk/ | EN (US) | frei | ja | Einzelbegriff |
| IRMI – The Builders Risk Book | https://subscribe.irmi.com/the-builders-risk-book | EN (US) | kostenpflichtig | ja | Fachbuch |

## 6. DACH – technische Versicherung

| Quelle | Link | Land | Zugang | TV | Bemerkung |
|---|---|---|---|---|---|
| SVV – AVB Maschinenversicherung 2022 | https://www.svv.ch/sites/default/files/2022-05/MaschinenV_AVB_SVV_Deutsch_2022.pdf | CH | frei | ja | Primärquelle Bedingungstext |
| law.ch – Glossar Bauversicherungen | https://law.ch/lawinfo/bauwesenversicherungen/glossar-2 | CH | frei | ja | Bauwesen, Maschinenkasko, Bauplatzpolice |
| WKO – Versicherungs-ABC M | https://www.wko.at/information-consulting/versicherungsmakler-berater-versicherungsangelegenheiten/versicherungs-abc-m | AT | frei | teilw. | Maklerverband; Buchstaben A–Z einzeln |
| Aon – Technische Versicherungen | https://www.aon.com/germany/risk-services/technische-versicherungen | DE | frei | ja | Spartenliste inkl. Montage-BU, Bauleistungs-BU |
| Württembergische – Technische Versicherungen | https://www.wuerttembergische.de/geschaeftskunden/technische-versicherungen/ | DE | frei | ja | Abgrenzung Transport → Montage → Maschine |
| Gabler Versicherungslexikon (Springer) | https://doi.org/10.1007/978-3-8349-4625-6 | DE | Buch/Lizenz | ? | Standardlexikon; TV-Umfang nicht geprüft |

### GDV-Musterbedingungen Technische Versicherung (Primärquelle DE)

Übersicht: https://www.gdv.de/gdv/technische-versicherungen-6268 · Gesamtübersicht: https://www.gdv.de/gdv/service/musterbedingungen
Status: unverbindliche Bekanntgabe des GDV zur fakultativen Verwendung. Stand der Liste: abgerufen 2026-11-01.

| Nr. | Kürzel | Titel | Version | Link |
|---|---|---|---|---|
| 01 | AMB 2020 | Maschinenversicherung von stationären Maschinen | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/5988/dd20ab16a091ced625527c6caf3750ee/01-allgemeine-bedingungen-fuer-die-maschinenversicherung-von-stationaeren-maschinen-amb-2020--data.pdf) |
| 02 | TK AMB 2020 | Klauseln zu AMB | 01.12.2020 | [PDF](https://www.gdv.de/resource/blob/6048/ddb59158f8ddefca7b4cd746ea0177a8/02-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-maschinenversicherung-von-stationaeren-maschinen-tk-amb-2020--data.pdf) |
| 03 | ABMG 2020 | Maschinen- und Kaskoversicherung fahrbarer/transportabler Geräte | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/6274/f143e6556112c68c96505b161c901960/03-allgemeine-bedingungen-fuer-die-maschinen-und-kaskoversicherung-von-fahrbaren-oder-transportablen-geraeten-abmg-2020--data.pdf) |
| 04 | TK ABMG 2020 | Klauseln zu ABMG | 13.11.2023 | [PDF](https://www.gdv.de/resource/blob/6034/3861e7028bed7855bdee1f703fc5fe57/04-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-maschinen-und-kaskoversicherung-von-fahrbaren-oder-transportablen-geraeten-tk-abmg-2020--data.pdf) |
| 05 | ABE 2020 | Elektronikversicherung | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/6154/48b480785972a19232627eb3cb3860e8/05-allgemeine-bedingungen-fuer-die-elektronikversicherung-abe-2020--data.pdf) |
| 06 | TK ABE 2020 | Klauseln zu ABE | 01.12.2020 | [PDF](https://www.gdv.de/resource/blob/6226/d4e4174e5fb63529793971ea6f9f4825/06-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-elektronikversicherung-tk-abe-2020--data.pdf) |
| 07 | AMoB 2021 | Montageversicherung | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/6236/256f06f94a3a2575f5c9a6e2dedc8182/07-allgemeine-bedingungen-fuer-die-montageversicherung-amob-2021--data.pdf) |
| 08 | TK AMoB 2021 | Klauseln zu AMoB | 01.11.2024 | [PDF](https://www.gdv.de/resource/blob/6152/3ef5f67f57bb494f71bb0511d70e0d31/08-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-montageversicherung-tk-amob-2021--data.pdf) |
| 11 | ABBL 2018 | Versicherung von Bauleistungen | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/6230/5d6e63a6be1320f961490d2d270c2df6/11-allgemeine-bedingungen-fuer-die-versicherung-von-bauleistungen-abbl-2018--data.pdf) |
| 12 | TK ABBL 2018 | Klauseln zu ABBL | 01.11.2024 | [PDF](https://www.gdv.de/resource/blob/6266/298e598d911bc9a72419257394e0b389/12-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-versicherung-von-bauleistungen-tk-abbl-2018--data.pdf) |
| 13 | ABBV 2011 | Baubestandsversicherung | 01.07.2016 | [PDF](https://www.gdv.de/resource/blob/6286/6026b31c8f9519d259cc52ab1abc2422/13-allgemeine-bedingungen-fuer-die-baubestandsversicherung-abbv-2011--data.pdf) |
| 14 | TK ABBV 2011 | Klauseln zu ABBV | 06.01.2011 | [PDF](https://www.gdv.de/resource/blob/6088/a6b6db59cf3c287df431e61b12c54208/14-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-baubestandsversicherung-tk-abbv-2011--data.pdf) |
| 15 | MGar 2024 | Garantieversicherung | 01.07.2025 | [PDF](https://www.gdv.de/resource/blob/6040/68e570474f01082dda9c17f3d5b92069/15-allgemeine-bedingungen-fuer-die-garantieversicherung-mgar-2024--data.pdf) |
| 16 | TK MGar 2024 | Klauseln zu MGar | 01.11.2024 | [PDF](https://www.gdv.de/resource/blob/6264/7eabf7cbb276274180a5d4134d27fc7c/16-klauseln-zu-den-allgemeinen-bedingungen-fuer-die-garantieversicherung-tk-mgar-2024--data.pdf) |

**Betriebsunterbrechung – Technische Versicherung** ([Übersicht](https://www.gdv.de/gdv/betriebsunterbrechung-technische-versicherungen-6092))

| Kürzel | Titel | Version | Link |
|---|---|---|---|
| AMBUB 2011 | Maschinen-Betriebsunterbrechungsversicherung | 06.01.2011 | [PDF](https://www.gdv.de/resource/blob/6084/4908b6c2c01fc60f2f46fad8231d751f/01-allgemeine-bedingungen-fuer-die-maschinen-betriebsunterbrechungsversicherung-ambub-2011--data.pdf) |
| TK AMBUB 2018 | Klauseln zu AMBUB | 24.01.2018 | über Übersichtsseite |

**Übergreifend**
- Gemeinsamer Allgemeiner Teil **AT AH-D&O-Sach-TV (ohne Projektgeschäft)** – gilt für Haftpflicht, D&O, Sach und TV inkl. BU; über https://www.gdv.de/gdv/service/musterbedingungen
- GDV-Glossar (allgemein, TV-Abdeckung ungeprüft): https://www.gdv.de/gdv/service/glossar

> [!note] Beobachtungen
> - Die aktuelle GDV-Liste führt **ABBL 2018** für Bauleistung; ABU/ABN erscheinen dort nicht mehr. Die Nummern 09/10 fehlen in der Liste – ob dort früher ABU/ABN standen, ist nicht verifiziert.
> - Klauselnummern folgen einem Schema je Sparte: 1xxx ABE, 2xxx AMB, 3xxx ABMG, 7xxx AMoB; Präfix `TK A` = Besonderer Teil, `TK B` = Allgemeiner Teil. → Kandidat für einen Klausel-Katalog in satzart.
> - Projektgeschäft (ABBL, AMoB) ist vom gemeinsamen AT ausgenommen.

## 6a. Europa – Länderquellen

Vollständige Länderrecherche (AT, CH, BE, NL, ES, GB, FR, IT, übrige, EU) → [[quellen-europa-tv]]

| Land | Musterbedingungen TV | Datenstandard | Kurzfazit |
|---|---|---|---|
| CH | ✅ SVV (Maschinen, Bauwesen, Montage) | ✗ nicht öffentlich | Bedingungen frei verfügbar |
| AT | ◐ AMB/AEVB als Versicherer-PDFs | ✅ OMDS (VVO) | Datenstandard prüfen |
| BE | ✅ Assuralia (Machinebreuk, TRC 2012) | ◐ Telebib2 | – |
| NL | ✗ | ✅ SIVI AFD | – |
| ES | ✗ | ✅ EIAC | stärkster Standard außerhalb DE |
| GB | ◐ LEG 1/2/3, DE1–DE5, LMA | ◐ LMG CDR | Klausel-Referenz |
| FR | ◐ Décennale/DO (A.243-1) | ◐ EDICourtage | – |
| IT | ◐ Schema Tipo 2.3 (CAR öffentlich) | ✗ (gesetzliche Rami) | – |
| EU | – | ◐ CEN EN 18356 (Entwurf) | Solvency-II-LoB als grobe Achse |

## 7. Allgemein / Makler (core, ohne TV-Tiefe)

| Quelle | Link | Sprache |
|---|---|---|
| Lockton – Glossary | https://global.lockton.com/us/en/glossary-of-insurance-terms | EN |
| Howden – Insurance Glossary | https://howdeninsurance.co.uk/insurance-glossary | EN (UK) |
| California DOI – Glossary | https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/ | EN (US) |
| CII Dictionary (Mitgliederbereich, >3.500 Begriffe) | https://www.insuranceage.co.uk/node/1190366 | EN (UK) |

---

## Vorschlag Begriffsschichten

| Ebene | Inhalt | Leitquelle |
|---|---|---|
| `core` | Vertrag, Police, Prämie, Selbstbehalt, Schaden, VN/VR/VM | IAIS, ACORD, IATE |
| `re` | Mitversicherung, Führung, Quote, XL, Retrozession | ACORD GRLC, Pearce, Hannover Re |
| `tv` | Sparten, Deckungsphasen, Spartenklauseln | Munich Re, IMIA, SVV/GDV-AVB, ZBW STW |
| `i18n` | DE↔EN-Äquivalente | IATE, Mr Honey, STW |

### TV-Sparten – Seed-Liste DE ↔ EN

| DE | EN | Abk. | Phase | Status |
|---|---|---|---|---|
| Bauleistungsversicherung (CH: Bauwesenversicherung) | Contractors' All Risks | CAR | Bau | gesichert |
| Montageversicherung | Erection All Risks | EAR | Montage/Probebetrieb | gesichert |
| Kombinierte Projektversicherung | Comprehensive Project Insurance | CPI | Bau + Montage | gesichert (Munich Re) |
| Maschinenversicherung (stationär) | Machinery Breakdown | MB / MBD | Betrieb | gesichert |
| Maschinenversicherung fahrbar / Maschinenkasko | Contractors' Plant and Machinery / Equipment | CPM / CPE | Betrieb | gesichert |
| Maschinen-Betriebsunterbrechung | Machinery Loss of Profits | MLOP | Betrieb | gesichert |
| Elektronikversicherung | Electronic Equipment Insurance | EEI | Betrieb | gesichert |
| Montage-/Bauleistungs-BU | Advance Loss of Profits / Delay in Start-up | ALOP / DSU | Bau/Montage | gesichert |
| Garantieversicherung | Machinery Guarantee Insurance | – | Betrieb | zu prüfen |
| – (kein etablierter DE-Begriff gefunden) | Civil Engineering Completed Risks | CECR | Betrieb (Tiefbau) | zu prüfen |
| – | Deterioration of Stock | DOS | Betrieb | DE-Begriff zu prüfen |
| – | Decennial Liability | – | nach Abnahme | DE-Begriff zu prüfen |

## Nächste Schritte

- [x] Glossar aus Rechercheergebnissen erstellt → [[glossar]]

### ACORD (Zugang vorhanden – Login durch Nutzer im eingebauten Browser)
- [ ] Desktop-App öffnen, Computer bestätigen, acord.org im eingebauten Browser starten
- [ ] Nutzer loggt sich selbst ein (kein Passwort im Chat)
- [ ] Mitgliedsumfang prüfen: Business Glossary V2.12, GRLC Data Dictionary, Codelisten
- [ ] GRLC Data Dictionary auf TV-Sparten durchsuchen (CAR, EAR, MB, MLOP, ALOP/DSU, CECR, CPM)
- [ ] Mit- und Rückversicherung abgleichen (coinsurance, lead, quota share, XL, retrocession)
- [ ] `key`-Felder in [[glossar]] gegen ACORD-Bezeichner abgleichen
- [ ] Lizenzbedingungen prüfen: Darf ACORD-Terminologie in satzart übernommen werden?
- [ ] Nutzer ändert Passwort nach Abschluss (falls doch geteilt)

### Übrige
- [x] GDV-Musterbedingungen TV inkl. Klauseln erfasst (Quelle: gdv.de)
- [ ] Begriffsdefinitionen (⇒-markierte Begriffe) aus AMB, ABMG, ABE, AMoB, ABBL, MGar extrahieren → [[glossar]]
- [ ] Klauselnummernschema (TK A / TK B, Spartenblöcke) als Datenmodell für Klausel-Katalog prüfen
- [ ] Gemeinsamen Allgemeinen Teil AT AH-D&O-Sach-TV auswerten (Definitionen für `core`)
- [ ] GDV-Glossar auf TV-Begriffe prüfen
- [ ] Klären: Status ABU/ABN neben ABBL 2018 im Markt

### GDV-Datensatz (gdv-online.de)
- [ ] Aktuelles Release + XML-Beschreibung laden (Download-Bereich)
- [ ] Spartenschlüssel der TV-Sparten extrahieren → Spalte `gdv_code` in [[glossar]]
- [ ] Satzart 0300 (Beteiligungen) gegen Mitversicherungsmodell in satzart abgleichen
- [ ] Satzart 0350 (Klauseln) gegen GDV-TK-Nummernschema abgleichen
- [ ] Wertelisten/Anlagen als Lookup-Quellen bewerten (Lizenz: frei verfügbar)
- [ ] Mapping-Tabelle `key` ↔ GDV-Code ↔ ACORD-Code anlegen
### Europa
- [x] Länderrecherche AT, CH, GB, FR, IT, übriges Europa, EU → [[quellen-europa-tv]]
- [ ] OMDS (AT) und EIAC (ES) auf TV-Spartencodes prüfen; Ergebnis als Spalten `omds_code`, `eiac_code` im Mapping
- [ ] Landesbegriffe aus [[quellen-europa-tv#Landesbegriffe TV (Ergänzung zu glossar)]] als `i18n`-Felder ins Glossar übernehmen
- [ ] `design_clause` mit LEG 1/2/3 und DE1–DE5 konkretisieren
- [ ] Offene Punkte in [[quellen-europa-tv#Offene Punkte]] abarbeiten

### Übrige (Fortsetzung)
- [ ] ZBW STW (SKOS) als maschinenlesbare Basis für `tv`-Hierarchie evaluieren
- [ ] IATE-Export für `i18n` testen
