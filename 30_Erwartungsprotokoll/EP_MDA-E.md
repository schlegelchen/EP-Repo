---
typ: erwartungsprotokoll
zelle: MDA-E
fall: MDA
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

# Erwartungsprotokoll MDA × E

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *IR* = `Instrumentenregister_E_MDA_2026-09-29` (.md/.csv, dort die Quell-URLs je reg_id); *Dossier* = `Zelldossiers_2026-10-01/MDA-E.md` (nur t0-Angaben, einschließlich Nachtrag „Strom nach Herkunft“); *Rollen* = `Rollenregister_MDA_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (01.01.2021–30.06.2022, group_only = false, date_uncertain = false).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `Dk` (Sicherheit laut Quelle: eher sicher) — *Codes*, Zeile MDA-E.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | EU | Handel 2021: EU-27 49,1 % (Russland 12,9 %). Kapitalbestand 31.12.2021: EU-27 67,6 % (ohne Zypern/Niederlande 38,4 %), Russland 17,7 %. Premier Energy (EMMA Capital 71,25 %), größter Stromverteiler, EU-Herkunft nur über .cz-Domain, *zu prüfen*. | *Codes* MDA-E; Dossier (IMF-DIP 31.12.2021) |
| 2 Sperrtatbestand (Verwundbarkeit) | ja | Strom 74 % aus Cuciurgan (Inter RAO). Leitungen in die Ukraine vorhanden, Ersatzlieferungen 2021 nicht belegt (A1: kein belegter Ersatz = ja). Gas: Iași–Ungheni als Ersatz belegt. | *Codes* MDA-E; Dossier Nachtrag Strom: Ukraine 161 GWh = 4,5 %, Rumänien 0, „nicht spezifiziert“ 95,5 % (2021, Eurostat nrg_ti_eh); Russland 0 GWh |
| 3 Absicherung | ja | AA/DCFTA | *Codes* MDA-E; Dossier (AA/DCFTA angewandt 01.09.2014, in Kraft 01.07.2016) |
| 4 Ebenen (nur I/P) | – | nicht einschlägig | *Codes* MDA-E |
| 5 Doppelperformanz | nein | – | *Codes* MDA-E |
| 6 beide / eine / keine / unklar | zu beiden | – | *Codes* MDA-E |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung (aus *Codes*):** Handel 2021 EU-27 49,1 % (Russland 12,9 %), Kapitalbestand EU-27 67,6 % (ohne Zypern/Niederlande 38,4 %), Russland 17,7 %. Premier Energy (EMMA Capital 71,25 %) größter Stromverteiler, EU-Herkunft nur über .cz-Domain, *zu prüfen*. Frage 2 ja: Strom 74 % aus Cuciurgan (Inter RAO); Leitungen zur Ukraine vorhanden, Ersatzlieferungen 2021 nicht belegt (A1); Gas: Iași–Ungheni als Ersatz belegt. Frage 3 ja: AA/DCFTA. Kipplinie laut Quelle: „mit belegten Stromlieferungen aus der Ukraine → B“.

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

„verbindlich?“ nach 3.2.7 b (weit), neu beurteilt. Beleg = reg_id im IR (URL dort).

**2a Instrumente der Pole**

| Datum                | Träger                  | Pol                           | Instrument                                                                                                  | Typ (D1)                                                                                                               | verbindlich?                                          | Adressat im Zielstaat | Beleg       |
| -------------------- | ----------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------- | ----------- |
| 2019-10 (Vorlauf)    | EU                      | B                             | MFA, erste Tranche 30 Mio. EUR                                                                              | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-01 |
| 2020-04-17 (Vorlauf) | Finanzministerium RU    | R                             | Darlehen 200 Mio. EUR mit Beschaffungsbindung (Wirksamkeit begrenzt)                                        | Vortrag: Anreiz (Konditionalität: Beschaffungsbindung, Instrument-Zelle) · bestätigt (Levi):ok                         | ja (Finanzierungszusage mit Konditionalität)          | Staatshaushalt        | IR E-MDA-02 |
| 2020-05-25 (Vorlauf) | EU                      | B                             | MFA 100 Mio. EUR                                                                                            | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-05 |
| 2020-07 (Vorlauf)    | EU                      | B                             | zweite Tranche 30 Mio. EUR (dritte Tranche entfallen)                                                       | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-06 |
| 2020-08-27 (Vorlauf) | EBRD / EIB              | B (EIB) / multilateral (EBRD) | EBRD 20 Mio. EUR + EIB 38 Mio. EUR, Gasleitung Ungheni–Chișinău                                             | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja (Finanzierungszusage); Trägerzuordnung *zu prüfen* | Staat / Netzbetreiber | IR E-MDA-07 |
| 2020-11-25 (Vorlauf) | EU                      | B                             | MFA-Tranche 50 Mio. EUR                                                                                     | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-08 |
| 2021-06-02           | EU                      | B                             | Plan bis zu 600 Mio. EUR                                                                                    | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | nein (Plan)                                           | Staat                 | IR E-MDA-09 |
| 2021-09-30           | Gazprom                 | R                             | Vertragsverlängerung um 1 Monat, Mengenkürzung, Preis ca. 550 → ca. 790 USD, Schuldforderung > 700 Mio. USD | Vortrag: Zwang · bestätigt (Levi):ok                                                                                   | ja (Liefer-/Preismaßnahme)                            | Moldovagaz / Staat    | IR E-MDA-10 |
| 2021-10-08           | EU                      | B                             | MFA zweite Tranche 50 Mio. EUR                                                                              | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-11 |
| 2021-10-27           | EU                      | B                             | Zusage 60 Mio. EUR                                                                                          | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | nein für sich (bindend mit E-MDA-16)                  | Staat                 | IR E-MDA-13 |
| 2021-10-29           | Gazprom                 | R                             | Fünfjahresvertrag ab 01.11.2021                                                                             | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja (Vertrag)                                          | Moldovagaz            | IR E-MDA-14 |
| 2021-12-21           | EU                      | B                             | Zuschuss 60 Mio. EUR als Budgethilfe mit Konditionalität                                                    | Vortrag: Anreiz (Konditionalität: „mit Konditionalität“, Instrument-Zelle; Inhalt nicht genannt) · bestätigt (Levi):ok | ja                                                    | Staatshaushalt        | IR E-MDA-16 |
| 2022-01-19           | Rumänien                | B (Mitgliedstaat)             | Eintrag laut IR                                                                                             | Vortrag: unklar (Inhalt des Eintrags nicht ausgewiesen) · bestätigt (Levi):ok                                          | nein                                                  | Staat                 | IR E-MDA-17 |
| 2022-03-16           | ENTSO-E / Moldelectrica | B (Zuordnung *zu klären*)     | Synchronisation der Netze                                                                                   | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Netzbetreiber         | IR E-MDA-18 |
| 2022-04-06           | EU                      | B                             | MFA 2022–2024, 150 Mio. EUR                                                                                 | Vortrag: Anreiz · bestätigt (Levi):ok                                                                                  | ja                                                    | Staatshaushalt        | IR E-MDA-19 |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

**2b Kontext / Bestand:** Gazprom 2,89 / 3,05 Mrd. m³ (IR E-MDA-C2). Gas 2021: 98,6 % Russland (Dossier).

**2c Dritt- und Multilateralakteure (nicht B/R):** PGNiG/Vitol, Spotgas 2021-10-27 (E-MDA-12); IWF (E-MDA-03, -15, -20); Verfassungsgericht 2020-05-07 (E-MDA-04, Ereignis zu E-MDA-02, kein Poleinsatz).

Nicht übernommen: erste Auszahlung 01.08.2022 und russisches Importverbot August 2022 (nach Stichtag).

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Alle belegten Kontakte auf Ebene Staats-/Regierungschef (Kontakte der Präsidentin Sandu). Kontakte zu Wirtschafts- oder Energieministern sind in *Kontakte* nicht erfasst.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| EU-Institutionen | Präsidentin Sandu (ab 24.12.2020); PM Gavrilița (ab 06.08.2021) | dokumentiert (Spitzenebene) | Michel: K3e845324faeb (2021-02-28), K8d44c4b5eca9 (2021-11-22, Video), K2ef78b28bb55 (2021-12-15); von der Leyen: K26a2eb84f6aa (2021-10-26), K88d33e20d673 (2021-12-15); Borrell: K33f8d93563b8 (2021-12-15) |
| EU-Mitgliedstaaten | Präsidentin Sandu | dokumentiert | Merkel: K91898d255802 (2021-03-09, Video), K1f31fa6490e8 (2021-05-19); Nausėda: K439275027f78 (2021-04-09); Rutte: Ke6bfba3c671c (2021-07-08); Higgins: K4f1ea5b87ea2 (2021-07-12); Levits: Ke87a494f1298 (2021-07-14); Macron: K8c6e934b664b (2021-11-12), K064bd26ed78e (2022-02-26), K956006ef7df8 (2022-05-19), Kc62b18d864bb (2022-06-15) |
| EU (Wirtschafts-/Energieminister-Ebene) | Wirtschaftsminister Gaibu (ab 06.08.2021); Infrastrukturminister Spînu (Energiezuständigkeit *zu prüfen*) | nicht belegt | kein Kontakt in *Kontakte* erfasst |
| Russland (Spitze) | Präsidentin Sandu | nicht belegt | kein russischer Kontakt in *Kontakte* erfasst |
| Gazprom (Verhandlungen mit Moldovagaz) | Vizepremier/Infrastrukturminister Spînu; Gazprom-Vorstand Miller | nicht belegt (Vermerk: Verhandlungsebene, nicht Kontakttag; Primärbeleg nicht im gelesenen Material; *zu prüfen*; bisher „dokumentiert“) | Faktenprüfung 29.09.2026 laut Machbarkeitsprüfung §3; Primärbeleg nicht im gelesenen Material |

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 55 % (hoch) | 11 % (niedrig) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | hoch (EU-Exportanteil ca. 64 %, DCFTA, MFA); Alternativen *zu prüfen* | hoch (Strom ca. 74 % Cuciurgan; Ukraine-Importe 2021 nur 4,5 %; Gasalternative Iași–Ungheni) | *Mod* |
| Staatskapazität (territorial / fiskalisch) | territorial 76,7 % (niedrig); fiskalisch 0,72; v2x_rule 0,765 | – | V-Dem v16, 2021, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit WGI Government Effectiveness 2021 (Revision 2025, linearer Score): Estimate −0,177; Score 48,7 [90-%-Intervall 41,2–56,2]. Klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung: für diese Zelle (E) nicht einschlägig, nicht erhoben. Kontext: Premier Energy (EMMA Capital 71,25 %), EU-Herkunft *zu prüfen* (*Codes*).
- **H2** Ersatzbeziehung zugänglich: **Gas: ja** — Interkonnektor Iași–Ungheni, 5,076 Mio. m³/Tag seit 01.10.2021 (Dossier); kein Gasspeicher 2021 (Dossier). **Strom: nein, soweit belegt** (*zu prüfen* durch Levi) — Leitungen zur Ukraine vorhanden, Ersatzlieferungen 2021 nicht belegt: Ukraine 161 GWh = 4,5 %, Rumänien 0, „nicht spezifiziert“ 95,5 % (Eurostat nrg_ti_eh, 2021; Dossier-Nachtrag); MGRES 74 % der Versorgung rechtes Ufer 2021 (Dossier). Die Kipplinie in *Codes* hängt an belegten Stromlieferungen aus der Ukraine.
- **H3** Blockadepotenzial: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H4** Ausgangsbedingung Brüsseler Kette: **zu prüfen**. Kandidaten bis 23.02.2022: AA/DCFTA (in Kraft 01.07.2016), MFA-Tranchen mit Konditionalität (IR E-MDA-08, -11). Ob eine an Anforderungen gebundene Entscheidung eines benannten Trägers über Status oder Zugang vorliegt, geben die gelesenen Eingaben nicht her. · Moskauer Kette: **ja, soweit belegt** (*zu prüfen*): Darlehen 200 Mio. EUR vom 17.04.2020 (Ressourcenzuteilung mit Beschaffungsbindung, Wirksamkeit begrenzt; IR E-MDA-02); Fünfjahresvertrag Gazprom ab 01.11.2021 (IR E-MDA-14); EAWU-Beobachterstatus 14.05.2018 (Dossier, Moldova.org, sekundär).

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
**Begründung (2–4 Sätze):** Die bereits stark ausgeprägten Handelsbeziehungen mit der EU dürften auch unter Kriegsbedingungen nicht zugunsten einer stärkeren wirtschaftlichen Orientierung an Russland aufgegeben werden. Im Gegenteil würde ein fortdauernder Krieg in der Ukraine Moldau geografisch und infrastrukturell noch stärker vom russischen Wirtschaftsraum abschneiden und damit die Möglichkeiten einer erneuten wirtschaftlichen Hinwendung zu Russland zusätzlich begrenzen. Dies gilt insbesondere für den Energiesektor. Zwar bestanden hier lange erhebliche Abhängigkeiten von russischen Gaslieferungen, aufgrund inzwischen verfügbarer alternativer Lieferwege und der vergleichsweise geringen Größe des moldauischen Marktes erscheint eine Kompensation ausfallender russischer Lieferungen grundsätzlich möglich. In der E-Dimension ist daher eher mit einer weiteren Verfestigung der europäischen Orientierung als mit einer Rückverschiebung zugunsten Russlands zu rechnen.

## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Cowork/Codex
- Ableitung durch: Levi 05.10.2026