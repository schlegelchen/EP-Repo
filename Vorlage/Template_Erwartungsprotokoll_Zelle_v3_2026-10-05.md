---
typ: erwartungsprotokoll
zelle: "{{FALL}}-{{DIM}}"
fall:
dimension:            # I / E / M / P
hypothese:            # H1 (I) / H2 (E) / H3 (M) / H4 (P)
stichtag_eingaben: 2022-02-23        # t0 = Ende des Fensters 01.03.2021–23.02.2022
stichtag_mechanismen: 2022-06-30     # F1, entschieden
regelwerk: Regelwerk_Codierung_v3.1_2026-10-05   # Codes E/M/I aus Runde 2 (v3); v3.1 ändert nur P
eingaben_von:         # Claude (Cowork), Eingabepaket EP1
ableitung_von:        # Levi (B6b); Claude leitet Abschnitt 6 nicht ab (D7)
erstellt_am:
kenntnis_endzustand:  # ja / teilweise / nein (Levi)
blindheitsstufe: 3    # F2 (04.10.): Levi füllt aus, Ableitung nach Regel
status: entwurf       # entwurf / fixiert
fixiert_am:
sha256:
tags: [erwartungsprotokoll]
---

# Erwartungsprotokoll {{FALL}} × {{DIM}}

> [!warning] Nur Belege mit Datum ≤ Stichtag. Endzustand t1 hier **nicht** eintragen.

> [!info] Vorlage v3 (05.10.2026). Änderungen gegenüber v2 nach den Entscheidungen D1–D7 in [[Entscheidungen_vor_B7_2026-10-05]]: Spalte „Typ“ (D1), Zugangsdefinition (D2), Zählfenster (D3), Gleichstandsregel (D4), Blockade nur H3 (D5), Ableitung der I-Zellen über H1 (D6), Kopfzeilen (D7).

## 1 Ausgangszustand t0

**Code (aus der konsolidierten Codierung):** `B / R / Dk / Df / B° / R° / gespalten / nicht entscheidbar`

| Frage (Regelwerk v3.1) | Antwort | Begründung | Beleg (Datum) |
|---|---|---|---|
| 1 Mehrheit | | | |
| 2 Sperrtatbestand (Verwundbarkeit) | | | |
| 3 Absicherung | | | |
| 4 Ebenen (nur I/P) | | | |
| 5 Doppelperformanz | | | |
| 6 beide / eine / keine / unklar | | | |

*Hinweis:* Leere Antworten sind keine Lücke, wenn die Ergebnisreihenfolge die Frage nicht erreicht (keine Mehrheit → Frage 2/3 entfallen; Mehrheit eines Pols mit Ergebnis B/R → Frage 6 entfällt).

## 2 Mechanismeneinsatz (bis 30.06.2022)

*Zählfenster (D3):* Für die Ableitung zählen Einträge vom 01.03.2021 bis 30.06.2022. Frühere Einträge stehen unter „Bestand/Vorlauf“ und zählen nur, soweit sie zu t0 fortbestehen (z. B. geltende Verträge).

| Datum | Träger | Pol | Instrument | Typ (D1: Sozialisierung / Anreiz / Zwang) | verbindlich? (3.2.7 b: Konditionalität mit Statusfolgen, Vertrag, Finanzierungszusage, Sicherheitsleistung, Zwangsmaßnahme; Rhetorik nein) | Adressat im Zielstaat | Beleg |
|---|---|---|---|---|---|---|---|
| | | B/R | | Vortrag: … · bestätigt (Levi): … | ja/nein | | |

*Typ (D1, präzisiert D1a 05.10.2026):* Sozialisierung = Dialog, Kontakt, Bericht, Erklärung, Ausbildung, Normvermittlung ohne Vorteil oder Nachteil; Anreiz = Gewährung oder Zusage eines Vorteils (Geld, Preis, Liefermenge, Status, Marktzugang, Sicherheitsleistung), auch ohne ausdrücklich genannte Gegenleistung – ist eine Bedingung belegt: „Anreiz (Konditionalität)“; Zwang = Androhung oder Verhängung eines Nachteils (Lieferstopp, Preisanhebung, Mengenkürzung, Sperre, Sanktion); unklar = nur, wenn unklar ist, was der Akt war (z. B. Ankündigung ohne belegten Inhalt). Bestandsmaße (z. B. SIPRI-Fenster) erhalten keinen Typ: „Bestand (kein Mittel)“. Die Paket-Session trägt den Typ vor, Levi bestätigt oder ändert in B6b.

## 3 Zugang

*Definition (D2):* Zugang = belegter direkter Kontakt (Kontaktreihe, ohne group_only/date_uncertain) **oder** ein im Register dokumentierter Akt des Trägers gegenüber einem benannten Entscheider. „Indirekt“ (Akt gegenüber Regierung allgemein, Konferenzformat, Parteiendialog) zählt nicht als Zugang, wird aber vermerkt.

| Träger | Entscheider (Rollen-/Trägerregister) | Zugang | Beleg (Kontakt-ID, Format) |
|---|---|---|---|
| | | dokumentiert / nicht belegt (Vermerk: indirekt) | |

*Asymmetrieregel:* Kontakte nur als positiver Zugangsbeleg; fehlt ein Beleg: „nicht belegt“, nie „kein Zugang“.

## 4 Moderatoren zu t0 (Jahreswerte 2021, Vorlauf 2019/2020)

| Moderator | zu B | zu R | Indikator / Beleg |
|---|---|---|---|
| Linkage (Rohwert und Stufe, symmetrische Schwellen) | | | |
| Verwundbarkeit (qualitativ, Logik von Frage 2) | | | |
| Staatskapazität (territorial / fiskalisch) | | – | |

Werte und Begründungen: Moderatoren_t0_v2_2026-10-05 (WGI nur Robustheit, mit 90-%-Intervall; B1a). In der Ableitung werden Rohwerte bzw. qualitative Begründungen verglichen, nicht Stufen.

## 5 Dimensionale Bedingung

- **H1** Trägerveränderung bis Stichtag: Ersetzung / Konversion / keine — Beleg: (Ersetzung = Wechsel von Regierungschef oder führender Regierungspartei; Konversion = gleiche Träger, belegter Wechsel der Selbstbeschreibung; B3)
- **H2** Ersatzbeziehung zugänglich (Verbindung, Marktzugang, Anbieter): ja / nein — Beleg:
- **H3** Blockadepotenzial zu t0 (Hindernis = alle zu t0 verankerten militärischen Bindungen oder Truppenpräsenzen, die einem Pol Entscheidungen in diesem Bereich verwehren): territorial / verankerte Bindung / Veto / keines — Beleg:
  - Berührende Entscheidungskategorien: siehe `30_Erwartungsprotokoll/H3_Kategorien_fixiert.md`
- **H4** Ausgangsbedingung Brüsseler Kette: ja / nein · Moskauer Kette: ja / nein — Beleg:

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

**Erwartete Richtung:** B / R / Fortbestand (nur I) / unbestimmt (= nicht entscheidbar)
**Erwartete Blockade:** ja / nein / entfällt
**Konfidenz:** hoch / mittel / niedrig
**Begründung (2–4 Sätze):**

## 7 Offenlegung

- Bekannt beim Ausfüllen: (u. a. Kenntnis der vorzeitigen Regelprüfung vom 05.10.2026, falls gesehen; D8)
- Eingaben erhoben von:
- Ableitung durch:
