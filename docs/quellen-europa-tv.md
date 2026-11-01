---
title: Quellen Europa – technische Versicherung
project: satzart
date: 2026-11-01
tags: [satzart, quellen, europa, technische-versicherung, datenstandard, musterbedingungen]
status: recherche
bezug: "[[glossare-versicherung]] · [[glossar]]"
---

# Quellen Europa – technische Versicherung

> [!info] Methode
> Recherche vom 2026-11-01. Gesucht wurde pro Land das Äquivalent zu (A) GDV-Musterbedingungen TV inkl. Klauseln, (B) GDV-Datensatz VU-Vermittler, (C) Glossaren.
> `geprüft` = Seite/Dokument abgerufen · `Treffer` = nur in Suchergebnissen gesehen · `ungeprüft` = Aussage nicht belegt.
> Stichproben-Verifikation: SVV Bauwesen, Assuralia TRC 2012, CEN/TC 445 – bestätigt.

## Übersichtsmatrix

| Land | A Musterbedingungen TV (Verband/Staat) | B Datenstandard VU↔VM | C Glossar mit TV | Bewertung für satzart |
|---|---|---|---|---|
| **DE** | ✅ GDV (AMB, ABMG, ABE, AMoB, ABBL, ABBV, MGar, AMBUB + TK) | ✅ GDV-Datensatz (gdv-online.de) | ◐ GDV-Glossar (ungeprüft) | Referenz |
| **CH** | ✅ SVV: Maschinen, Bauwesen, Montage (AVB 2022, ZB 2019) | ✗ nicht öffentlich belegt (IG B2B, EcoHub) | ✗ | Bedingungen gut, Daten offen |
| **AT** | ◐ AMB/AEVB nur als Versicherer-PDFs, VVO-Status unbelegt | ✅ OMDS (VVO, XML, kostenlos) – TV-Codierung ungeklärt | ◐ WKO Versicherungs-ABC | Datenstandard prüfen |
| **BE** | ✅ Assuralia, nicht bindend: Machinebreuk, TRC (2012) | ◐ Telebib2 (Brocom) – nicht belegt | ✗ | Bedingungen gut |
| **NL** | ✗ nur Versicherer-Wordings (CAR, Machinebreuk) | ✅ SIVI AFD 2.0 – TV-Sparten ungeklärt | ✗ | Datenstandard prüfen |
| **ES** | ✗ nur Versicherer-Wordings | ✅ EIAC (TIREA/CIMA, XML, Codetabellen) | ✗ | stärkster Datenstandard außerhalb DE |
| **GB** | ◐ Einzelklauseln: LEG 1/2/3, DE1–DE5, LMA-Klauseln | ◐ LMG Core Data Record v3.2 (ACORD-basiert, London Market) | ◐ FCA Glossary (nur Sparten) | Klauseln als Referenz für `design_clause` |
| **FR** | ◐ nur obligatorische Bauversicherung (Décennale, DO, A.243-1) | ◐ EDICourtage (Nachrichtentypen, keine TV-Codes belegt) | ◐ INC-Lexikon Bau | Décennale/DO für `decennial_liability` |
| **IT** | ◐ staatlich: Schema Tipo 2.3 (CAR öffentliche Aufträge) | ✗ kein ANIA-Standard belegt | ✗ IVASS ohne TV | gesetzliche Rami als Codeliste |
| **PT, DK, SE, NO, FI, PL, CZ, LU, IE, Rest** | ✗ nur Versicherer-Wordings bzw. nichts | ✗ | ✗ | – |
| **EU** | – | ◐ CEN/TC 445 EN 18356-1 (Entwurf), EN 17419 | ✗ EIOPA nur Abkürzungen | Solvency-II-LoB als gröbste Ebene |

Legende: ✅ vorhanden und belegt · ◐ teilweise/ungeklärt · ✗ nicht gefunden

---

## Österreich (AT)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | AMB 2013 Maschinenbruch (Oberösterreichische) | https://versich.at/fileadmin/import/pdf/amb2013.pdf | 2013 | frei | MB | geprüft – Verbandsherkunft nicht genannt |
| A | AEVB 2024 Elektronik (Oberösterreichische) | https://www.versich.at/fileadmin/import/pdf/aevb2024.pdf | 02.12.2024 | frei | EEI | geprüft |
| A | AMB-BU 2013 | https://www.keinesorgen.at/fileadmin/import/pdf/ambub2013.pdf | 2013 | frei | MLOP | Treffer |
| A | AMMB 1990/95 Maschinen-Montage | https://www.keinesorgen.at/fileadmin/import/pdf/ammb90-95.pdf | 1995 | frei | EAR | Treffer |
| A | Zurich AT – Maschinenbruch AMB | https://edge.sitecorecloud.io/zurichinsurf8c0-zwpshared-prod-d824/media/project/zurich-headless/zurich-austria/docs/betriebsversicherung/bedingungen/maschinenbruch-amb.pdf | ? | frei | MB | Treffer |
| A | ABS 2004 (VAV) – Allg. Sachbedingungen | https://www.vav.at/dam/jcr:8b4a1577-ba09-4f20-a9e4-91cb39e69177/ABS%202004_lang.pdf | 2004 | frei | AT-Teil | Treffer |
| B | OMDS 2.x / 3.0 (VVO) – Beschreibung in WKO-Folien | https://www.wko.at/wien/information-consulting/versicherungsmakler-berater-versicherungsangelegenheiten/folien-bildungstag-2024-selb-digitalisierung-im-maklerbuero.pdf | OMDS 2.16 (2024); 3.0 seit 2021 | kostenlos lt. Folien | ? | geprüft (Sekundär) |
| B | omds.at / vvo.at | https://www.omds.at · https://www.vvo.at | – | – | – | im Recherchewerkzeug gesperrt – ungeprüft |
| C | WKO Versicherungs-ABC | https://www.wko.at/information-consulting/versicherungsmakler-berater-versicherungsangelegenheiten/versicherungs-abc-m | 03.02.2025 | frei | ja (M: Maschinen, Maschinen-BU, Montage) | geprüft |

Kernaussagen: OMDS ist das klare Gegenstück zum GDV-Datensatz (XML; Person, Vertrag, Inkasso, Schaden, Provision, Klauseln/Bedingungen). BiPRO wurde in AT nicht übernommen. Verbandsmuster für Bauwesen, Montage und Garantie wurden nicht gefunden.

## Schweiz (CH)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | SVV Maschinenversicherung (Seite) | https://svv.ch/de/musterbedingungen/maschinenversicherung | 2019 | frei | MB | geprüft |
| A | AVB Maschinen | https://svv.ch/sites/default/files/media/documents/2022-05/MaschinenV_AVB_SVV_Deutsch_2022.pdf | 2022 | frei | MB | geprüft |
| A | ZB Maschinen | https://svv.ch/sites/default/files/media/documents/2019-04/SVV_ZB_MaV_2019_DE.pdf | 2019 | frei | MB | geprüft |
| A | SVV Bauwesenversicherung (Seite) | https://svv.ch/de/musterbedingungen/bauwesenversicherung | 2019 | frei | CAR | geprüft (Stichprobe) |
| A | AVB Bauwesen | https://svv.ch/sites/default/files/media/documents/2022-05/Bauwesen_AVB_SVV_Deutsch_2022.pdf | 2022 | frei | CAR | geprüft |
| A | ZB Bauwesen | https://svv.ch/sites/default/files/media/documents/2019-10/Bauwesen%20ZB%20SVV%20Deutsch%202019.pdf | 2019 | frei | CAR | geprüft |
| A | SVV Montageversicherung (Seite) | https://svv.ch/de/musterbedingungen/montageversicherung | 2019 | frei | EAR | geprüft |
| A | AVB Montage | https://svv.ch/sites/default/files/media/documents/2022-05/Montage_AVB_SVV_Deutsch_2022.pdf | 2022 | frei | EAR | geprüft |
| A | ZB Montage | https://svv.ch/sites/default/files/media/documents/2019-04/SVV_ZB_Montageversicherung_2019_DE.pdf | 2019 | frei | EAR | geprüft |
| A | Grafik Probebetrieb | https://svv.ch/sites/default/files/media/documents/2017-11/grafik_probebetrieb_deutsch_2017.pdf | 2017 | frei | EAR | geprüft |
| A | SVV Bauwesen-Fachdokumente (Risikofragebögen Montage, Bau, PV) | https://svv.ch/de/bauwesen | 2024–2026 | frei | CAR/EAR | geprüft – **relevant für Antragsfragen** |
| A | Zurich CH – AVB Maschinen/Elektronik | https://www.zurich.ch/-/media/zurich-site/content/firmenkunden/sach-haftpflichtversicherungen/dokumente/avb-maschinen-elektronik-versicherung/avb-maschinen-elektronik-versicherung.pdf?la=de | ? | frei | MB/EEI | Treffer – Versicherer, schließt Elektronik-Lücke |
| B | IG B2B for Insurers + Brokers / EcoHub | nur Sekundärquellen | – | unklar | ? | ungeprüft |
| C | BPV-Glossar (FINMA-Archiv) | https://www.finma.ch/finmaarchiv/bpv/d/glossar/index.html?lang=de | 2006 | frei | nein | geprüft – veraltet |

Kernaussagen: SVV ist ein echtes Äquivalent für Maschinen, Bauwesen, Montage. Für Elektronik, Maschinen-BU, Garantie, Maschinenkasko wurde kein SVV-Muster gefunden. Ein offener Datenstandard ist nicht belegt.

## Belgien (BE)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | Assuralia – Machinebreuk (NL), nicht bindend | https://files.assuralia.be/werking-verzekering_fonctionnement-assurance/Niet-bindende-standaardverzekeringsvoorwaarden_Conditions-standards-dassurance-non-contraignantes/MachineBreuk_NL_jan2012.pdf | 01/2012 | frei | MB | geprüft – Art. 19 Definitionen |
| A | Assuralia – Tous Risques Chantier (FR), nicht bindend | https://files.assuralia.be/werking-verzekering_fonctionnement-assurance/Niet-bindende-standaardverzekeringsvoorwaarden_Conditions-standards-dassurance-non-contraignantes/TRC_FR_jan2012.pdf | 01/2012 | frei | CAR + Haftpflicht | geprüft (Stichprobe) – Art. 18 Definitionen |
| A | Assuralia SR07 (NL) | https://www.assuralia.be/images/docs/werking-verzekering_fonctionnement-assurance/Niet-bindende-standaardverzekeringsvoorwaarden_Conditions-standards-dassurance-non-contraignantes/SR07_NL_nov2011.pdf | 11/2011 | frei | ? | Treffer |
| B | Telebib2 (Brocom) | – | – | – | ? | nicht belegt |

## Niederlande (NL)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| B | SIVI All Finance Standard (AFD 2.0) – Handbuch | https://www.manula.com/manuals/sivi/sivi-all-finance-standard/1/en/topic/readers-guide | AFD 2.0 | Handbuch frei | ? | geprüft |
| B | SIVI AFD-Definition Standard | https://www.manula.com/manuals/sivi/afd-definition-standard/1/en/topic/introduction-afd-definition-standard | Release 001.000.007 (01.01.2025) | Handbuch frei | ? | geprüft – Produktdefinitionen inkl. Berechnungsregeln |
| B | SIVI Branchecodelijst (über ANVA) | https://www.anva.nl/en/news-insights-customers/do-you-already-know-the-new-industry-code-list-from-sivi | 01.05.2024 | ? | ? | geprüft (Sekundär) |
| A | Techniek Nederland – Montage-/Transportverzekering (Kollektiv) | https://verzekeringen.technieknederland.nl/media/23qdhdo2/clausuleblad-montagetransport-vi.pdf | ? | frei | EAR | Treffer |
| A | Verbond van Verzekeraars – Modellbedingungen TV | – | – | – | – | nicht gefunden |

## Spanien (ES)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| B | EIAC – Documentos Estándar V07.1 | https://homologacioncima.tirea.es/wp-content/uploads/2026/03/209_IAC_ESP_DOC_DOCS-ESTANDAR-EIAC-V07-1_V04.pdf | V04, 30.05.2025, 93 S. | frei nutzbar, Rechte TIREA | teilw. (Construcción, Industriales, Pérdidas Diversas) | geprüft – Codetabellen Kap. 10.3 offen |
| B | CIMA – Projektpräsentation | https://www.cimaseg.es/wp-content/uploads/2025/03/20250227_CIMA_Presentacion-proyectos-en-marcha_V02-2.pdf | 02/2025 | frei | ? | Treffer |
| A | UNESPA/ICEA – Modellbedingungen TV | – | – | – | – | nicht gefunden |

## Großbritannien (GB)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | LMA Engineering Business Panel | https://lmalloyds.com/committee/engineering-business-panel | LMA5197A (2014), LMA5397 (2020) | Seite frei | CAR/EAR | geprüft |
| A | Lloyd's Wordings Repository | https://www.lloydswordings.com/ | ? | vermutl. Registrierung | ? | gesperrt – ungeprüft |
| A | London Engineering Group (IUA) | https://www.iua.co.uk/IUA_Member/IUANew/UnderwritingItems/Committees/London_Engineering_Group.aspx | ? | vermutl. Mitglied | LEG 1/2/3 | gesperrt – ungeprüft |
| A | LEG-Klauseln – Erläuterung (Gatehouse Chambers) | https://gatehouselaw.co.uk/wp-content/uploads/2021/12/LEG-clauses-the-latest-thinking-website.pdf | 2021 | frei | LEG 1, 2/96, 3/06 | geprüft (Sekundär) |
| A | DE1–DE5 Design-Klauseln (Carter Newell) | https://www.carternewell.com/?p=2956 | Fassung 1995 | frei | DE1–DE5 | geprüft (Sekundär) |
| A | LMA-Bulletin Serial Loss / Serial Defect | https://www.lmalloyds.com/LMA_Bulletins/LMA22-022-JHF.aspx | 15.06.2022 | frei | Erneuerbare | geprüft |
| A | Beale & Co – LEG-Revision | https://beale-law.com/wp-content/uploads/2026/09/Beale-Co-On-Their-Last-Legs-LEG-to-Publish-Revised-LEG-Exclusion-Clauses.pdf | 09/2026 | frei | LEG | Treffer – **mögliche Neufassung der LEG-Klauseln** |
| B | LMG Core Data Record (CDR) | https://www.lloyds.com/conducting-business/requirements-and-standards/core-data-record/about | v3.2, 29.03.2023 | Registrierung | ? | geprüft |
| B | CDR v3.3 Treaty (ACORD) | https://acord.org/news-detail/2026/05/18/data-council-launches-core-data-record-v3.3-supporting-treaty-reinsurance | 18.05.2026 | Pressemeldung | RV | geprüft |
| B | Polaris (Artikel) | https://www.insurancetimes.co.uk/insight/how-standards-can-help-brokers-and-underwriters/1435394.article | ? | – | nein (Privatkunden) | geprüft |
| C | FCA Handbook Glossary | https://handbook.fca.org.uk/glossary/G257 | laufend | frei | nur Sparten | Treffer |

## Frankreich (FR)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | Code des assurances – Clauses-types A.243-1 (Annexe III, EN-Übersetzung) | https://french-business-law.com/french-legislation-art/article-annexe-iii-art-a243-1-of-the-french-insurance-code | seit 28.11.2009 | frei | Décennale | geprüft |
| A | Clauses-types RCD individuelle / collective / DO (Spiegel Neukaledonien) | https://rcnc.gouv.nc/sites/default/files/documents/R243-1_Annexe%20II_clauses%20types%20DO.pdf | ? | frei | DO, Décennale | Treffer |
| A | Albingia – TRC / Montage-Essais (Versicherer) | https://www.albingia.fr/wp-content/uploads/2023/02/Tous-risques-chantiers-Montage-essais.pdf | 2023 | frei | CAR/EAR | Treffer – Terminologiebeleg |
| B | EDICourtage – EDImessage (Nachrichtentypen) | https://www.edicourtage.fr/edimessage-synthese-par-editeur | 03/2023 | Mitgliedschaft | nein (belegt: Auto, MRH, Multi-Pro) | geprüft |
| C | FFA-Glossar | https://www.ffa-assurance.fr/glossaire/letter_a | ? | frei | nur DO | geprüft |
| C | INC – Lexique assurance construction | https://www.inc-conso.fr/sites/default/files/conseil_923_1541-lexique_assurance_construction%28j118%29.pdf | 12/2009 | frei | DO, TRC, Décennale | geprüft |

## Italien (IT)

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| A | Schema Tipo 2.3 (D.M. 123/2004) – Exemplar AIG | https://orgn-aigit.dmp.aig.com/content/dam/aig/emea/italy/documents/fascicoli-informativi-travel/aig-schema-tipo-2.3-set-informativo.pdf | ? | frei | CAR + RCT öffentliche Aufträge | geprüft |
| A | Chubb – Rischi tecnologici (CAR, EAR, Guasti Macchine) | https://www.chubb.com/it-it/aziende/prodotti/polizze-rischi-tecnologici.html | ? | frei | ja | geprüft – Terminologiebeleg |
| A | Groupama – CAR Opere Civili | https://cdn.groupama.it/app/uploads/2026/02/Set-Informativo-CAR-Opere-Civili-Ed.-02-2026.pdf | Ed. 02/2026 | frei | CAR | Treffer |
| B | Codice delle assicurazioni private, Art. 2 (Rami Danni 1–18) | https://www.filodiritto.com/codici/decreto-legislativo-7-settembre-2005-n-209-codice-delle-assicurazioni-private/capo-i-definizioni-e-classificazioni-generali/art-2-classificazione-ramo | D.Lgs. 209/2005 | frei | indirekt (Ramo 9, BU Ramo 16) | geprüft |
| C | IVASS Glossario | https://www.ivass.it/consumatori/imparaconivass/glossario/glossario_educazione_assicurativa.pdf | ? | frei | nein | geprüft |

## EU / europaweit

| Kat. | Quelle | URL | Stand | Zugang | TV | Status |
|---|---|---|---|---|---|---|
| B | CEN/TC 445 – EN 18356-1 / CEN/TS 18356-2 (FIDA, Datenmodell + OpenAPI) | https://www.cencenelec.eu/media/CEN-CENELEC/Events/Webinars/2026/2026-04-21_webinar_centc445_fida_insurance_standardization_reimer.pdf | Enquiry 06–08/2026 | frei (Folien) | nein – Gewerbliche Sach als nächstes Modell | geprüft (Stichprobe) |
| B | EN 17419-1:2020 – Transfer elektronischer Dokumente | https://www.boutique.afnor.org/en-gb/standard/nf-en-174191/digital-information-interchange-in-the-insurance-industry-transfer-of-elect/fa188969/260658 | 11/2020 | kostenpflichtig | nein | geprüft |
| D | Solvency II, Del. VO (EU) 2015/35 Anhang I – 12 Nicht-Leben-LoB | https://legislation.gov.uk/eur/2015/35/annex/I/2020-01-01 | 2020 | frei | indirekt (LoB 7/8/12) | geprüft – EUR-Lex-URL ergänzen |
| D | EIOPA Q&A 1769 – BU-Zuordnung zu LoB | https://www.eiopa.europa.eu/qa-regulation/questions-and-answers-database/1769_en | 2019 | frei | MLOP/ALOP | geprüft |
| C | EIOPA Glossar (Abkürzungen) | https://www.eiopa.europa.eu/glossary_en | online | frei | nein | geprüft |
| C | AMICE Glossar | https://amice-eu.org/resources/glossary/ | ? | frei | ? | Treffer |

---

## Landesbegriffe TV (Ergänzung zu [[glossar]])

| key | DE | CH | GB | FR | IT | BE (NL/FR) | NL | ES |
|---|---|---|---|---|---|---|---|---|
| `contractors_all_risks` | Bauleistungsversicherung | Bauwesenversicherung | Contractors'/Construction All Risks | Tous Risques Chantier (TRC) | Polizza CAR | Alle bouwplaatsrisico's / TRC | CAR-verzekering, Constructieverzekering | Todo Riesgo Construcción |
| `erection_all_risks` | Montageversicherung | Montageversicherung | Erection All Risks | Tous Risques Montage-Essais (TRME) | Polizza EAR | – | Montageverzekering | Todo Riesgo Montaje |
| `machinery_breakdown` | Maschinenversicherung | Maschinenversicherung | Machinery Breakdown | Bris de machines | Guasti Macchine | Machinebreuk / Bris de machines | Machinebreukverzekering | Avería/Rotura de Maquinaria |
| `electronic_equipment` | Elektronikversicherung | EDV-Anlagen-Versicherung | Electronic Equipment | (Teil von Bris de machines) | Elettronica | – | – | – |
| `contractors_plant_machinery` | Maschinen fahrbar / Maschinenkasko | Maschinenkasko | Contractors' Plant | Engins de chantier | Macchinari di cantiere | – | – | – |
| Oberbegriff | Technische Versicherung | Technische Versicherungen | Engineering insurance | Risques techniques | Rischi tecnologici | – | – | Ingeniería |

Status: Zuordnungen aus Versicherer- und Verbandsdokumenten; Felder „–“ nicht belegt. ES-Begriffe aus Versicherer-Wordings (z. T. LatAm) – vor Übernahme prüfen.

---

## Schlussfolgerungen für satzart

1. **Musterbedingungen (DACH-Fokus):** DE (GDV) und CH (SVV) liefern frei verfügbare Primärtexte; AT nur über Versicherer-PDFs. BE ist das einzige weitere EU-Land mit Verbandsmustern (MB, CAR).
2. **Datenstandards:** Neben GDV kommen **OMDS (AT)** und **EIAC (ES)** als strukturell vergleichbare Standards infrage; SIVI (NL) als Referenz für Produktdefinitionen. Für CH ist kein offener Standard belegt.
3. **Klauseln:** GB-Klauseln (LEG, DE1–DE5) sind international die Referenz für Konstruktions-/Mangelausschlüsse → `design_clause` im Glossar konkretisieren. LEG-Neufassung 2026 beobachten.
4. **EU-Ebene:** Solvency-II-LoB als gröbste Spartenachse; CEN EN 18356 als künftiges Mapping-Ziel für gewerbliche Sach – kein TV-Modell.
5. **Glossare:** Kein Land hat ein Verbandsglossar mit TV-Tiefe. Die Definitionsartikel der AVB (z. B. Assuralia Art. 18/19, GDV ⇒-Begriffe) sind die belastbarste Quelle.

## Offene Punkte

- [ ] OMDS-Spezifikation und Wertelisten auf vvo.at/omds.at lesen (TV-Sparten codiert?)
- [ ] VVO anfragen: existieren VVO-Musterbedingungen TV (AMB, AEVB, Bauwesen, Montage)?
- [ ] CH: IG B2B / EcoHub nach öffentlicher Spezifikation fragen
- [ ] EIAC-PDF Kap. 10.3 (Ramo-Codes) auswerten
- [ ] SIVI AFD: Produktdefinitionen TV und Lizenz prüfen
- [ ] Telebib2 bei Brocom anfragen
- [ ] Weitere Assuralia-Standards (Elektronik, Montage, BU) suchen
- [ ] Lloyd's Wordings / IUA-LEG-Volltexte über Zugang prüfen; LEG-Revision 2026 verfolgen
- [ ] EUR-Lex-URL für Del. VO 2015/35 Anhang I ergänzen
