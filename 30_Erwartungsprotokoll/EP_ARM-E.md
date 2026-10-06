---
typ: erwartungsprotokoll
zelle: ARM-E
fall: ARM
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

# Erwartungsprotokoll ARM × E

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!note] Hinweis zum Entwurf
> Eingabepaket (Abschnitte 1–5). Abschnitte 6 und 7 bewusst leer. Quellenkürzel: *Codes* = `70_Cowork/Codes_t0_konsolidiert_2026-10-05.csv`; *IR* = `Instrumentenregister_E_ARM_2026-09-29` (.md/.csv, dort die Quell-URLs je reg_id); *Dossier* = `Zelldossiers_2026-10-01/ARM-E.md` (nur t0-Angaben übernommen); *Rollen* = `Rollenregister_ARM_2026-09-29`; *Mod* = `Moderatoren_t0_v2_2026-10-05`; *Kontakte* = `Elitenkontakte_Mehrjahre/06_Laenderbezogene_Kontakttage.json` (Filter: 01.01.2021–30.06.2022, group_only = false, date_uncertain = false). Das Feld `regelwerk` trägt den Wert der Vorlage v3; das aktuelle Regelwerk ist v3.1 (siehe offene Punkte).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung Runde 2):** `Dk` (Sicherheit laut Quelle: unsicher; Quelle: Runde 2) — übernommen aus *Codes*, Zeile ARM-E.

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | keine klar | Handel 2021: Russland 31,1 %, EU-27 19,1 %. Kapitalbestand 31.12.2021: Russland 31,9 %, EU-27 27,2 % (davon Zypern 11,3 %). Qualitätsregel A4: kein Abstand im Kapital. | *Codes* ARM-E; Dossier (IMF-DIP, 31.12.2021); Nacherhebung_E_ARM A.1 |
| 2 Sperrtatbestand (Verwundbarkeit) | in der Quelle nicht ausgefüllt | Quelle enthält keine Antwort zu Frage 2. Zu Gazprom Armenia (100 % Gasnetz) siehe Frage 6. | *Codes* ARM-E |
| 3 Absicherung | in der Quelle nicht ausgefüllt | Quelle enthält keine Antwort zu Frage 3. | *Codes* ARM-E |
| 4 Ebenen (nur I/P) | – | nicht einschlägig für E | *Codes* ARM-E |
| 5 Doppelperformanz | nein | – | *Codes* ARM-E |
| 6 beide / eine / keine / unklar | zu beiden | Russland: Gazprom Armenia hält 100 % des Gasnetzes. EU: Handel, Kapital (CEPA). | *Codes* ARM-E |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

**Begründung des Codes (aus *Codes*, wörtlich sinngemäß übernommen):** Handel 2021 Russland 31,1 %, EU-27 19,1 %; Kapitalbestand 31.12.2021 Russland 31,9 %, EU-27 27,2 % (davon Zypern 11,3 %). Gazprom Armenia hält 100 % des Gasnetzes. Qualitätsregel A4: kein Abstand im Kapital. Kipplinie laut Quelle: „bei weiterer Auslegung von ‚mit Abstand‘ → R“.

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge (in der Spalte Datum mit „(Vorlauf)“ gekennzeichnet) stehen als Bestand/Vorlauf und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

Spalte „verbindlich?“ nach 3.2.7 b (weit), neu beurteilt; die ältere Spalte des IR wurde nicht übernommen. Beleg = reg_id im IR (URL dort).

**2a Instrumente der Pole**

| Datum                               | Träger                    | Pol                                             | Instrument                                                     | Typ (D1)                                                                                                                | verbindlich?                                                     | Adressat im Zielstaat       | Beleg       |
| ----------------------------------- | ------------------------- | ----------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------- | ----------- |
| 2019-01-01 (Vorlauf)                | Gazprom                   | R                                               | Gaspreis 150 → 165 USD/1.000 m³                                | Vortrag: Zwang · bestätigt (Levi): ok                                                                                   | ja (Preismaßnahme)                                               | Regierung / Gazprom Armenia | IR E-ARM-01 |
| 2019-06-27 (Vorlauf)                | Rosatom/TVEL              | R                                               | Brennstofflieferung Metsamor                                   | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | ja (Liefervertrag); Einordnung als Mechanismus                   | Betreiber Metsamor          | IR E-ARM-03 |
| 2019-12-14 (Vorlauf)                | Finanzministerium RU      | R                                               | Antrag auf Kreditverlängerung                                  | Vortrag: unklar (Antrag, Annahme und Richtung des Vorteils nicht belegt) · bestätigt (Levi): ok                         | nein                                                             | Regierung                   | IR E-ARM-05 |
| 2020-03-31 bis 2020-04-06 (Vorlauf) | Gazprom                   | R                                               | Preisverhandlung                                               | Vortrag: Sozialisierung · bestätigt (Levi): ok                                                                          | nein                                                             | Regierung / Gazprom Armenia | IR E-ARM-06 |
| 2020-06-12 (Vorlauf)                | Regierung RU / Rosatom    | R                                               | Kredit 270 Mio. USD mit 80 % Beschaffungsbindung; ARM lehnt ab | Vortrag: Anreiz (Konditionalität: 80 % Beschaffungsbindung, Instrument-Zelle) · bestätigt (Levi): ok                    | ja (Finanzierungszusage mit Konditionalität); Wirkung: abgelehnt | Staatshaushalt              | IR E-ARM-08 |
| 2019–2020 (Vorlauf)                 | EU                        | B                                               | Jahresmittel ca. 65 Mio. EUR                                   | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | ja (Finanzierungszusagen); Kategorie-K im IR                     | Staat                       | IR E-ARM-K1 |
| 2019-Q4 (Vorlauf)                   | EIB                       | B (Zuordnung der EIB als EU-Träger *zu prüfen*) | Darlehen 4,2 Mio. EUR                                          | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | ja (Finanzierungszusage)                                         | Staat                       | IR E-ARM-04 |
| 2020-11 (Vorlauf)                   | EU                        | B                                               | Haushaltshilfe-Tranche 35,6 Mio. EUR mit Konditionalität       | Vortrag: Anreiz (Konditionalität: „mit Konditionalität“, Instrument-Zelle; Inhalt nicht genannt) · bestätigt (Levi): ok | ja                                                               | Staatshaushalt              | IR E-ARM-13 |
| 2020-12-23 (Vorlauf)                | EU                        | B                                               | 24 Mio. EUR mit Konditionalität                                | Vortrag: Anreiz (Konditionalität: „mit Konditionalität“, Instrument-Zelle; Inhalt nicht genannt) · bestätigt (Levi): ok | ja                                                               | Staatshaushalt              | IR E-ARM-14 |
| 2021-03-01                          | EU / Mitgliedstaaten      | B                                               | CEPA in Kraft                                                  | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | ja (Vertrag)                                                     | Staat                       | IR E-ARM-15 |
| 2021-07-09                          | EU-Kommission             | B                                               | Wirtschafts- und Investitionsplan, bis zu 2,6 Mrd.             | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | nein                                                             | Staat                       | IR E-ARM-16 |
| 2021 (Datum *zu prüfen*)            | EU                        | B                                               | Resilience Facility 23 Mio. EUR                                | Vortrag: Anreiz · bestätigt (Levi): ok                                                                                  | nein                                                             | Staat                       | IR E-ARM-17 |
| 2022-04-01 (Datum *zu prüfen*)      | Gazprom / Gazprom Armenia | R                                               | Anpassung Gaspreisformel (Brennwert)                           | Vortrag: unklar (Anpassung der Preisformel, Richtung des Vorteils nicht belegt) · bestätigt (Levi): ok                  | nein, Wirkung nicht belegt                                       | Gazprom Armenia             | IR E-ARM-19 |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

**2b Kontext / Bestand (keine Instrumente)**: GSP+ (IR E-ARM-C1); Gas-gegen-Strom-Tausch mit Iran (IR E-ARM-C2, Drittakteur); Gas 2021: 87,7 % Russland, 12,3 % Iran (Dossier).

**2c Dritt- und Multilateralakteure (nicht B/R)**: IWF (E-ARM-02, -07); Japan, USA, China; EFSD (E-ARM-12, Zuordnung zu R *zu prüfen*); EBRD 2021-09-14, Darlehen 70 Mio. USD an ENA (E-ARM-18).

Nicht übernommen: Einträge des IR mit Datum nach 30.06.2022 und Hinweise auf spätere Zeiträume.

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

Kontakte nur direkte Kontakte (Filter siehe oben). Alle belegten Kontakte liegen auf Ebene Staats- oder Regierungschef; Kontakte zu Wirtschafts- oder Energieministern sind in *Kontakte* nicht erfasst.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| EU-Institutionen (Michel) | PM Paschinjan (im Amt, Rücktritt 25.04.2021, geschäftsführend bis 08/2021, ab 02./06.08.2021 neu ernannt); Präsident Sarkissjan bis 01.02.2022 | dokumentiert (Spitzenebene) | Michel: K10e45b4b17d4 (2021-06-02, persönlich), K5066f5e25911 (2021-07-17, Sarkissjan, A1), K3ff6e1d5715f (2021-07-17), K213c88c39a5d (2021-11-16, Telefon), Ka102c628349a (2021-12-14, persönlich), K4309c244d78d (2022-03-09), K78fb02beecd3 (2022-04-06), Kde9034657700 (2022-04-18), K07e231347de3 (2022-04-22), K673d185224d0 (2022-05-22) |
| EU-Mitgliedstaat (Macron) | PM Paschinjan | dokumentiert | K0aa49df9a990 (2021-01-06, Telefon, A2), Kb286707c5502 (2021-04-24), K2e1256083e64 (2021-05-13), Kb20d95959331 (2021-06-01, persönlich), K4ece7516c86f (2021-08-03), K17c916fe0472 (2021-08-21), K45d18c192f76 (2022-03-01), K70e1d10c589b (2022-03-09, persönlich) |
| EU (Wirtschaftsminister-Ebene, Kerobyan ab 27.11.2020) | Wirtschaftsminister (Khachatryan bis 24.11.2020, Kerobyan ab 27.11.2020) | nicht belegt | kein Kontakt in *Kontakte* erfasst (keine Aussage über Zugang) |
| Russland (Putin) | PM Paschinjan | dokumentiert | 29 Kontakte, u. a. K20f7be54d5c9 (2021-01-11, persönlich), K42f1bb9e9c71 (2021-11-26, persönlich), K0d7eed5cc2f0 (2022-04-19, persönlich), K38d1ba8720c0 (2022-05-16, persönlich); übrige: Kfd1a4ff5926f, Kfcf294144df8, Kaa91e4799da4, Ke3a67c3538c7, K8a5a85389067, K6a787f7415fa, K59f79c8df51b, Kcae188a5941d, K68d360ddb45d, K8dd94e153338, K7dce8519a2ef, Kd72ebe8b47f8, K80d15d156f58, K9f650af5a38d, Kb9cf033a0512, K8314df7a0962, Ka6fd6eb4b0b2, K6da519250b57, Kf589f6df6110, Kbcb0dfaa8eb6, K715e994c2729, K2aaf3f25b672, K7f0a66d6a217, K04f3153fee95, K29f0773840a3 (2022-06-18, Chatschaturjan, A1) |
| Russland (Regierungschef Mischustin) | PM Paschinjan | dokumentiert | Kb08048efeb87 (2021-04-29, persönlich), K6fdf52083834 (2021-12-29, Telefon), K5fc9ad6e463a (2022-06-20, persönlich) |
| Russland (Lawrow) | PM Paschinjan / Außenminister | dokumentiert | K73baec025dae (2021-05-06, persönlich), K2d1f33e450e8 (2022-06-09), K87ef8e1a66fb (2022-06-09, Chatschaturjan, A1) |
| Gazprom / Gazprom Armenia | Preis-/Vertragsentscheider | nicht belegt | Preisverhandlungen als Vorgang im IR (E-ARM-06), kein Kontakt mit Namen der Entscheider erfasst |
| Russland (Wirtschafts-/Energieminister) | Wirtschaftsminister Kerobyan; Energiezuständigkeit Infrastrukturminister (Papikjan bis 02.08.2021, dann Sanosjan; Energiezuordnung *zu prüfen*) | nicht belegt | kein Kontakt in *Kontakte* erfasst |

Quelle der Rollen: *Rollen* (nur Rollen im Amt bis 30.06.2022 übernommen). Informeller Träger Samvel Karapetjan (Tashir/ENA): im Register als „Einschätzung“, Datierung *zu prüfen*; Herkunft von Tashir zu t0 nicht belegt.

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | 19 % (niedrig) | 29 % (mittel) | Außenhandelsanteil, Mittel Import/Export 2019–2021; Schwellen hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. *Mod* |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | niedrig (EU-Exportanteil ca. 20 %); „hoch“ auf B-Seite stützt sich in anderen Fällen auf den Exportanteil, Alternativen *zu prüfen* | hoch (Gas ca. 88 % aus Russland, Netz zu 100 % Gazprom Armenia, keine gleichwertige Alternative) | *Mod* |
| Staatskapazität (territorial / fiskalisch) | territorial 96,4 % (hoch); fiskalisch 1,60 (V-Dem v2stfisccap); v2x_rule 0,718 | – | V-Dem v16, 2021, `vdem_v16.RData`, eigene Auswertung, nicht zweitgeprüft (*Mod*) |

Robustheit (WGI Government Effectiveness 2021, Revision 2025, linearer Score, kein Perzentilrang): Estimate −0,346; Score 45,3 [90-%-Intervall 37,4–53,1]. Intervalle der Fälle überlappen weitgehend; klar getrennt sind nur BIH und GEO. V-Dem bleibt Hauptmaß (Entscheidung B1a, 05.10.2026). Quelle: `WGI_Government_Effectiveness_2026-10-05` (World-Bank-DataBank-Export, Stand 25.09.2026, abgerufen 05.10.2026; Wertjahr 2021).

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05. In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung bis Stichtag: für diese Zelle (E) nicht einschlägig, nicht erhoben. Kontextnotiz: ENA seit 2015 im Eigentum von Tashir (Dossier); Tashir-Herkunft zu t0 nicht belegt.
- **H2** Ersatzbeziehung zugänglich (Verbindung, Marktzugang, Anbieter): **nein, soweit belegt** (*zu prüfen* durch Levi). Beleg: Gas 2021 87,7 % Russland, 12,3 % Iran, fast vollständig über Georgien (Dossier). Iran-Leitung Tabriz–Meghri 2,3 Mrd. m³ (gebaut 2009); 2021 Tausch Iran von ca. 0,3446 Mrd. m³ gegen 1,034 TWh (Dossier). Verbindung nach Aserbaidschan besteht, in Betrieb nicht belegt. LNG: nicht belegt. Stromverbindungen: Georgien 220 kV + 110 kV, Iran 220 kV (Dossier). Der Iran-Anteil ist ein Drittanbieter, der die Abhängigkeit nicht ersetzt (Einschätzung der Moderatoren-Datei, *Mod*: „keine gleichwertige Alternative“).
- **H3** Blockadepotenzial: für diese Zelle (E) nicht einschlägig, nicht erhoben.
- **H4** Ausgangsbedingung Brüsseler Kette: **zu prüfen**. Kandidaten (bis 23.02.2022): CEPA in Kraft 01.03.2021 (Vertrag; IR E-ARM-15), Haushaltshilfe mit Konditionalität (IR E-ARM-13/-14). Ob darunter eine an Anforderungen gebundene Entscheidung eines benannten Trägers über *Status oder Zugang* liegt, geben die gelesenen Eingaben nicht her. · Moskauer Kette: **ja, soweit belegt** (*zu prüfen*): EAWU-Beitritt 10.10.2014 (in Kraft 02.01.2015, Dossier), Brennstoffliefervertrag TVEL (IR E-ARM-03), Gazprom Armenia 100 % Gasnetz (*Codes*); Kreditangebot 270 Mio. USD 2020 (IR E-ARM-08) wurde abgelehnt. Beleg jeweils wie angegeben; ein einzelner „Akt der Kooptation/Anerkennung/Schutzzusage/Ressourcenzuteilung“ im Fenster ist in den gelesenen Eingaben nicht benannt.

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
**Konfidenz:** niedrig
**Begründung (2–4 Sätze):** Regelergebnis nach B6c, von Levi am 06.10.2026 übernommen (D9). Im Zählfenster ist nur für B ein verbindliches Mittel mit Zugang eingetragen (CEPA in Kraft 01.03.2021, E-ARM-15); für R stehen im Fenster nur nicht verbindliche Einträge. Schritt 1 ergibt daher B. Konfidenz niedrig, weil Schritt 1 auf einer Zeile beruht und das Autorurteil abweicht.

**Autorurteil Levi (B6b, 05.10.2026; D9, wird zusätzlich geprüft):** Richtung R · Blockade entfällt · Konfidenz hoch.
In der E-Dimension sind zunächst keine größeren Verschiebungen zu erwarten. Zum einen stoßen armenische Produkte auf dem europäischen Markt auf erhebliche Wettbewerbs- und Zugangsbarrieren, zum anderen sind die bestehenden wirtschaftlichen Verflechtungen mit Russland weiterhin umfassend. Eine substanzielle Verschiebung dürfte daher kaum isoliert innerhalb der ökonomischen Dimension erfolgen, sondern wäre voraussichtlich an Veränderungen in den übrigen Dimensionen gekoppelt. Hinzu kommt, dass Armeniens angespannte Beziehungen zu Aserbaidschan und der Türkei seine Möglichkeiten zur Diversifizierung wirtschaftlicher und infrastruktureller Abhängigkeiten erheblich einschränken. Russland lässt sich unter diesen Bedingungen kurzfristig nur schwer ersetzen; zugleich erscheint auch eine stärkere einseitige Abhängigkeit vom Iran politisch und strategisch nicht als angestrebte Alternative. Eine kurzfristige Normalisierung der Beziehungen zu Aserbaidschan und der Türkei sind unwahrscheinlich.
## 7 Offenlegung

- Bekannt beim Ausfüllen: Teilweises Wissen durch Vorbereitung der Kapitel
- Eingaben erhoben von: Claude (Cowork)/Astra (Codex)
- Ableitung durch: Levi 05.10.2026
