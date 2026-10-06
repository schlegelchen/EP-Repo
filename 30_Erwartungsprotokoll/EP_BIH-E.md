---
typ: erwartungsprotokoll
zelle: BIH-E
fall: BIH
dimension: E
hypothese: H2
stichtag_eingaben: 2022-02-23
stichtag_mechanismen: 2022-06-30
regelwerk: Regelwerk_Codierung_v3.1_2026-10-05
eingaben_von: Claude (Cowork), Eingabepaket EP1 Session 2
ableitung_von: Levi
erstellt_am: 2026-10-05
kenntnis_endzustand: teilweise
blindheitsstufe: 3
status: fixiert
fixiert_am: 2026-10-06
sha256:
tags:
  - erwartungsprotokoll
---

# Erwartungsprotokoll BIH × E

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *IR* = `Instrumentenregister_E_BIH_2026-09-29` (.md/.csv, dort die Quell-URLs je reg_id); *Dossier* = `Zelldossiers_2026-10-01/BIH-E.md` (nur t0-Angaben); *Rollen* = `Rollenregister_BIH_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (01.01.2021–30.06.2022, group_only = false, date_uncertain = false).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `B` (Sicherheit laut Quelle: sicher) — *Codes*, Zeile BIH-E.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | EU | Handel 2021: EU-27 64,5 %. Kapitalbestand 31.12.2021: EU-27 61,2 %, Russland 2,7 %. | *Codes* BIH-E; Dossier (IMF-DIP 31.12.2021) |
| 2 Sperrtatbestand (Verwundbarkeit) | nein | Gas 100 % aus Russland ohne zweite Anbindung, aber nur 2,8 % der Energie; Strom 54,6 % und Mineralölprodukte 72,1 % aus der EU. | *Codes* BIH-E; Dossier (2021) |
| 3 Absicherung | ja | SAA (in Kraft 01.06.2015), Energiegemeinschaft | *Codes* BIH-E; Dossier |
| 4 Ebenen (nur I/P) | – | nicht einschlägig | *Codes* BIH-E |
| 5 Doppelperformanz | nein | – | *Codes* BIH-E |
| 6 beide / eine / keine / unklar | in der Quelle nicht ausgefüllt | – | *Codes* BIH-E |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung (aus *Codes*):** Handel 2021 EU-27 64,5 %; Kapitalbestand 31.12.2021 EU-27 61,2 %, Russland 2,7 %. Frage 2 nein: Gas 100 % aus Russland ohne zweite Anbindung, aber nur 2,8 % der Energie; Strom 54,6 % und Mineralölprodukte 72,1 % aus der EU. Frage 3 ja: SAA (01.06.2015), Energiegemeinschaft.

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

„verbindlich?“ nach 3.2.7 b (weit), neu beurteilt. Beleg = reg_id im IR (URL dort).

**2a Instrumente der Pole**

| Datum                | Träger                           | Pol                                      | Instrument                                                | Typ (D1)                                                                                       | verbindlich?                                          | Adressat im Zielstaat | Beleg       |
| -------------------- | -------------------------------- | ---------------------------------------- | --------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------- | ----------- |
| 2019-05-09 (Vorlauf) | EBRD, mit EU-WBIF-Kofinanzierung | multilateral / B (Zuordnung *zu prüfen*) | Darlehen bis 210 Mio. EUR, Korridor Vc                    | Vortrag: Anreiz · bestätigt (Levi):ok                                                          | ja (Finanzierungszusage); Trägerzuordnung *zu prüfen* | Staat / Entitäten     | IR E-BIH-02 |
| 2020-04-22 (Vorlauf) | EU                               | B                                        | MFA-Vorschlag                                             | Vortrag: Anreiz · bestätigt (Levi):ok                                                          | nein                                                  | Staat                 | IR E-BIH-04 |
| 2020-04-29 (Vorlauf) | EU                               | B                                        | COVID-Paket                                               | Vortrag: unklar (Paket, Inhalt im Eintrag nicht ausgewiesen) · bestätigt (Levi):ok             | nein / *zu prüfen*                                    | Staat                 | IR E-BIH-05 |
| 2020-05-25 (Vorlauf) | EU                               | B                                        | MFA 250 Mio. EUR in zwei Tranchen mit MoU-Konditionalität | Vortrag: Anreiz (Konditionalität: MoU-Konditionalität, Instrument-Zelle) · bestätigt (Levi):ok | ja                                                    | Staatshaushalt        | IR E-BIH-06 |
| 2020-12-17 (Vorlauf) | EU                               | B                                        | Investitionsplan, erste Leitinvestitionen                 | Vortrag: Anreiz · bestätigt (Levi):ok                                                          | Projektzuschüsse ja; Plan nein                        | Staat                 | IR E-BIH-07 |
| 2021-10-08           | EU                               | B                                        | MFA, erste Tranche 125 Mio. EUR                           | Vortrag: Anreiz · bestätigt (Levi):ok                                                          | ja                                                    | Staatshaushalt        | IR E-BIH-08 |
| 2021-12-02           | Putin / Dodik / Gazprom          | R                                        | Pläne (Gasprojekte), Entitätsebene RS                     | Vortrag: Sozialisierung · bestätigt (Levi):ok                                                  | nein (Pläne, Erklärung)                               | Entität RS            | IR E-BIH-09 |
| 2022-06-01           | Gazprom Export / Energoinvest    | R                                        | Verlängerung bis 31.12.2022                               | Vortrag: Anreiz · bestätigt (Levi):ok                                                          | ja (Vertrag); Regierungsbeteiligung nicht belegt      | Energoinvest          | IR E-BIH-10 |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

**2b Kontext / Bestand:** Gazprom Export ca. 400 Mio. m³/Jahr (IR E-BIH-C1, *zu prüfen*). Einziger Einspeisepunkt Zvornik, Lieferung über TurkStream; Annex Energoinvest ab 01.04.2021 (RFE/RL Bosnisch 05.04.2021); vorzeitige Kündigung des FGSZ-Transportvertrags mit 23 Mio. USD Vertragsstrafe, umstritten (Dossier).

**2c Dritt- und Multilateralakteure (nicht B/R):** China Exim (E-BIH-01; Bürgschaft des Föderationsparlaments 2019-03-07); IWF (E-BIH-03).

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Alle belegten Kontakte auf Ebene Staats-/Regierungschef bzw. Entitätsspitze. Kontakte zu Außenhandelsminister Košarac oder anderen Fachministern sind in *Kontakte* nicht erfasst. Ein föderales Energieministerium ist im Register nicht verzeichnet; die Entitätsebene ist im Register nicht abgedeckt.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| EU-Institutionen | Vorsitzender des Ministerrats Tegeltija (23.12.2019–25.01.2023) | dokumentiert | Borrell: K3121ce7df5f8 (2021-05-18, persönlich, A1); Várhelyi: K7a228196bd16 (2021-05-19), K0573459742dd (2021-11-23) |
| EU-Mitgliedstaaten | Tegeltija; RS-Präsidentin Cvijanović | dokumentiert | Merkel: Kfca01e30c238 (2021-06-30, Telefon), Kab9e4fa9d7a9 (2021-09-14, persönlich); Plenković: K67f2badb939e (2021-12-02), K78859f2e18ab (2021-12-13); Orbán–Cvijanović: Kae418e3cad75 (2021-10-04, persönlich) |
| EU (Fachministerebene) | Außenhandelsminister Košarac (23.12.2019–25.01.2023) | nicht belegt | kein Kontakt in *Kontakte* erfasst |
| Russland (Spitze) | Präsidentschaft (Dodik, Džaferović, Komšić); Tegeltija | nicht belegt | kein russischer Kontakt in *Kontakte* erfasst |
| Gazprom Export / Energoinvest | – | nicht belegt | Vertragsvorgänge im IR (E-BIH-10, nach Stichtag 23.02.2022), keine Kontaktdaten |

Informeller Träger Dodik: im Register „Einschätzung“.

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 66 % (hoch) | 2 % (niedrig) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | hoch (EU-Exportanteil ca. 72 %); Alternativen *zu prüfen* | niedrig (Gas 100 % russisch, aber nur 2,8 % der Energie) | *Mod* |
| Staatskapazität (territorial / fiskalisch) | territorial 88,3 % (mittel); fiskalisch 1,09; v2x_rule 0,387 | – | V-Dem v16, 2021, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit WGI Government Effectiveness 2021 (Revision 2025, linearer Score): Estimate −0,806; Score 35,9 [90-%-Intervall 27,5–44,2]. Klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H2** Ersatzbeziehung zugänglich: **nein beim Gas, soweit belegt** (*zu prüfen* durch Levi). Beleg: Gas 100 % russisch über einen einzigen Einspeisepunkt (Zvornik, TurkStream), keine zweite Anbindung (*Codes*; Dossier, 2021). Gas macht nur 2,8 % der Energie aus; Strom zu 54,6 % und Mineralölprodukte zu 72,1 % aus der EU (Dossier, 2021). Energiegemeinschaft: Datum des Vertragsparteistatus im Dossier nicht erhoben.
- **H3** Blockadepotenzial: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H4** Ausgangsbedingung Brüsseler Kette: **zu prüfen**. Kandidaten bis 23.02.2022: SAA in Kraft 01.06.2015; Antrag Februar 2016 (Dossier); MFA mit MoU-Konditionalität (IR E-BIH-06, -08). Eine an Anforderungen gebundene Entscheidung eines benannten Trägers über Status oder Zugang (z. B. Kandidatenstatus) ist in den gelesenen Eingaben nicht benannt. · Moskauer Kette: **nicht belegt** (Pläne vom 02.12.2021, Entitätsebene, sind Erklärung, kein dokumentierter Akt; die Vertragsverlängerung 01.06.2022 liegt nach dem Stichtag 23.02.2022).

## 6 Ableitung (Levi)

**Ableitungsregeln nach Dimension**

*E, M, P (H2, H3, H4):*
1. Verbindliche Mittel im Zählfenster mit Zugang (D2, D3) — B: ja/nein · R: ja/nein. Nur ein Pol → dessen Richtung. Keiner → unbestimmt.
2. Falls beide: Typ Sozialisierung/Anreiz überwiegt und Linkage B > R (Rohwert) → B. Typ Zwang/Anreiz überwiegt und Verwundbarkeit R > B (qualitativ) → R. Gleichstand der Verwundbarkeit (beide hoch oder beide niedrig) → unbestimmt, außer ein Gefälle wird qualitativ begründet (Logik Frage 2; D4). Widersprechen sich beide Prüfungen → unbestimmt.
3. Nur M (H3, D5): Blockade fortbestehend? Ja, wenn das Hindernis aus Abschnitt 5 zu t0 besteht und im Zählfenster keine berührende Entscheidung (H3-Kategorien) belegt ist. In E und P: „entfällt“.

*I (H1, D6):* Abschnitt 2 ist für I nicht erhoben und wird als solcher offengelegt; die Ableitung stützt sich auf Abschnitt 5.
1. Keine Trägerveränderung bis Stichtag → erwartete Richtung = Fortbestand der t0-Orientierung (keine Verschiebung zu einem Pol).
2. Ersetzung oder Konversion → erwartete Richtung = Orientierung des neuen bzw. konvertierten Trägers laut belegter Selbstbeschreibung (B/R); ohne belegte Selbstbeschreibung → unbestimmt.
3. Blockade: entfällt.
*Formulierung der I-Regel: Vorschlag Claude zu D6, von Levi bestätigt am 05.10.2026.*

**Erwartete Richtung:** B
**Erwartete Blockade:** entfällt
**Konfidenz:** hoch
**Begründung (2–4 Sätze):** Bosniens wirtschaftliche Verflechtung mit Europa wird auch künftig dominierend bleiben. Aufgrund der geografischen Lage des Landes, seiner engen Einbindung in den europäischen Wirtschaftsraum und der deutlich größeren wirtschaftlichen Anziehungskraft der EU verfügt Russland nur über begrenzte Möglichkeiten, in dieser Dimension als konkurrierender Integrationspol aufzutreten. Eine grundlegende Verschiebung der wirtschaftlichen Orientierung Bosniens zugunsten Russlands ist daher kaum zu erwarten.
## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Cowork/Codex
- Ableitung durch: Levi 05.10.2026
