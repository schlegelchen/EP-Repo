---
titel: "Regelprüfung der Ableitung (Abschnitt 6) in den Erwartungsprotokollen EP_*"
typ: pruefung
datum: 2026-10-05
status: entwurf
tags: [erwartungsprotokoll, regelpruefung, kapitel-3]
bezug: "[[Arbeitsvorlage_Erwartungsprotokoll_und_Kapitelangleichung_5-8_2026-09-29]] Teil C, Abschnitt 6 · [[Entscheidungsprotokoll_2026-10-04]] B13, A10 · EP_ARM-I … EP_SRB-P"
---

# Regelprüfung der Ableitung (Abschnitt 6)

## 1 Befund in einem Satz

**In keinem der zehn Bögen ist eine Erwartung eingetragen:** Abschnitt 6 enthält überall nur die Platzhalter („B / R / unbestimmt“, „ja / nein“, „hoch / mittel / niedrig“), Abschnitt 7 ist leer. Eine Übereinstimmung „eingetragen ↔ nach Regel“ ist daher bei allen zehn Zellen **nicht prüfbar**. Die Spalte „nach Regel folgende Erwartung“ ist deshalb die Ableitung, die der Bogen aus seinen Abschnitten 2–5 zuließe; sie ist **kein eingetragener Wert** und kein Code B/R/Dk/Df.

## 2 Geprüfte Grundlage

- Regel: Arbeitsvorlage Teil C, Abschnitt 6 (Schritte 1–4).
- Auslegung „verbindlich“: Entscheidungsprotokoll B13 (Stand 05.10.): nach Kapitel 3.2.7 b (weit), nicht nach A10 (eng); „unbestimmt“ = nicht entscheidbar (A5). Alle zehn Bögen nennen im Kopf von Abschnitt 2 die Auslegung 3.2.7 b weit; kein Bogen wendet A10 an.
- Bögen: `30_Erwartungsprotokoll/EP_*.md` (10 Dateien; `H3_Kategorien_fixiert.md` nicht geprüft, da kein EP-Bogen). Hinweis: Der Ordner heißt im Vault `30_Erwartungsprotokoll` (mit Unterstrich).
- Kein Wissen über die Fälle außerhalb der Bögen verwendet.

## 3 Ergebnis je Zelle

Lesehilfe „Blockade“: Regel 4 knüpft die Blockade an eine Bedingung aus Abschnitt 5, die „als Hindernis fortbesteht“, und führt nur für H3 eine Folge aus. Für H1 (alle I-Zellen) und H4 (alle P-Zellen) legt die gelesene Regel nicht fest, was als Hindernis gilt; die Blockade ist daher in allen zehn Zellen **nicht aus der Regel ableitbar** (*Auslegung zu prüfen*).

| Zelle | eingetragene Erwartung | nach Regel folgende Erwartung | übereinstimmend (ja/nein) | Begründung (ein Satz) |
|---|---|---|---|---|
| ARM-I | keine (Abschnitt 6 leer) | Richtung: unbestimmt (nicht entscheidbar) · Blockade: nicht ableitbar | nicht prüfbar | Abschnitt 2 enthält nur eine nicht verbindliche Erklärung Russlands (2022-04-19) und keinen B-Eintrag, also Schritt 3; das Ergebnis beruht auf dem nicht erhobenen Instrumentenregister I, nicht auf einem Gegenbefund. |
| ARM-P | keine | Richtung: R, **bedingt** (sonst unbestimmt) · Blockade: nicht ableitbar | nicht prüfbar | Beide Pole haben verbindliche Mittel mit dokumentiertem Zugang (B: CEPA 2021-03-01; R: Friedenskontingent, FSB-Stationierung, Waffenruhe 2021-11-16), in Schritt 2 scheitert B an Linkage B 19 % < R 29 %, und R erfüllt die Verwundbarkeitsbedingung (hoch gegenüber R, niedrig gegenüber B) nur, wenn die russischen Sicherheitsleistungen als Zwang oder Anreiz gelten, was der Bogen nicht festlegt. |
| BIH-I | keine | Richtung: unbestimmt (nicht entscheidbar) · Blockade: nicht ableitbar | nicht prüfbar | Abschnitt 2 ist leer („nicht belegt (nicht erhoben)“), also Schritt 3; das Ergebnis folgt aus fehlender Erhebung. |
| BIH-P | keine | Richtung: B, **mit Vorbehalt** · Blockade: nicht ableitbar | nicht prüfbar | B hat mehrere verbindliche Mittel mit dokumentiertem Zugang (Stellungnahme 2019-05-29, MFA 2021-10-08, EPF und Sanktionsrahmen 03/2022), bei R sind die möglichen verbindlichen Mittel (P-BIH-27, -31) im Bogen „zu prüfen“, sodass Schritt 1 gilt, und selbst bei Schritt 2 erfüllt R die Verwundbarkeitsbedingung nicht (Verwundbarkeit gegenüber R niedrig). |
| GEO-I | keine | Richtung: unbestimmt (nicht entscheidbar) · Blockade: nicht ableitbar | nicht prüfbar | Abschnitt 2 ist leer („nicht belegt (nicht erhoben)“), also Schritt 3. |
| GEO-P | keine | Richtung: B, **mit Vorbehalt** · Blockade: nicht ableitbar | nicht prüfbar | B hat verbindliche Mittel mit dokumentiertem Zugang (MFA 2020-11-25 und 2021-08-31, EPF), bei R ist der Zugang zu georgischen Entscheidern „nicht belegt“ (Adressaten der Finanzzusagen sind De-facto-Führungen), sodass Schritt 1 B ergibt, was bei einer Lesart „nicht belegt = Zugang vorhanden“ über Schritt 2 nur dann B bliebe, wenn die Brüsseler Mittel als Sozialisierung oder Überzeugung gelten. |
| MDA-I | keine | Richtung: unbestimmt (nicht entscheidbar) · Blockade: nicht ableitbar | nicht prüfbar | Abschnitt 2 ist leer; die im Bogen genannten P-MDA-V2 und P-MDA-04 sind ausdrücklich nicht aufgenommen, also Schritt 3. |
| MDA-P | keine | Richtung: B oder unbestimmt, **nicht eindeutig** · Blockade: nicht ableitbar | nicht prüfbar | Beide Pole haben verbindliche Mittel (B: MFA, Frontex, Statusbeschlüsse; R: Kreditabkommen 2020-04 und Gasvertrag 2021-10-29, beide im Bogen unsicher bzw. mit Zugang nur über den Vorlauf oder „indirekt“), und in Schritt 2 steht Linkage B 55 % > R 11 % einer Verwundbarkeit gegenüber, die beide Seiten als „hoch“ ausweist, ohne dass der Bogen R > B belegt. |
| SRB-I | keine | Richtung: unbestimmt (nicht entscheidbar) · Blockade: nicht ableitbar | nicht prüfbar | Abschnitt 2 ist leer; die im Bogen erwähnten P-SRB-01/-02/-03 sind nicht aufgenommen, also Schritt 3. |
| SRB-P | keine | Richtung: B oder unbestimmt, **nicht eindeutig** · Blockade: nicht ableitbar | nicht prüfbar | Beide Pole haben verbindliche Mittel mit Zugang (B: Beitrittskonferenzen, Konditionalität 2021-05-11 und 2021-12-14; R: EAWU-Freihandel 2021-07-10, RZD-Vertrag 2019), Linkage B 61 % > R 6 % spricht für B, die Verwundbarkeit ist aber für beide „hoch“ und R > B im Bogen nicht ausgewiesen, sodass B nur gilt, wenn die Brüsseler Mittel als Sozialisierung oder Überzeugung zählen und die Moskauer Bedingung nicht erfüllt ist. |

**Zählung:** 0 von 10 prüfbar · 5 I-Zellen: Richtung nach Regel formal „unbestimmt“ (Schritt 3, wegen leerem Abschnitt 2) · P-Zellen: ARM-P R (bedingt), BIH-P B, GEO-P B (beide mit Vorbehalt), MDA-P und SRB-P nicht eindeutig.

## 4 Strukturelle Befunde zur Regel (Ursachen der Vorbehalte)

1. **Mechanismustyp fehlt in Abschnitt 2.** Schritt 2 verlangt „Sozialisierung oder Überzeugung“ (B) bzw. „Zwang oder Anreiz“ (R). Die Tabellenspalten führen Instrument und „verbindlich?“, aber keinen Mechanismustyp; die Zuordnung ist weder im Bogen noch in der gelesenen Regel festgelegt. Ohne sie ist Schritt 2 in ARM-P, MDA-P, SRB-P (und im Gegenfall BIH-P, GEO-P) nicht abschließend anwendbar.
2. **Vergleichsmaßstab Verwundbarkeit.** Die Regel vergleicht „Verwundbarkeit gegenüber R > gegenüber B“; in MDA und SRB steht beidseitig „hoch“ mit unterschiedlichen Indikatoren (Export-/Energieanteile), ein Vergleich R > B ist aus den Bögen ohne eigene Gewichtung nicht ablesbar.
3. **Reichweite von „Zugang“.** Die Regel sagt „mit Zugang“, nicht ob „indirekt“ genügt und wie „nicht belegt“ zu behandeln ist (Asymmetrieregel: nicht belegt ≠ kein Zugang). Das entscheidet insbesondere GEO-P (R) und MDA-P (R).
4. **Blockade bei H1 und H4** ist in Schritt 4 nicht definiert (nur H3).
5. **Leeres Instrumentenregister I.** In allen fünf I-Zellen liefert Schritt 3 „unbestimmt“ allein aus fehlender Erhebung. Nach A5 gilt „nicht entscheidbar“ nur, wenn eine ergebnisentscheidende Frage „unklar“ ist und beide Ausgänge möglich sind; ob die Erhebungslücke dafür genügt, ist nicht geregelt.
6. **Zeitbezug der Instrumente.** Die Tabellen enthalten Instrumente ab 2019 (Vorlauf) bis 30.06.2022; die Regel nennt kein Fenster. Insbesondere MDA-P (R: Kredit 2020-04, Zugang über Dodon, Präsident bis 2020-12-24) hängt davon ab, ob Vorlaufinstrumente zählen.

## 5 Offene Punkte und Unsicherheiten

- **Hauptpunkt:** Abschnitt 6 und 7 sind in allen zehn Bögen nicht ausgefüllt (laut Kopf: „Eingabepaket Abschnitte 1–5“); die Prüfung „eingetragen ↔ Regel“ kann erst nach dem Eintrag durchgeführt werden. Die Tabelle oben ersetzt ihn nicht.
- Frontmatter aller Bögen: `erstellt_von: Claude (Cowork)`, `blindheitsstufe: 3`; B12 sieht vor, dass Levi die Bögen selbst ausfüllt (Stufe 3). Ob die Stufe nach Ableitung durch Claude fortgilt, ist **zu prüfen**.
- Die rule-basierten Spalteneinträge setzen voraus, dass die „zu prüfen“-Markierungen der Bögen (z. B. P-BIH-27, -31; P-MDA-07; P-SRB-27, -36; P-GEO-29, -47) offen bleiben; wird eines davon als verbindlich eingestuft, kann sich Schritt 1 zu Schritt 2 ändern (v. a. BIH-P, GEO-P).
- Nicht geprüft: Richtigkeit der Einträge in Abschnitt 1–5 (Belege, Daten, Moderatorenwerte), Kapitel 3.2.7 b im Wortlaut (nicht gelesen) und die Erwähnung „Moderatoren_t0_v2“; nur die Folgerichtigkeit der Regelanwendung auf die vorhandenen Einträge.
- Keine Dateien in `70_Schreiben` verändert; keine Codes B/R/Dk/Df abgeleitet (Richtungsangaben B/R/unbestimmt beziehen sich ausschließlich auf die Erwartung nach Abschnitt 6).
