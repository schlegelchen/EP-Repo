---
titel: "Gegenprüfung der t0-Codes gegen Regelwerk v3.2"
typ: pruefprotokoll
datum: 2026-10-06
pruefer: Claude (Cowork)
status: abgeschlossen – Klarstellung GEO-E von Levi bestätigt (06.10.2026)
bezug: "[[Regelwerk_Codierung_v3.2_2026-10-06]] · [[Codes_t0_konsolidiert_2026-10-05]] · [[Entscheidungen_vor_B7_2026-10-05]] (C4)"
tags: [codierung, regelwerk, t0, gegenpruefung, nachtrag-nach-fixierung]
---

# Gegenprüfung der t0-Codes gegen Regelwerk v3.2

> [!info] Zweck und Status
> Nach C4 sollen die t0-Codes unter v3.2 unverändert bleiben. Geprüft wurden alle 20 Zeilen von `Codes_t0_konsolidiert_2026-10-05.csv` gegen die Änderungen von v3.2. Die Prüfung erfolgt nach der Fixierung (Commit `a291e96`) und wird als offen ausgewiesener Nachtrag eingecheckt. Grundlage sind nur die Antworten und Begründungen der CSV, keine Dossiers.

## Ergebnis

**Alle 20 t0-Codes bleiben unverändert.** Eine Zeile (GEO-E) hängt an einer Auslegung der neuen Definition „substanzielle Bindung“, die zu klären ist (unten).

| Änderung v3.2 | Betroffene Zeilen | Befund |
|---|---|---|
| (1) Frage 1, widersprüchliche Indikatoren | ARM-I, ARM-E, GEO-E, SRB-I, SRB-M („keine klar“) | Jede Zeile benennt Indikatoren und begründet, warum kein Pol überwiegt; ARM-E zusätzlich mit Kippzeile. Unverändert. |
| (2) Frage 2, Teilerhebung | keine | Keine Zeile hat Frage 2 = „unklar“; die „nein“-Antworten beruhen auf erhobenen Kernbereichen. Unverändert. |
| (3) Frage 6, substanzielle Bindung | alle Dk-Zeilen mit Frage 6 = „zu beiden“ | ARM-I (CEPA; Allianz mit Russland), ARM-E (CEPA; EAWU), SRB-I (Kandidatenstatus; strategische Partnerschaft), SRB-M (Militärkooperationsabkommen 2013, Rüstungsbezug; MTA/KFOR, PfP/IPAP), SRB-P (Beitrittsrahmen; EAWU-Freihandel), GEO-P (Einbindung abtrünniger Gebiete), MDA-P (GUS): Gegenbindung jeweils substanziell. Nicht substanzielle Angaben in den Begründungen (OVKS-Beobachter, Kontaktkanal Putin–Vučić) tragen das Ergebnis nicht allein. **GEO-E: siehe Klarstellung.** |
| (4) Ergebnisregel 7, B°/R° bei Frage 2 = unklar | keine | Keine B°/R°-Codes. |
| (8) Klarstellung Frage 2 = ja → Dk | GEO-M, MDA-E, MDA-M, SRB-E, BIH-P | Alle fünf haben bereits Frage 6 = „zu beiden“ und Code Dk. Unverändert. |
| D12 Türkei im Militär | ARM-M, GEO-M, SRB-M, BIH-M | Kein Rüstungsbezug aus der Türkei im SIPRI-Fenster 2019–2021, der eine Antwort ändern würde (ARM 81,1 % RUS/BLR; GEO und BIH 100 % EU/USA; SRB 94 % RUS/BLR). Unverändert. |
| D11 t1, Bezugsdatum, Fenster | – | betrifft t0 nicht |

## Klarstellung zur Entscheidung (Levi)

**GEO-E (Dk):** Frage 1 = „keine klar“, Frage 6 = „zu beiden“. Die russische Gegenbindung beruht laut Begründung auf der **Mehrheitsbeteiligung von Inter RAO an Telasi (75 %)** und auf Überweisungen (17,5 %). Die Aufzählung in v3.2 (Frage 6) nennt Mehrheitsbeteiligungen nicht ausdrücklich; Überweisungen sind keine Bindung im Sinne der Definition.

- **Vorschlag:** Die Aufzählung „substanziell“ wird ausgelegt als nicht abschließend; eine **Mehrheitsbeteiligung eines Pols an einem Netzbetreiber oder am größten Unternehmen eines Kernsektors** zählt als substanzielle Bindung. Das entspricht der Logik von Frage 1 (Wirtschaft), die genau diese Beteiligung als gewichtiges Kriterium behandelt. Damit bleibt GEO-E = Dk.
- **Alternative:** strenge Lesart; dann wäre die russische Seite bei GEO-E nicht substanziell. Weil Frage 1 = „keine klar“ ist, sieht die Ergebnisregel dafür kein „nur zur Seite aus Frage 1“ vor; das Ergebnis wäre unklar geregelt (eher Df oder nicht entscheidbar). Das spricht für den Vorschlag.
- Nach C4 gilt eine solche Klarstellung für t0 und t1 und beide Codierer und wird als offene Abweichung nach der Fixierung protokolliert.

## Entscheidung Levi (06.10.2026)

**Bestätigt:** Eine Mehrheitsbeteiligung eines Pols an einem Netzbetreiber oder am größten Unternehmen eines Kernsektors zählt als substanzielle Bindung (Frage 6, v3.2); die Aufzählung in v3.2 ist nicht abschließend. Offen ausgewiesene Klarstellung nach der Fixierung (C4); gilt für t0 und t1 und beide Codierer. **GEO-E bleibt Dk.**

Prüfung der Relevanz von Telasi (Claude, vorläufig): Inter RAO (russisch, staatlich kontrolliert) hält 75 % am Stromverteiler der Hauptstadt (Telasi); dazu Khrami I/II (Inter-RAO-Gruppe) und eine 50-%-Beteiligung einer russischen Netzgesellschaft an Sakrusenergo (Träger *zu prüfen*). Zu t0 bestand mit Schiedsverfahren (Teilschiedssprüche 19.04.2021 und 23.11.2021, Inhalt nicht gelesen) ein aktives Rechtsverhältnis mit dem georgischen Staat. Als **Bindung** (Frage 6) relevant; als **Verwundbarkeit** (Frage 2) nicht, da der Verteilnetzbetrieb reguliert ist und russischer Strom 2021 nur 1,8 % des Verbrauchs deckte. Kundenzahl und Anteil von Telasi am Landesverbrauch: *zu prüfen* (GNERC-Jahresbericht). Überweisungen (17,5 %) tragen das Ergebnis nicht.
