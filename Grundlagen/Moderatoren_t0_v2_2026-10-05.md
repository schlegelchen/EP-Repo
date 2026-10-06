---
titel: "Moderatoren zu t0, Fassung 2 (symmetrische Linkage, qualitative Verwundbarkeit, Staatskapazität nach V-Dem)"
typ: register
datum: 2026-10-05
status: entwurf – für EP1/B6b
tags: [erwartungsprotokoll, moderatoren, linkage, verwundbarkeit, staatskapazitaet, b6a]
bezug: "[[Moderatoren_t0_2026-09-29]] (Fassung 1, §4 ersetzt) · [[Entscheidungen_vor_B7_2026-10-05]] (B1, B2) · Kapitel 3.2.4, 3.2.7 b und e"
---

# Moderatoren zu t0, Fassung 2

Ersetzt den Schwellenvorschlag in [[Moderatoren_t0_2026-09-29]] §4 nach Levis Entscheidungen vom 05.10.2026 (B1, B2). Rohwerte für Linkage stammen aus Fassung 1 (Mittel aus Import- und Exportanteil 2019–2021). In der Ableitung (Abschnitt 6) werden **Rohwerte bzw. die qualitative Begründung** verglichen; die Stufen dienen nur der Darstellung.

## 1 Linkage (symmetrische Schwellen für beide Pole)

Stufen: hoch ≥ 50 %, mittel 25–50 %, niedrig < 25 %. Proxy: Anteil am Außenhandel (Mittel Import/Export 2019–2021). *Grenze:* Handelsanteile erfassen Personen-, Finanz- und Bildungsbindungen nicht (Kapitel 3.2.4 nennt sie).

| Fall | Linkage B (Rohwert) | Stufe | Linkage R (Rohwert) | Stufe | Vergleich B vs. R |
|---|---|---|---|---|---|
| ARM | 19 % | niedrig | 29 % | mittel | R > B |
| GEO | 22 % | niedrig | 12 % | niedrig | B > R |
| MDA | 55 % | hoch | 11 % | niedrig | B > R |
| SRB | 61 % | hoch | 6 % | niedrig | B > R |
| BIH | 66 % | hoch | 2 % | niedrig | B > R |

*Zur Frage, ob sich asymmetrische Schwellen begründen ließen:* Möglich wäre es nur über ein Intensitätsmaß, das den Anteil am Gewicht des Partners in der Weltwirtschaft misst (Handelsintensitätsindex); dann wäre ein Russlandanteil von 25 % tatsächlich „dicht“. Das wäre ein eigenes, begründungspflichtiges Maß. Hier gelten symmetrische Schwellen; ein Intensitätsmaß kann als Robustheitsprüfung nachgereicht werden.

## 2 Verwundbarkeit (qualitativ, nach der Logik von Frage 2 / Kapitel 3.2.7 e)

Verwundbar ist ein Staat gegenüber einem Pol, wenn er Störungen durch diesen Pol mangels zugänglicher, gleichwertiger Alternativen auch nach einer Anpassung seiner Politik ausgesetzt bleibt. Ein hoher Anteil an einem Energieträger, der nur einen kleinen Teil der Energieversorgung ausmacht, begründet keine Verwundbarkeit (Entscheidung 03.10., Nr. 2).

| Fall | gegenüber R | Begründung (Dossierstand) | gegenüber B | Begründung |
|---|---|---|---|---|
| ARM | **hoch** | Gas zu rund 88 % aus Russland, Gasnetz zu 100 % Gazprom Armenia; gleichwertige Alternative zu t0 nicht belegt | niedrig | EU-Anteil am Export rund 20 % |
| GEO | **niedrig** | Gas überwiegend über Aserbaidschan; russischer Anteil gering (GNERC, Eintrittsroute); russisches Eigentum am Tbilisser Verteilnetz (Telasi) ist Investition, keine Versorgungsabhängigkeit | niedrig | EU-Anteil am Export rund 20 % |
| MDA | **hoch** | Strom zu rund 74 % aus Cuciurgan (Inter RAO); Importe aus der Ukraine 2021 nur 4,5 % (Eurostat, Nachtrag ins Dossier ausstehend); beim Gas Alternative Iași–Ungheni vorhanden | hoch | EU-Anteil am Export rund 64 %, DCFTA, Makrofinanzhilfe |
| SRB | **hoch** | Gas zu 100 % aus Russland; Verbindung Bulgarien–Serbien im Bau, nicht gleichwertig (Entscheidung 03.10., Nr. 3); LNG nicht belegt; Gas 14,7 % der Energie, ≈ 35 % davon in Strom/Fernwärme (Eurostat 2021, siehe Nachtrag SRB-E) | hoch | EU-Anteil am Export rund 65 % |
| BIH | **niedrig** | Gas zu 100 % russisch, aber 2,8 % der Energie; Strom und Ölprodukte überwiegend aus der EU | hoch | EU-Anteil am Export rund 72 % |

*Hinweis:* Für die Brüsseler Seite ist „Verwundbarkeit“ vor allem Absatz- und Finanzierungsabhängigkeit; die Bewertung „hoch“ beruht auf dem Exportanteil ohne gesonderte Prüfung alternativer Absatzmärkte (*zu prüfen*).

## 3 Staatskapazität (V-Dem v16, 2021)

Zwei Komponenten nach dem Verständnis begrenzter Staatlichkeit (territoriale und sachliche Reichweite staatlicher Regelsetzung und -durchsetzung):

- **Territorial:** `v2svstterr` – Anteil des Staatsgebiets unter staatlicher Kontrolle (%). Stufen: hoch ≥ 95, mittel 85–95, niedrig < 85.
- **Fiskalisch/administrativ:** `v2stfisccap` – Fähigkeit, Steuern zu erheben (latente Skala; Vergleich: Schweden 3,1, Finnland 2,8, Belarus 0,8). Ohne feste Stufen; Rohwert berichten.

| Fall | territorial 2021 | Stufe | fiskalisch 2021 | bisheriger Proxy `v2x_rule` 2021 (nur zum Vergleich) |
|---|---|---|---|---|
| ARM | 96,4 % | hoch | 1,60 | 0,718 |
| GEO | 80,9 % | niedrig | 0,93 | 0,751 |
| MDA | 76,7 % | niedrig | 0,72 | 0,765 |
| SRB | 92,9 % | mittel | 1,83 | 0,483 |
| BIH | 88,3 % | mittel | 1,09 | 0,387 |

Der Wechsel zeigt, warum der alte Proxy ungeeignet war: Georgien und Moldau erschienen über Rechtsstaatlichkeit als „hoch“, obwohl sie wegen der abtrünnigen Gebiete die geringste territoriale Kontrolle haben.

**Robustheitsprüfung (optional):** World Governance Indicators, Government Effectiveness 2021 (Weltbank), wie in der Literatur zu begrenzter Staatlichkeit üblich. *Dass Börzel und Risse WGI verwenden, ist mein Kenntnisstand und vor dem Zitat zu prüfen.* Nachtrag über den Prompt in [[Recherche_und_Nachtragsprompts_B7_2026-10-05]].

Quelle Staatskapazität: `vdem_v16.RData` (Datenablage P_Inventar_2026-09-21), eigene Auswertung, nicht zweitgeprüft.


**Nachtrag 05.10.2026 (Verwundbarkeit SRB):** Die Einstufung „hoch“ ist durch die Eurostat-Gasbilanz 2021 gestützt (Bruttoverfügbarkeit 2.394,5 ktoe; Eigenförderung ≈ 12 %, Importe ≈ 79 %; ≈ 35,5 % in Strom- und Wärmeerzeugung, ≈ 20 % Industrie, ≈ 12 % Haushalte). Details und Vorbehalte: [[Zelldossiers_2026-10-01/SRB-E]], Abschnitt „Nachtrag Gasbilanz SRB 2021“.

**Nachtrag 05.10.2026 (Robustheit Staatskapazität, N6):** WGI Government Effectiveness 2021 (Estimate) liegt vor, siehe [[WGI_Government_Effectiveness_2026-10-05]]: GEO 0,339 · SRB 0,085 · MDA −0,177 · ARM −0,346 · BIH −0,806. Die Rangfolge weicht deutlich von V-Dem ab (territorial: ARM > SRB > BIH > GEO > MDA; fiskalisch: SRB > ARM > BIH > GEO > MDA). Vermutlich messen die Indizes Verschiedenes (WGI: Qualität von Verwaltung und öffentlichen Leistungen; v2svstterr: territoriale Kontrolle) – *Deutung vorläufig, nicht entschieden*. **Entschieden (Levi, 05.10.2026, B1a):** V-Dem bleibt Hauptmaß; WGI wird als Robustheitsprüfung mit Intervallen und Hinweis auf die Überlappung berichtet. Geklärt am Originalexport: Der „0–100 Score“ ist ein absoluter Score (2025 Revision), kein Perzentilrang. Die 90-%-Intervalle der Fallländer überlappen 2021 weitgehend (GEO 50,8–67,8; SRB 46,0–62,1; MDA 41,2–56,2; ARM 37,4–53,1; BIH 27,5–44,2); trennscharf ist nur BIH gegenüber GEO. Die WGI-Rangfolge ist also unsicher und widerlegt die V-Dem-Einstufung nicht.

**Nachtrag 06.10.2026 (SRB, Interkonnektor Ungarn):** Horgoš–Kiskundorozsma ist seit 01.10.2021 in Richtung Serbien → Ungarn in Betrieb; Ungarn → Serbien nur unterbrechbare kommerzielle Reverse-Kapazität; Bezug nicht-russischen Gases bis t0 nicht belegt. Einstufung „hoch“ bleibt. Details: [[Zelldossiers_2026-10-01/SRB-E]], Abschnitt „Nachtrag Interkonnektor Ungarn“.
