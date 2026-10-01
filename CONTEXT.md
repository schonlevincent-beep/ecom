# Azaléa – Kontext aus dem Cowork-Task „ad performance analysis“

*Übernommen am 01.10.2026 · Task lief vom 17.07. bis 29.09.2026 · Quelle: Google Drive „Cowork task ad performance analysis 2026-10-01“*

Azaléa ist eine DTC-Hautpflege-Brand (DE + CH, Shopify, Meta Ads) mit zwei Geschäftsführern. Hauptprodukt im Ad-Fokus ist das **Silikon-Narbenpflaster (Rolle)**. Daneben gibt es die Anti-Pickel-Patch-Rolle (Hydrokolloid) und Retinal Peptide. Alle Analysen, Prompts und Konzepte liegen in `outputs/`.

## Wirtschaftliche Eckdaten

| | Wert | Quelle |
| :-- | --: | :-- |
| Warenkosten Narbenpflaster | 2,20 € | Deckungsbeitrag_Breakeven |
| Warenkosten Anti-Pickel-Rolle | 4,31 € | Deckungsbeitrag_Breakeven |
| Versand DE (eigener Versand) / CH (Dropshipping) | 3,67 € / 8,36 € | Deckungsbeitrag_Breakeven |
| Zahlungsgebühren (Mischwert) | 3,25 % | Deckungsbeitrag_Breakeven |
| Deckungsbeitrag-Marge (altes Angebot) | ~73 % | Deckungsbeitrag_Breakeven |
| **Aktuelles Angebot** | **2+1 gratis zu 59,90 €** (vorher 47,90 €) | Neue_Kampagnenstruktur (18.08.) |
| **Break-even-CPA / ROAS (neues Angebot)** | **~46 € / 1,26** | Neue_Kampagnenstruktur |
| Rabattcode | **Narbe15** (15 %) | Prompts_MostAware_Narbenpflaster |

## Zeitlicher Verlauf der Erkenntnisse

1. **29.07. – Meta_Ads_Analyse_Azalea:** ROAS ~0,10. Der Checkout war das größte Leck (28 % Abschluss). Native-Ads brachten 0 Warenkörbe.
2. **03.08. – Checkup / Deckungsbeitrag / Tagesanalyse:** Das Tracking stimmt jetzt. Break-even-CPA lag beim alten Angebot bei 27 €. Die Rabattquote war mit 34,6 % deutlich höher als die 15 % von Narbe15.
3. **06.08. – Testphase_Auswertung_11_Tage:** Beweis- und Review-Creatives (AD 5, 7, 11) schlagen die Mechanismus-Creatives. Die Anzeigengruppe MostAware ist besser als Cold. Videos funktionieren nicht.
4. **09.–12.08. – Tagesanalyse / Analyse_3_Tage:** „Variation 1“ (Kampagne CBO TEST 2) ist der Gewinner (CPA ~46 €). Die AI/Native-Kampagne hat insgesamt 620 € für 0 Warenkörbe ausgegeben, Empfehlung: abschalten. AD 5 ist ausgebrannt.
5. **18.08. – Grundanalyse_August_1_18 + Gegenpruefung_und_Skalierungsplan:**
   - Zahlen 01.–18.08.: 4.888 € Ausgaben, 69 Bestellungen, blended ROAS 0,485, CPA 87 €.
   - Ursachen: 13 Anzeigengruppen, von denen keine die Lernphase verlässt. 30 % des Budgets gingen in Placements ohne Ertrag (v. a. IG Stories). Die schlechteste Anzeigengruppe (Image Broad Cold) bekam das meiste Budget.
   - Die Creatives selbst sind ok (CTR 3,1 %, CPC 0,70 €). Das Problem liegt hinter dem Klick.
   - Ziel 50k €/Monat: Das geht erst, wenn die Stückrechnung profitabel ist.
6. **18.08. – Neue_Kampagnenstruktur_Umsetzungsplan (letzter Strukturstand):**
   - Prospecting über ABO, 1 Anzeigengruppe mit 300 €/Tag: Broad, DE+CH, Frauen 18–65, Advantage+ Audience aus, Placements manuell. Dazu Retargeting mit 50 €/Tag.
   - Creatives in Cold: „2+1Gratis“, AD 11 „Reviews2“, „30TAGE Geld zurück“, „Kaiserschnitt Variante 1“.
   - Testregel: mindestens 130 € Spend pro Anzeige, Abbruch ohne Warenkorb, maximal 4 Anzeigen gleichzeitig, Checkpoint nach 4 Tagen.
   - Skalierung: Budget um maximal 20 % alle 48–72 h erhöhen, sobald der ROAS über 1,26 liegt.
7. **Bis 29.09. – Creative-Arbeit:** Prompts für Retargeting-Creatives, Knightvision-Static-Ads und Produktbilder im Lefaya-Stil (siehe unten, was davon fehlt).

## Offene Hebel aus den Analysen (Stand August)

- Warenkorbwert über 50 € halten (Bundle als Standardauswahl).
- Checkout-Abschluss auf mindestens 65 % bringen.
- Mails für abgebrochene Checkouts einrichten.
- Native-Ads nur mit einer Advertorial-Zwischenseite wieder starten (`Prompt_Advertorial_LP_Hautjournal.md`).
- Echte 9:16-Assets für Stories bauen.

## Compliance-Regeln (gelten für alle Creatives)

- Nie „heilt“, „verschwindet“ oder „wirkt bei jedem“ schreiben. Stattdessen: „verbessert“, „unterstützt“, „bei mir“.
- Narbenpflaster: kein Wort zu Falten oder Anti-Aging.
- „Goldstandard“ ist über den PubMed-Konsens (24 Dermatologen) belegt. Die Quelle muss auf der Seite auffindbar sein.
- Keine erfundenen Namen oder Bewertungen unter Zitaten.
- Rabattangaben nach § 11 PAngV.

## Nicht übernommen

- `Prompts_Knightvision_StaticAds_Narbenpflaster.md` und `Produktbilder_Azalea_nach_Lefaya-Stil.md` (die letzte Datei vom 29.09.) fehlen im Drive-Upload.
- Die Gesprächsverläufe (`.claude/projects/*.jsonl`) fehlen ebenfalls im Upload.
- Die Bilder (Lefaya-Theratex-Referenzen, Screenshots in `uploads/`) liegen nur in Drive und nicht im Repo.
