---
typ: erwartungsprotokoll
zelle: ARM-M
fall: ARM
dimension: M
hypothese: H3
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

# Erwartungsprotokoll ARM × M

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *MSR* = `M_Statusregister_korrigiert_2026-09-29.csv` (Datenablage M_Register_2026-09-26); *Dossier* = `Zelldossiers_2026-10-01/ARM-M.md` (nur t0-Angaben); *H3* = `30_Erwartungsprotokoll/H3_Kategorien_fixiert.md` (Status entwurf); *Rollen* = `Rollenregister_ARM_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (01.01.2021–30.06.2022, group_only = false, date_uncertain = false).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `R` (Sicherheit laut Quelle: eher sicher) — *Codes*, Zeile ARM-M.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | Russland | 102. Basis Gjumri, OVKS, Rüstungsbezüge 2019–2021 zu 81,1 % aus Russland/Belarus | *Codes* ARM-M; SIPRI-TIV-Fenster 2019–2021 (MSR/Dossier) |
| 2 Sperrtatbestand (Verwundbarkeit) | nein | Kein Sperrtatbestand auf Brüsseler Seite | *Codes* ARM-M |
| 3 Absicherung | ja | Stützpunktabkommen mit Protokoll 2010, OVKS-Vertrag | *Codes* ARM-M; Dossier (Protokoll 19.08.2010) |
| 4 Ebenen (nur I/P) | – | nicht einschlägig | *Codes* ARM-M |
| 5 Doppelperformanz | nein | – | *Codes* ARM-M |
| 6 beide / eine / keine / unklar | in der Quelle nicht ausgefüllt | – | *Codes* ARM-M |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung (aus *Codes*):** 102. Basis Gjumri, OVKS, Rüstungsbezüge 2019–2021 zu 81,1 % aus Russland/Belarus. Frage 2 nein: kein Sperrtatbestand auf Brüsseler Seite. Frage 3 ja: Stützpunktabkommen mit Protokoll 2010, OVKS-Vertrag.

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

Beleg = Eintrag im *MSR* bzw. Dossier. „verbindlich?“ nach 3.2.7 b (weit). Im MSR ist für ARM kein Eintrag im Fenster 01.03.2021–23.02.2022 verzeichnet (Dossier).

| Datum                                                  | Träger           | Pol | Instrument                                                                                  | Typ (D1)                                             | verbindlich?                                                          | Adressat im Zielstaat                                                     | Beleg                        |
| ------------------------------------------------------ | ---------------- | --- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------- |
| 2020-11-09 (Vorlauf)                                   | Russland         | R   | Stationierung russischer Friedenstruppen in Bergkarabach, trilaterale Erklärung             | Vortrag: Anreiz · bestätigt (Levi):ok                | ja (Sicherheitsleistung); MSR: Regierungsakt „teilweise“, *zu prüfen* | Regierung ARM (Territorium Bergkarabach/Armenien: Einordnung *zu prüfen*) | MSR M-ARM-01                 |
| Bestand (2019–2025 laut MSR; nur Zeitraum bis t0 gilt) | Russland         | R   | 102. Basis Gjumri besteht fort                                                              | Vortrag: Bestand (kein Mittel) · bestätigt (Levi):ok | ja (Stationierungsvertrag, Bestand; kein neuer Akt im Fenster)        | Regierung                                                                 | MSR M-ARM-K1; Dossier        |
| 2019–2021 (Fenster)                                    | Russland/Belarus | R   | Rüstungslieferungen, SIPRI TIV 281 Mio., Anteil RUS/BLR 81,1 %, EU/USA/CAN 0, übrige 18,9 % | Vortrag: Bestand (kein Mittel) · bestätigt (Levi):ok | Einordnung als Mechanismus *zu prüfen* (Lieferungen, Bestandsmaß)     | Streitkräfte                                                              | MSR M_SIPRI_Fenster; Dossier |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

Brüsseler Seite (NATO, EU und Mitgliedstaaten): in den gelesenen Eingaben **nicht belegt** (kein M-Eintrag, SIPRI-Anteil EU/USA/CAN 0 im Fenster 2019–2021). Posten nach 23.02.2022 bis 30.06.2022: in den gelesenen Eingaben für ARM-M nicht belegt.

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Alle belegten Kontakte auf Ebene Staats-/Regierungschef. Kontakte zu Verteidigungsministern sind in *Kontakte* nicht erfasst.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| Russland (Putin) | PM Paschinjan; Verteidigungsminister: Tonojan bis 20.11.2020, Harutjunjan bis 03.08.2021, Karapetjan 03.08.–15.11.2021, Papikjan ab 15.11.2021 | dokumentiert (Spitzenebene) | 29 Kontakte, u. a. K20f7be54d5c9 (2021-01-11, persönlich), K42f1bb9e9c71 (2021-11-26, persönlich), K0d7eed5cc2f0 (2022-04-19, persönlich), K38d1ba8720c0 (2022-05-16, persönlich); vollständige ID-Liste in `EP_ARM-E.md`, Abschnitt 3 |
| Russland (Mischustin, Lawrow) | wie oben | dokumentiert | Kb08048efeb87, K6fdf52083834, K5fc9ad6e463a; K73baec025dae, K2d1f33e450e8, K87ef8e1a66fb |
| Russland (Verteidigungsministerium) | Verteidigungsminister ARM | nicht belegt | kein Kontakt in *Kontakte* erfasst |
| OVKS (Organisation) | – | nicht belegt | im *Kontakte*-Filter kein Kontakt mit OVKS-Trägern erfasst |
| EU-Institutionen (Michel) / EU-Mitgliedstaat (Macron) | PM Paschinjan | dokumentiert (Spitzenebene) | Michel: K10e45b4b17d4, K5066f5e25911, K3ff6e1d5715f, K213c88c39a5d, Ka102c628349a, K4309c244d78d, K78fb02beecd3, Kde9034657700, K07e231347de3, K673d185224d0; Macron: K0aa49df9a990, Kb286707c5502, K2e1256083e64, Kb20d95959331, K4ece7516c86f, K17c916fe0472, K45d18c192f76, K70e1d10c589b |
| NATO / Brüsseler Verteidigungsträger | Verteidigungsminister ARM | nicht belegt | kein Kontakt in *Kontakte* erfasst |

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 19 % (niedrig) | 29 % (mittel) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | niedrig (EU-Exportanteil ca. 20 %) | hoch (Gas ca. 88 % aus Russland, Netz 100 % Gazprom Armenia, keine gleichwertige Alternative) | *Mod* |
| Staatskapazität (territorial / fiskalisch) | territorial 96,4 % (hoch); fiskalisch 1,60; v2x_rule 0,718 | – | V-Dem v16, 2021, `vdem_v16.RData`, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit WGI Government Effectiveness 2021 (Revision 2025, linearer Score): Estimate −0,346; Score 45,3 [90-%-Intervall 37,4–53,1]. Klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (Export Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung: für diese Zelle (M) nicht einschlägig, nicht erhoben.
- **H2** Ersatzbeziehung: für diese Zelle (M) nicht einschlägig, nicht erhoben.
- **H3** Blockadepotenzial zu t0: **verankerte Bindung** (Festlegung nach *H3*, Status entwurf). Hindernisse zu t0: 102. Basis Gjumri (Abkommen 1995/1996, *zu prüfen*; Protokoll 19.08.2010, laut Dossier Laufzeit 49 Jahre ab 1995, Ablauf 2044), OVKS-Mitgliedschaft (Art. 4 und Art. 1 Abs. 2), Freundschaftsvertrag 1997, Vereinigte Streitkräftegruppe 30.11.2016 (Dossier). Russische Friedenstruppen in Bergkarabach sind nach *H3* **nicht** einbezogen (kein Beleg für „gegen den Willen“). Truppenstärke Basis 3.000 vs. 5.000: *zu prüfen*. Berührende Entscheidungskategorien: siehe `30_Erwartungsprotokoll/H3_Kategorien_fixiert.md` (Beschaffung, Übungen, Ausbildung, zivile Missionen sind nicht berührend).
- **H4** Ausgangsbedingung Brüsseler Kette: **nicht belegt** (kein an Anforderungen gebundener Beschluss eines benannten Trägers über Status oder Zugang im M-Bereich in den gelesenen Eingaben). · Moskauer Kette: **ja** (*zu prüfen* Wortlaut-Zuordnung): dokumentierte Schutzzusage über OVKS-Vertrag Art. 4 und Stützpunktabkommen mit Protokoll 19.08.2010; Beleg Dossier/*Codes*.

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
**Erwartete Blockade:** ja
**Konfidenz:** niedrig
**Begründung (2–4 Sätze):** Regelergebnis nach B6c, von Levi am 06.10.2026 übernommen (D9). Im Zählfenster ist kein Mittel eines Pols eingetragen (M-ARM-01, M-ARM-K1 und das SIPRI-Fenster sind Vorlauf bzw. Bestand), daher ergibt Schritt 1 unbestimmt. Abschnitt 5 nennt verankerte Hindernisse (Basis Gjumri mit Protokoll 19.08.2010, OVKS), und im Fenster ist keine berührende Entscheidung eingetragen; Blockade ja. Konfidenz niedrig, weil das Autorurteil abweicht.

**Autorurteil Levi (B6b, 05.10.2026; D9, wird zusätzlich geprüft):** Richtung R · Blockade nein · Konfidenz hoch.
Armenien befindet sich sicherheitspolitisch in einem strukturellen Dilemma: Gegenüber dem militärisch überlegenen Aserbaidschan ist es weiterhin auf externe Sicherheitsgarantien beziehungsweise einen Schutzpartner angewiesen. Eine stärkere Orientierung an EU, NATO oder einzelnen westlichen Staaten bleibt jedoch dadurch begrenzt, dass mit der Türkei ein enger Verbündeter Aserbaidschans selbst Mitglied der NATO ist. Damit ist ein einfaches Ersetzen Russlands durch einen westlichen Schutzpartner kaum möglich. Erst eine Normalisierung der armenisch-türkischen Beziehungen würde den außen- und sicherheitspolitischen Handlungsspielraum Armeniens wesentlich erweitern und ein tatsächliches Balancing zwischen Russland und westlichen Akteuren ermöglichen.
## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Cowork/Codex
- Ableitung durch: Levi 05.10.2026
