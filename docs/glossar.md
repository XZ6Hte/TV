---
title: Glossar satzart
version: 0.1
date: 2026-11-01
project: satzart
tags: [satzart, glossar, terminologie]
status: entwurf
quellen: "[[glossare-versicherung]]"
---

# Glossar satzart

> [!info] Geltungsbereich
> Entwurf aus der Quellenrecherche vom 2026-11-01 ([[glossare-versicherung]]). Definitionen sind eigene Kurzfassungen und kein Bedingungstext. ACORD-Abgleich steht aus.

## Schema

| Feld | Bedeutung |
|---|---|
| `key` | technischer Schlüssel (en-US, snake_case) – Kandidat für Enum/Lookup |
| `de` / `en` | Vorzugsbenennung |
| `abbr` | gebräuchliche Abkürzung |
| `layer` | `core` · `re` · `tv` |
| `status` | `belegt` = Quelle verlinkt · `fachlich` = gängige Fachpraxis, Quelle offen · `offen` = Definition/Äquivalent ungeklärt |

---

## core – allgemeine Begriffe

| key | de | en | abbr | Definition | status | Quelle |
|---|---|---|---|---|---|---|
| `policyholder` | Versicherungsnehmer | policyholder | VN | Vertragspartner des Versicherers, der die Deckung abschließt und die Prämie schuldet | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `insurer` | Versicherer | insurer, carrier | VR | Unternehmen, das das Risiko gegen Prämie übernimmt | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `intermediary` | Versicherungsvermittler | intermediary, broker, agent | VM | Dritter, der Verträge vermittelt oder verhandelt; Makler handelt für den Kunden, Agent für den Versicherer | belegt | [Howden](https://howdeninsurance.co.uk/insurance-glossary) |
| `policy` | Police, Versicherungsschein | policy | – | schriftlicher Versicherungsvertrag | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `premium` | Prämie, Beitrag | premium | – | Entgelt des VN für den Versicherungsschutz | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `endorsement` | Nachtrag | endorsement | – | Änderung eines bestehenden Vertrags, die Deckung oder Limits erweitert oder einschränkt | belegt | [USAssure](https://go.usassure.com/rs/381-ISO-510/images/Builders-Risk-Glossary-2024.pdf) |
| `deductible` | Selbstbehalt, Selbstbeteiligung | deductible, excess | SB | Teil des Schadens, den der VN selbst trägt; in der RV entspricht dem die Retention | belegt | [ProZ](https://www.proz.com/kudoz/german-to-english/insurance/253075-selbstbehalt.html) |
| `peril` | Gefahr | peril | – | Ursache eines möglichen Schadens, z. B. Feuer, Diebstahl | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `policy_limit` | Versicherungssumme / Höchstentschädigung | policy limit | VS | maximale Leistung gesamt oder je Deckung | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `claim` | Schaden(meldung) | claim | – | Anzeige an den Versicherer, dass ein möglicherweise gedeckter Schaden vorliegt | belegt | [CA DOI](https://www.insurance.ca.gov/01-consumers/105-type/95-guides/20-glossary/) |
| `exclusion` | Ausschluss | exclusion | – | ausdrücklich nicht versicherte Gefahren, Sachen oder Situationen | belegt | [AAA](https://magazine.northeast.aaa.com/?p=216682) |
| `underinsurance` | Unterversicherung | underinsurance | – | VS liegt unter dem Versicherungswert; Entschädigung wird anteilig gekürzt | belegt | [SGIC](https://sgic.com.np/products/engineering) |
| `replacement_value` | Neuwert | replacement cost | – | Kosten der Wiederbeschaffung neuer Sachen gleicher Art und Güte | belegt | [Württembergische](https://www.wuerttembergische.de/geschaeftskunden/technische-versicherungen/) |
| `general_conditions` | Allgemeine Versicherungsbedingungen | general conditions of insurance | AVB | standardisierte Vertragsbedingungen einer Sparte | belegt | [Mr Honey](https://www.gutenberg.org/ebooks/3214) |

## re – Mit- und Rückversicherung

| key | de | en | abbr | Definition | status | Quelle |
|---|---|---|---|---|---|---|
| `reinsurance` | Rückversicherung | reinsurance | RV | Versicherung des Versicherers; senkt dessen Risiko | belegt | [Swiss Re](https://reports.swissre.com/2013/financial-report/information/glossary.html) |
| `cedant` | Zedent, Erstversicherer | ceding company, reinsured | – | Versicherer, der Risiko ganz oder teilweise an einen Rückversicherer abgibt | belegt | [RAA/Pearce](https://erudit.org/en/revue/assurances/1973/v41/n1/1103770ar.pdf) |
| `cession` | Zession, Abgabe | cession, cede | – | Übertragung von (Rück-)Versicherungsgeschäft an einen Rückversicherer | belegt | [RAA/Pearce](https://erudit.org/en/revue/assurances/1973/v41/n1/1103770ar.pdf) |
| `retrocession` | Retrozession | retrocession | – | Rückversicherung des Rückversicherers | fachlich | – |
| `treaty` | obligatorische RV, Vertrag | treaty reinsurance | – | automatische RV ganzer Portefeuilles | belegt | [Swiss Re/Uni Málaga](https://riuma.uma.es/bitstreams/cf293348-455a-45d6-8945-0419d0be4922/download) |
| `facultative` | fakultative RV | facultative reinsurance | fak. | RV einzelner Risiken, Einzelfallentscheidung | belegt | [Munich Re US](https://munichre.com/us-non-life/en/solutions/reinsurance/facultative-engineering.html) |
| `quota_share` | Quotenrückversicherung | quota share | QS | Aufteilung des Geschäfts in festem Verhältnis | belegt | [Swiss Re](https://reports.swissre.com/2013/financial-report/information/glossary.html) |
| `excess_of_loss` | Schadenexzedent | excess of loss | XL | nicht-proportional; RV übernimmt eine definierte Schadentranche | belegt | [Swiss Re/Uni Málaga](https://riuma.uma.es/bitstreams/cf293348-455a-45d6-8945-0419d0be4922/download) |
| `pooling_arrangement` | Pool, Mitversicherungsgemeinschaft | pooling arrangement | – | mehrere (Rück-)Versicherer teilen definierte Risiken in festen Anteilen | belegt | [EIOPA Rulebook](https://www.eiopa.europa.eu/rulebook/solvency-ii-single-rulebook/article-2414_nl) |
| `coinsurance` | Mitversicherung | co-insurance | – | mehrere Versicherer zeichnen ein Risiko gemeinsam mit Anteilen | fachlich | – |
| `lead_insurer` | führender Versicherer | lead insurer | – | Versicherer, der in der Mitversicherung Vertrag und Schaden für alle Beteiligten verwaltet | fachlich | – |
| `placement` | Platzierung | placement | – | Unterbringung eines (Rück-)Versicherungsrisikos am Markt | belegt | [ProZ](https://www.proz.com/kudoz/english-to-german/insurance/4346224-placement.html) |

> [!note] Begriffsfalle
> Im US-Sprachgebrauch bedeutet `coinsurance` auch die Unterversicherungsklausel (Proportionalitätsregel). Im Datenmodell muss das getrennt bleiben von `coinsurance` als Mitversicherung.

## tv – technische Versicherung

### Sparten

| key | de | en | abbr | Phase | Definition | status | Quelle |
|---|---|---|---|---|---|---|---|
| `contractors_all_risks` | Bauleistungsversicherung (CH: Bauwesenversicherung) | Contractors' All Risks | CAR | Bau | Allgefahrendeckung für Bauleistung, Material und Baustelleneinrichtung im Hoch- und Tiefbau, oft mit Haftpflichtteil | belegt | [Insurer Brain](https://www.insurerbrain.com/wiki/Definition:Contractors%27_all_risks_(CAR)_insurance) |
| `erection_all_risks` | Montageversicherung | Erection All Risks | EAR | Montage, Probebetrieb | Allgefahrendeckung für Montage von Maschinen, Anlagen und Stahlbau inkl. Testphase | belegt | [Insurer Brain](https://www.insurerbrain.com/wiki/Definition:Erection_all-risk_insurance_(EAR)) |
| `comprehensive_project` | kombinierte Projektversicherung | Comprehensive Project Insurance | CPI | Bau + Montage | CAR und EAR in einer Police | belegt | [Munich Re](https://munichre.com/en/solutions/for-industry-clients/covers-and-services-for-construction-projects.html) |
| `machinery_breakdown` | Maschinenversicherung (stationär) | Machinery Breakdown | MB, MBD | Betrieb | plötzliche, unvorhergesehene Schäden an Maschinen im Betrieb, z. B. Bedienfehler, Kurzschluss | belegt | [NICL](https://nicl.com.pk/?p=952) |
| `contractors_plant_machinery` | Maschinenversicherung fahrbar / Maschinenkasko | Contractors' Plant & Machinery / Equipment | CPM, CPE | Betrieb | Baumaschinen und Krane, auch gegen Unfallschäden durch äußere Einwirkung | belegt | [law.ch](https://law.ch/lawinfo/bauwesenversicherungen/glossar-2) |
| `machinery_loss_of_profits` | Maschinen-Betriebsunterbrechung | Machinery Loss of Profits | MLOP | Betrieb | Ertragsausfall infolge eines gedeckten Maschinenschadens | belegt | [Eagle](https://www.eagle.mu/fr/node/37) |
| `electronic_equipment` | Elektronikversicherung | Electronic Equipment Insurance | EEI | Betrieb | Sachschäden an elektronischen Anlagen und Geräten | belegt | [Zurich DE](https://www.zurich.de/de-de/geschaeftskunden/produkte/technische-versicherung) |
| `advance_loss_of_profits` | Montage-/Bauleistungs-BU | Advance Loss of Profits / Delay in Start-up | ALOP, DSU | Bau, Montage | Ertragsausfall durch verzögerte Inbetriebnahme nach Projektschaden | belegt | [Munich Re](https://munichre.com/en/solutions/for-industry-clients/covers-and-services-for-construction-projects.html) |
| `civil_engineering_completed_risks` | Versicherung fertiggestellter Tiefbauwerke | Civil Engineering Completed Risks | CECR | Betrieb | fertige Straßen, Tunnel, Brücken, Bahnsysteme | belegt (EN) / offen (DE) | [Munich Re](https://munichre.com/en/solutions/for-industry-clients/covers-and-services-for-construction-projects.html) |
| `operational_all_risks` | Betriebs-Allgefahrenversicherung | Operational All Risks | OAR | Betrieb | Sach- und BU-Deckung für Kraftwerke, Windparks u. ä. | belegt (EN) / offen (DE) | [Munich Re US](https://munichre.com/us-non-life/en/solutions/reinsurance/facultative-engineering.html) |
| `deterioration_of_stock` | Kühlgut-/Verderbversicherung | Deterioration of Stock | DOS | Betrieb | Verderb gelagerter Waren nach Ausfall von Kühl- bzw. Maschinenanlagen | offen (DE) | [Chaucer](https://www.chaucergroup.com/classes/engineering) |
| `machinery_guarantee` | Garantieversicherung | Machinery Guarantee Insurance | – | Betrieb | Absicherung von Hersteller-Gewährleistungsrisiken für Maschinen | offen | [Aon](https://www.aon.com/germany/risk-services/technische-versicherungen) |
| `decennial_liability` | zehnjährige Bauwerkshaftung | Decennial Liability | IDI | nach Abnahme | Haftung für Baumängel über 10 Jahre (FR-Rechtsraum) | offen (DE) | [Munich Re](https://munichre.com/en/solutions/for-industry-clients/covers-and-services-for-construction-projects.html) |
| `builders_risk` | ≈ Bauleistungsversicherung (US) | Builders' Risk | BR | Bau | US-Pendant zu CAR, Sachdeckung des Bauwerks während der Bauzeit | belegt | [HUB](https://www.hubinternational.com/en-us/insurance-glossary/b/builders-risk/) |

### Produkt- und Strukturbegriffe

| key | de | en | Definition | status | Quelle |
|---|---|---|---|---|---|
| `site_policy` | Bauplatzpolice (CH) | project policy, wrap-up | eine Police für Bauwesen, Montage und Haftpflicht aller Baubeteiligten | belegt | [law.ch](https://law.ch/lawinfo/bauwesenversicherung/glossar-2/) |
| `testing_period` | Probebetrieb | testing / commissioning period | Erprobungsphase nach Montage; Teil der EAR-Deckung | belegt | [SGIC](https://sgic.com.np/products/engineering) |
| `annual_vs_project` | Jahres- vs. Projektpolice | renewable vs. non-renewable | Betriebssparten (MB, CPM, EEI) laufen jährlich; CAR/EAR laufen über die Projektdauer | belegt | [ICICI Lombard](https://corporate.icicilombard.com/Portal/Machinery_Breakdown) |
| `cover_chain` | Deckungskette | cover chain | Transport → Montage (ab Abladen) → Maschine/Elektronik (ab Betriebsfertigkeit) | belegt | [Württembergische](https://www.wuerttembergische.de/geschaeftskunden/technische-versicherungen/) |
| `gap_cover` | GAP-Deckung | GAP cover | deckt die Differenz zwischen Entschädigung und Restschuld der Finanzierung | belegt | [vermittlerportal](https://www.vermittlerportal.de/sach/sach-gewerbe/sach-produkte/sach-technische-versicherung/geschaeftspartnerinfo-technische-versicherung-tv416.pdf) |
| `mega_loss` | Großschaden (IMIA) | mega loss | nach IMIA-Definition ein Schaden über 30 Mio. USD ab dem ersten Dollar | belegt | [AXA XL](https://axaxl.com/fast-fast-forward/articles/engineering-insurance-in-the-mega-loss-era) |
| `munich_re_clauses` | Munich-Re-Klauseln | Munich Re (MR) clauses | Standard-Zusatzklauseln zu CAR/EAR | belegt | [ITU](https://polen.itu.edu.tr/items/3f2e0f5c-355a-4f94-a734-75df47053c02) |
| `design_clause` | Konstruktionsfehlerklausel | design defect clause (DE3, DE4) | LEG/DE-Klauseln zum Umfang der Deckung bei Planungsfehlern | offen | [Munich Re UK](https://munichre.com/specialty/global-markets-uk/en/solutions/construction-engineering-insurance/construction-insurance.html) |

---

## Sparte → GDV-Bedingungswerk (DE)

| Sparte (`key`) | AVB | Klauseln | Klauselblock |
|---|---|---|---|
| `machinery_breakdown` | AMB 2020 | TK AMB 2020 | 2xxx |
| `contractors_plant_machinery` | ABMG 2020 | TK ABMG 2020 | 3xxx |
| `electronic_equipment` | ABE 2020 | TK ABE 2020 | 1xxx |
| `erection_all_risks` | AMoB 2021 | TK AMoB 2021 | 7xxx |
| `contractors_all_risks` | ABBL 2018 | TK ABBL 2018 | offen |
| `existing_structures` *(neu)* – Baubestandsversicherung | ABBV 2011 | TK ABBV 2011 | offen |
| `machinery_guarantee` | MGar 2024 | TK MGar 2024 | offen |
| `machinery_loss_of_profits` | AMBUB 2011 | TK AMBUB 2018 | offen |

Links: [[glossare-versicherung#GDV-Musterbedingungen Technische Versicherung (Primärquelle DE)]]

| key | de | Definition | status |
|---|---|---|---|
| `clause` | Klausel (TK) | standardisierte Vertragsergänzung zu einer AVB; `TK A` ändert den Besonderen Teil, `TK B` den Allgemeinen Teil | belegt (GDV) |
| `general_part` | Allgemeiner Teil (AT) | spartenübergreifende Regeln (Beginn, Beitrag, Obliegenheiten); GDV-Muster gemeinsam für Haftpflicht, D&O, Sach, TV ohne Projektgeschäft | belegt (GDV) |
| `special_part` | Besonderer Teil | spartenspezifischer Deckungsumfang (versicherte Sachen, Gefahren, Entschädigung) | belegt (GDV) |

## Offene Punkte

- `fachlich`-Einträge mit Primärquelle belegen (GDV-AVB, ACORD).
- DE-Äquivalente für CECR, OAR, DOS, Decennial verifizieren.
- DE3/DE4 sowie LEG-Klauseln definieren.
- `key`-Schlüssel gegen das ACORD Data Dictionary abgleichen und ggf. übernehmen.
