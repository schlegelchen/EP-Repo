---
typ: erwartungsprotokoll
zelle: GEO-E
fall: GEO
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
status: entwurf
fixiert_am:
sha256:
tags:
  - erwartungsprotokoll
---

# Erwartungsprotokoll GEO × E

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *IR* = `Instrumentenregister_E_GEO_2026-09-29` (.md/.csv, dort die Quell-URLs je reg_id); *Dossier* = `Zelldossiers_2026-10-01/GEO-E.md` (nur t0-Angaben); *Rollen* = `Rollenregister_GEO_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (01.01.2021–30.06.2022, group_only = false, date_uncertain = false).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `Dk` (Sicherheit laut Quelle: eher sicher) — *Codes*, Zeile GEO-E.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | keine klar | Handel 2021: EU-27 21,1 %, Russland 11,4 %. Kapitalbestand 31.12.2021: EU-27 31,1 %, Aserbaidschan 20,3 %, UK 15,7 %, Russland 2,6 %. EU in beiden Kanälen größter Partner, aber keine Mehrheitsbeteiligung eines EU-Trägers an einem Netzbetreiber (A4 nicht erfüllt). | *Codes* GEO-E; Dossier (Geostat, 31.12.2021) |
| 2 Sperrtatbestand (Verwundbarkeit) | in der Quelle nicht ausgefüllt | – | *Codes* GEO-E |
| 3 Absicherung | in der Quelle nicht ausgefüllt | – | *Codes* GEO-E |
| 4 Ebenen (nur I/P) | – | nicht einschlägig | *Codes* GEO-E |
| 5 Doppelperformanz | nein | – | *Codes* GEO-E |
| 6 beide / eine / keine / unklar | zu beiden | EU: Handel, Kapital, AA/DCFTA, Energiegemeinschaft. Russland: Telasi 75 % Inter RAO, Rücküberweisungen 17,5 %. | *Codes* GEO-E |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung (aus *Codes*):** siehe Zeilen oben; Handel 2021 EU-27 21,1 %, Russland 11,4 %; Kapitalbestand 31.12.2021 EU-27 31,1 %, Aserbaidschan 20,3 %, UK 15,7 %, Russland 2,6 %; EU in beiden Kanälen größter Partner, aber keine Mehrheitsbeteiligung eines EU-Trägers an einem Netzbetreiber (A4 nicht erfüllt).

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

„verbindlich?“ nach 3.2.7 b (weit), neu beurteilt. Beleg = reg_id im IR (URL dort).

**2a Instrumente der Pole**

| Datum                                     | Träger          | Pol                                             | Instrument                                      | Typ (D1)                                                                                                               | verbindlich?                                          | Adressat im Zielstaat | Beleg       |
| ----------------------------------------- | --------------- | ----------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------- | ----------- |
| 2019-02-19 (Vorlauf)                      | EIB             | B (Zuordnung der EIB als EU-Träger *zu prüfen*) | Darlehen 250 Mio. EUR mit EU-Garantie           | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja (Finanzierungszusage)                              | Staat                 | IR E-GEO-01 |
| 2019-03-13 (Vorlauf)                      | Gazprom         | R                                               | Verlängerung Transitvertrag                     | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja (Vertrag)                                          | Staat / Netzbetreiber | IR E-GEO-02 |
| 2019-06-21 (wirksam 2019-07-08) (Vorlauf) | Präsident RU    | R                                               | Verbot von Direktflügen (Reisewarnung: nein)    | Vortrag: Zwang · bestätigt (Levi):ok                                                                                   | ja (Zwangsmaßnahme, Handelssperre); Reisewarnung nein | Luftverkehr / Staat   | IR E-GEO-03 |
| 2019-06-24 (Vorlauf)                      | Rospotrebnadzor | R                                               | Weinkontrollen                                  | Vortrag: unklar (Kontrollen, Nachteil im Eintrag nicht belegt; kein Importverbot im IR) · bestätigt (Levi):zwang       | nein / *zu prüfen* (kein Importverbot im IR belegt)   | Weinexporteure        | IR E-GEO-04 |
| 2020-04-09 (Vorlauf)                      | EU              | B                                               | Ankündigung COVID-Paket                         | Vortrag: unklar (Ankündigung, Inhalt im Eintrag nicht belegt) · bestätigt (Levi):ok                                    | nein                                                  | Staat                 | IR E-GEO-05 |
| 2020-05-25 (Vorlauf)                      | EU              | B                                               | Makrofinanzhilfe 150 Mio. EUR                   | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-GEO-07 |
| 2020-09-29 (Vorlauf)                      | EU              | B                                               | 129 Mio. EUR                                    | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | *zu prüfen* (Art der Mittel)                          | Staat                 | IR E-GEO-08 |
| 2020-11-25 (Vorlauf)                      | EU              | B                                               | MFA-Auszahlung 100 Mio. EUR mit Konditionalität | Vortrag: Anreiz (Konditionalität: „mit Konditionalität“, Instrument-Zelle; Inhalt nicht genannt) · bestätigt (Levi):ok | ja                                                    | Staatshaushalt        | IR E-GEO-09 |
| 2020-12-14 (Vorlauf)                      | EU              | B                                               | 60 Mio. EUR                                     | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | *zu prüfen* (Art der Mittel)                          | Staat                 | IR E-GEO-10 |
| 2021-06-02 (*zu prüfen*)                  | EU              | B                                               | Wirtschafts- und Investitionsplan 2,3 Mrd.      | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | nein (Plan)                                           | Staat                 | IR E-GEO-11 |
| 2021-07-01                                | EIB             | B (*zu prüfen*)                                 | 106,7 Mio. EUR Darlehen + 26 Mio. EUR Zuschuss  | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staat                 | IR E-GEO-12 |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

**2b Kontext / Bestand:** EU > 120 Mio. EUR/Jahr, DCFTA (IR E-GEO-C1); Gazprom ca. 200 Mio. m³ im Jahr 2021 (IR E-GEO-C3). Gasbezug 2021 über Aserbaidschan 84,6 %, über die russische Route 15,4 % (Dossier, GNERC); Energy Community Report 2021: Aserbaidschan 2.182,7 Mio. m³, Russland 396,8 Mio. m³.

**2c Dritt- und Multilateralakteure (nicht B/R):** IWF (E-GEO-06; E-GEO-13 vom 2022-06-15, 280 Mio. USD), SOCAR, China (Freihandelsabkommen).

Nicht übernommen: Streichung der zweiten MFA-Tranche (Datum im IR unbekannt, möglicherweise nach Stichtag, *zu prüfen*); Hinweise des IR auf Zeiträume nach 30.06.2022.

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Alle belegten Kontakte auf Ebene Staats-/Regierungschef. Kontakte zu Wirtschafts- oder Energieministern sind in *Kontakte* nicht erfasst.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| EU-Institutionen (Michel) | PM Gharibaschwili (ab 22.02.2021) | dokumentiert (Spitzenebene) | K94c122e72337 (2021-03-15), Kd6e333e210b4 (2021-03-16) |
| EU-Mitgliedstaat (Macron) | Präsidentin Surabischwili | dokumentiert | Kf278a8b68721 (2022-02-26, Telefon) |
| EU (Wirtschaftsministerebene) | Wirtschaftsminister Turnawa (18.04.2019–09.02.2022), Dawitaschwili ab 09.02.2022 | nicht belegt | kein Kontakt in *Kontakte* erfasst |
| Russland (Staats-/Regierungsspitze) | PM Gharibaschwili | nicht belegt | kein russischer Kontakt in *Kontakte* erfasst |
| Gazprom | Vertragsentscheider Transit/Lieferung | nicht belegt | Vertragsvorgang im IR (E-GEO-02), keine Kontaktdaten |
| Inter RAO (Telasi 75 %) | – | nicht belegt | – |

Energieminister: im *Rollen*-Register nicht identifiziert. Informeller Machtträger Iwanischwili (GD-Vorsitz bis 11.01.2021, dann Kobachidse): im Register als „Einschätzung“.

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 22 % (niedrig) | 12 % (niedrig) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | niedrig (EU-Exportanteil ca. 20 %) | niedrig (Gas überwiegend über Aserbaidschan; Telasi ist Investition, keine Lieferabhängigkeit) | *Mod* |
| Staatskapazität (territorial / fiskalisch) | territorial 80,9 % (niedrig); fiskalisch 0,93; v2x_rule 0,751 | – | V-Dem v16, 2021, `vdem_v16.RData`, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit WGI Government Effectiveness 2021 (Revision 2025, linearer Score): Estimate 0,339; Score 59,3 [90-%-Intervall 50,8–67,8]. Klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (Export Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung: für diese Zelle (E) nicht einschlägig, nicht erhoben. Kontext: Sakrusenergo 50 % Russische Föderale Netzgesellschaft (TI Georgia) bzw. 50/50 Inter RAO (IEA) — Quellen widersprechen sich (*zu prüfen*); GOGC/GGTC und GSE in Staatsbesitz (Dossier).
- **H2** Ersatzbeziehung zugänglich: **ja** (*zu prüfen* durch Levi). Beleg: Gas 2021 zu 84,6 % über Aserbaidschan (GNERC-Eintrittsroute), 15,4 % über die russische Route (Dossier; Energy Community Report 2021: Aserbaidschan 2.182,7 Mio. m³, Russland 396,8 Mio. m³). Energiegemeinschaft Vertragspartei seit 01.07.2017 (Dossier). Stromimporte aus Russland 25 % der Importe 2021 (Dossier); Ersatzquelle für Strom: nicht belegt.
- **H3** Blockadepotenzial: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H4** Ausgangsbedingung Brüsseler Kette: **zu prüfen**. Kandidaten bis 23.02.2022: AA/DCFTA seit 01.07.2016, MFA mit Konditionalität (IR E-GEO-09). Ob eine an Anforderungen gebundene Entscheidung eines benannten Trägers über Status oder Zugang vorliegt, geben die gelesenen Eingaben nicht her. · Moskauer Kette: **nicht belegt** (kein dokumentierter Akt der Kooptation, Anerkennung, Schutzzusage oder Ressourcenzuteilung in den gelesenen Eingaben; das Direktflugverbot 2019 ist eine Zwangsmaßnahme, keine Kooptation).

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
**Konfidenz:** mittel 
**Begründung (2–4 Sätze):**
In der wirtschaftlichen Dimension steht Georgien vor der Herausforderung, seine Position auf dem europäischen Markt weiter auszubauen. Dies gilt insbesondere für traditionelle Exportgüter wie Wein, deren Absatz in der EU jedoch auf einen stark umkämpften Markt trifft. Russland bleibt deshalb weiterhin ein bedeutender Absatzmarkt und begrenzt die Geschwindigkeit einer vollständigen wirtschaftlichen Neuorientierung. In welchem Umfang Georgien darüber hinaus zur Umgehung westlicher Sanktionen gegen Russland beiträgt oder künftig beitragen könnte, lässt sich nur schwer belastbar einschätzen, da entsprechende Handels- und Finanzströme häufig intransparent sind und sich einer unmittelbaren Beobachtung entziehen.

## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Cowork/Codex
- Ableitung durch: Levi 05.10.2026