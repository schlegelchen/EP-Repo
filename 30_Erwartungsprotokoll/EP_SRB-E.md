---
typ: erwartungsprotokoll
zelle: SRB-E
fall: SRB
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

# Erwartungsprotokoll SRB × E

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *IR* = `Instrumentenregister_E_SRB_2026-09-29` (.md/.csv, dort die Quell-URLs je reg_id); *Dossier* = `Zelldossiers_2026-10-01/SRB-E.md` (nur t0-Angaben); *Rollen* = `Rollenregister_SRB_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (01.01.2021–30.06.2022, group_only = false, date_uncertain = false).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `Dk` (Sicherheit laut Quelle: sicher) — *Codes*, Zeile SRB-E.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | EU | Handel 2021: EU-27 60,3 %. Kapitalbestand 31.12.2021: EU-27 72,8 %, Russland 6,6 %, China 4,9 %. | *Codes* SRB-E; Dossier (IMF-DIP 31.12.2021) |
| 2 Sperrtatbestand (Verwundbarkeit) | ja | Gas 2021 zu 100 % aus Russland; Interkonnektor Bulgarien–Serbien im Bau zählt nicht; LNG nicht belegt. | *Codes* SRB-E; Dossier; *Mod* Nachtrag Eurostat-Gasbilanz 2021 |
| 3 Absicherung | ja | SAA (in Kraft 01.09.2013) | *Codes* SRB-E; Dossier |
| 4 Ebenen (nur I/P) | – | nicht einschlägig | *Codes* SRB-E |
| 5 Doppelperformanz | nein | – | *Codes* SRB-E |
| 6 beide / eine / keine / unklar | zu beiden | Gas, NIS, EAWU-Freihandel seit 10.07.2021 | *Codes* SRB-E |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung (aus *Codes*):** Handel 2021 EU-27 60,3 %; Kapitalbestand 31.12.2021 EU-27 72,8 %, Russland 6,6 %, China 4,9 %. Frage 2 ja: Gas 2021 zu 100 % aus Russland; der Interkonnektor Bulgarien–Serbien im Bau zählt nicht; LNG nicht belegt. Frage 3 ja: SAA (01.09.2013). Frage 6: Gas, NIS, EAWU-Freihandel seit 10.07.2021.

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

„verbindlich?“ nach 3.2.7 b (weit), neu beurteilt. Beleg = reg_id im IR (URL dort).

**2a Instrumente der Pole**

| Datum                         | Träger             | Pol                       | Instrument                                                                                | Typ (D1)                                                                                 | verbindlich?       | Adressat im Zielstaat | Beleg                                         |
| ----------------------------- | ------------------ | ------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------ | --------------------- | --------------------------------------------- |
| 2019-10-25 (Vorlauf)          | EAWU               | R (Zuordnung *zu klären*) | Unterzeichnung Freihandelsabkommen                                                        | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja (Vertrag)       | Staat                 | IR E-SRB-02                                   |
| 2020-03-26 (Vorlauf)          | EU                 | B                         | Ankündigung 93 Mio. EUR                                                                   | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | nein (Ankündigung) | Staat                 | IR E-SRB-03                                   |
| 2020-05-29 (Vorlauf)          | EU                 | B                         | IPA-Abkommen 70 Mio. EUR                                                                  | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja                 | Staat                 | IR E-SRB-04                                   |
| 2021-05-20                    | EIB / EU           | B (EIB *zu prüfen*)       | EIB 25 Mio. EUR + EU-Zuschuss 49,5 Mio. EUR, Gasinterkonnektor                            | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja                 | Staat / Netzbetreiber | IR E-SRB-05                                   |
| 2021-06-30                    | EIB                | B (*zu prüfen*)           | Darlehen 200 Mio. EUR                                                                     | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja                 | Staat                 | IR E-SRB-07                                   |
| 2021-07-10                    | EAWU               | R (*zu klären*)           | Freihandelsabkommen in Kraft; Datumsabweichung (TASS: 2024; ARIC: 2021), *zu prüfen*      | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja (Vertrag)       | Staat                 | IR E-SRB-08; Dossier (EEC-Seite, *zu prüfen*) |
| 2021-11-25 (Dossier-Nachtrag) | Gazprom / Russland | R                         | Gasvertrag um sechs Monate verlängert nach Treffen Putin–Vučić, Preis 270 USD beibehalten | Vortrag: Anreiz · bestätigt (Levi):ok                                                    | ja                 | Srbijagas / Staat     | Dossier-Nachtrag; Kontakt K5bbb5631d509       |
| 2022-05-29                    | Gazprom / Vučić    | R                         | Ankündigung Dreijahres-Gasvertrag                                                         | Vortrag: unklar (Ankündigung, Konditionen im Eintrag nicht belegt) · bestätigt (Levi):ok | nein (Ankündigung) | Staat                 | IR E-SRB-09                                   |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

**2b Kontext / Bestand:** Gazprom Neft 56,15 % an NIS (IR E-SRB-C1; die Angabe stammt aus einer Quelle von 2024 und gilt nicht für 2019–2022; NIS-Eigentum zu t0 durch die IMF-Datei nicht abgedeckt, nicht belegt). Gastrans: Gazprom Transgaz Krasnodar 51 %, Srbijagas 49 % (Dossier). Yugorosgaz-Anteile zu t0: nicht belegt.

**2c Dritt- und Multilateralakteure (nicht B/R):** China Exim (E-SRB-01); IWF (E-SRB-06, PCI 2021-06-18).

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Alle belegten Kontakte auf Ebene Staats-/Regierungschef. Kontakte zu Wirtschafts- oder Energieministern sind in *Kontakte* nicht erfasst.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| EU-Institutionen | Präsident Vučić; PM Brnabić | nicht belegt | kein Kontakt mit EU-Institutionen in *Kontakte* erfasst |
| EU-Mitgliedstaaten | PM Brnabić | dokumentiert (Spitzenebene) | Brnabić–Castex K321c4f3ed79d (2022-02-11); Brnabić–Baerbock Kac1b6729f4fd (2022-03-11) |
| EU (Wirtschaftsminister-/Energieminister-Ebene) | Wirtschaftsminister Atanasković, Energieminister Mihajlović (beide 28.10.2020–26.10.2022) | nicht belegt | kein Kontakt in *Kontakte* erfasst |
| Russland (Putin) | Präsident Vučić | dokumentiert | K5bbb5631d509 (2021-11-25, persönlich, A1), K7cd0b2fd688a (2022-04-06, Telefon) |
| Gazprom / Gazprom Neft (NIS) | – | nicht belegt | – |

Hinweis: PM Brnabić nach Quelle geschäftsführend ab 15.02.2022 (*Rollen*, *zu prüfen*). Informeller Träger Vučić: „Einschätzung“.

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 61 % (hoch) | 6 % (niedrig) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | hoch (EU-Exportanteil ca. 65 %); Alternativen *zu prüfen* | hoch (Gas 100 % aus Russland; BG–SRB nicht gleichwertig; LNG nicht belegt; Gas 14,7 % der Energie, davon ca. 35 % in Strom/Fernwärme, Eurostat 2021) | *Mod*; Nachtrag Eurostat-Gasbilanz 2021 (Bruttoverfügbarkeit 2.394,5 ktoe; Eigenproduktion ca. 12 %; Importe ca. 79 %; ca. 35,5 % Strom/Wärme, ca. 20 % Industrie, ca. 12 % Haushalte) |
| Staatskapazität (territorial / fiskalisch) | territorial 92,9 % (mittel); fiskalisch 1,83; v2x_rule 0,483 | – | V-Dem v16, 2021, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit WGI Government Effectiveness 2021 (Revision 2025, linearer Score): Estimate 0,085; Score 54,1 [90-%-Intervall 46,0–62,1]. Klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

**Nachtrag Interkonnektor Ungarn (06.10.2026, Anlass: Hinweis Levi mit ENTSOG-Karte):** Am Punkt Horgoš–Kiskundorozsma besteht eine Verbindung nach Ungarn. Der neue Ausgang der Gastrans-Leitung (Verlängerung TurkStream) ist seit 01.10.2021 kommerziell in Betrieb, technische Kapazität nur in Richtung Serbien → Ungarn ([Gastrans, Demand Assessment Report 2022](https://gastrans.rs/wp-content/uploads/2022/09/Demand-Assessment-Report_IP-Horgos-Kiskundorozsma_2022.pdf); [Gastrans, Beschreibung der Kopplungspunkte](https://gastrans.rs/transparency/short-summary-of-description-of-pipeline-and-interconnection-points-with-the-names-of-the-afo/?lang=en)). Für die Richtung Ungarn → Serbien sah die serbische Energieagentur am 05.03.2019 nur unterbrechbare kommerzielle Reverse-Kapazität vor ([Energy Community, MC 2019, Annex 23](https://www.energy-community.org/dam/jcr:86a1302f-f87c-4fbc-9e42-e67fdf0b499f/MC201912_Annex23.pdf), Ziff. 14). Ein Bezug nicht-russischen Gases über Ungarn bis t0 ist **nicht belegt**; die Mengenaufteilung der Einfuhren 2021 (Ungarn/Bulgarien) ist nicht erhoben. Die Karte ist undatiert und zeigt bereits die Verbindung Bulgarien–Serbien (Betrieb ab 12/2023), gibt also nicht den Stand zu t0 wieder. Folge für den Moderator: Verwundbarkeit gegenüber R bleibt „hoch“; es gibt eine zweite Route, aber keine belegte zweite Bezugsquelle.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung: für diese Zelle (E) nicht einschlägig, nicht erhoben. Kontext: NIS-Eigentum zu t0 nicht belegt.
- **H2** Ersatzbeziehung zugänglich: **nein, soweit belegt** (*zu prüfen* durch Levi). Beleg: Gas 2021 zu 100 % aus Russland (Dossier; *Mod*). Interkonnektor Bulgarien–Serbien in Bau (ab 14.01.2022, Dossier), nicht in Betrieb; Interkonnektor Ungarn–Serbien angekündigt, nicht in Betrieb; LNG-Zugang: nicht belegt.
- **H3** Blockadepotenzial: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H4** Ausgangsbedingung Brüsseler Kette: **ja, soweit belegt** (*zu prüfen*, Wortlaut): Eröffnung von Cluster 4 im 12.2021 (Dossier) als Entscheidung über Zugang zu den Beitrittsverhandlungen; Anforderungen/Benchmarks: *zu prüfen*; benannter Träger (Rat/Kommission): *zu prüfen*. Weitere Kandidaten: Kandidatenstatus 01.03.2012, Verhandlungsbeginn 21.01.2014, SAA in Kraft 01.09.2013 (Dossier). · Moskauer Kette: **ja, soweit belegt** (*zu prüfen*): Gasvertrag um sechs Monate verlängert, Preis 270 USD beibehalten, nach Treffen Putin–Vučić 25.11.2021 (Euronews 04.12.2021, sekundär; Kontakt K5bbb5631d509); EAWU-Freihandelsabkommen in Kraft 10.07.2021 (*zu prüfen*, Datumsabweichung).

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

**Erwartete Richtung:** unbestimmt
**Erwartete Blockade:** entfällt
**Konfidenz:** niedrig
**Begründung (2–4 Sätze):** Regelergebnis nach B6c, von Levi am 06.10.2026 übernommen (D9). Beide Pole haben verbindliche Mittel im Fenster mit Zugang, die Verwundbarkeit ist auf beiden Seiten hoch. Die D4-Ausnahme „alternative Gasquellen“ ist zu t0 nicht tragfähig belegt: Der Interkonnektor Horgoš–Kiskundorozsma lief ab 01.10.2021 in Richtung Serbien → Ungarn, Gas von Ungarn nach Serbien war nur als unterbrechbare kommerzielle Reverse-Kapazität vorgesehen, und Abschnitt 5 nennt keine gleichwertige Ersatzbeziehung (siehe Nachtrag in Abschnitt 4). Nach D4 folgt unbestimmt.

**Autorurteil Levi (B6b, 05.10.2026; D9, wird zusätzlich geprüft):** Richtung B · Blockade entfällt · Konfidenz hoch.
Westliche Sanktionen gegen Russland dürften auch Serbien zumindest indirekt beziehungsweise sekundär wirtschaftlich beeinflussen. Dies betrifft insbesondere den Energie- und Finanzsektor sowie Handelsbeziehungen mit russischen Unternehmen. Eine vollständige Abhängigkeit von russischen Gaslieferungen besteht jedoch nicht, da alternative Bezugsquellen grundsätzlich verfügbar sind, auch wenn diese mit höheren Kosten verbunden sein können. Strukturell bleibt die serbische Wirtschaft deutlich stärker mit der Europäischen Union verflochten als mit Russland. Auch China kann diese geografisch und wirtschaftlich bedingte Einbindung in den europäischen Wirtschaftsraum trotz wachsender Investitionen und Handelsbeziehungen nicht grundsätzlich ersetzen. In der E-Dimension ist daher keine grundlegende Verschiebung weg von Europa zu erwarten.

## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Cowork/Codex
- Ableitung durch: Levi 05.10.2026
