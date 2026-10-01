# Gegenprüfung & Skalierungsplan
*Überprüfung meiner Analyse gegen externe Quellen · korrigierte Empfehlungen · Weg zu 50k*
*Stand 18.08.2026*

---

## Teil 1 — Was sich bestätigt hat

### Die 50-Conversions-Regel ist echt und Metas eigene Vorgabe

Meta gibt in Help Center und Produkt-Tooltips **rund 50 Optimierungsereignisse pro Anzeigengruppe und Woche** als Schwelle für stabile Auslieferung an. Zwei Präzisierungen, die für euch wichtig sind:

- Die Schwelle gilt **pro Anzeigengruppe, nicht pro Anzeige.** Fünf Anzeigen in einer Gruppe teilen sich einen Topf von 50.
- Sie ist eine Richtlinie, keine harte Grenze. Konten darunter können laufen — mit **deutlich mehr Streuung**.

Damit ist die Erklärung für eure Tagesschwankungen bestätigt: 1,6 Käufe pro Anzeigengruppe und Woche gegen eine Vorgabe von 50.

### Die Konsolidierungsempfehlung ist Branchenstandard

Die Quellen sind hier ungewöhnlich einheitlich: **1 bis 3 Anzeigengruppen pro Kampagne**, aufteilen nur bei konkretem geschäftlichem Grund. Wörtlich: *„Run fewer ad sets with higher budgets rather than many ad sets starved of spend."* Und: Fragmentierung führt zu **40–60 % höheren CPAs**.

### Es gibt eine konkrete Formel für das Mindestbudget

> **Mindest-Tagesbudget je Anzeigengruppe = Ziel-CPA × 50 ÷ 7**

Für euch: **28 € × 50 ÷ 7 = 200 €/Tag pro Anzeigengruppe.**

Ihr gebt aktuell rund 272 €/Tag über das gesamte Konto aus. **Ihr könnt euch also rechnerisch genau eine Anzeigengruppe leisten, die überhaupt die Chance hat, aus der Lernphase zu kommen.** Nicht 13, nicht drei — eine.

### Der Placement-Unterschied ist statistisch belastbar

Ich habe nachgerechnet: Hätte Instagram Stories wie der Feed performt, wären aus 832 € rund **12,8 Käufe** zu erwarten gewesen. Tatsächlich waren es 4. Die Wahrscheinlichkeit, dass das Zufall ist, liegt bei etwa **0,3 %**. Der Unterschied ist real.

---

## Teil 2 — Wo meine Analyse angreifbar ist

Hier muss ich zurückrudern, und zwar an einer wichtigen Stelle.

### Einschränkung 1: Die Stories-Zahlen sind möglicherweise ein Creative-Problem, kein Platzierungsproblem

Die Quellen weisen auf etwas hin, das ich übersehen habe: Wenn Feed-Creatives (4:5, 1:1) automatisch für Stories (9:16) skaliert werden, **rutscht die Headline unter die Bedienoberfläche und der Call-to-Action landet zu tief**. Die Performance sieht dann nach Platzierungsproblem aus, ist aber ein Format-Problem.

**Und genau das trifft auf euch zu.** Eure laufenden Creatives — AD 3 Mechanismus-Bild, AD 7 Angebots-Ad, die Statics — sind im Feed-Format gebaut. In Stories werden sie beschnitten.

Die Daten stützen beide Lesarten:

| CBO TEST 2 | Kosten je Seitenaufruf | Warenkorbquote |
| :-- | --: | --: |
| Feed | 1,48 € | **10,4 %** |
| Instagram Stories | **1,21 €** | 4,3 % |

Stories liefert Seitenaufrufe **billiger** als der Feed, aber sie konvertieren weniger als halb so gut. Das passt sowohl zu „beschnittenes Creative" als auch zu „Vollbild-Platzierung erzeugt versehentliche Taps".

**Korrigierte Empfehlung:** Nicht „Stories für immer raus", sondern: **Stories deaktivieren, solange ihr keine echten 9:16-Assets habt.** Ihr habt jetzt Prompts für 9:16 — sobald die Creatives fertig sind, ist Stories einen sauberen Neutest wert.

### Einschränkung 2: Metas eigene Daten sprechen gegen manuelle Platzierungen

Meta gibt an, dass Advantage+ Platzierungen **10–30 % bessere Kosten pro Ergebnis** liefern als manuelle Auswahl. Das widerspricht meiner Empfehlung direkt.

Zwei Dinge relativieren das: Der 30-%-Wert bezieht sich auf Budgets unter 1.000 $/Monat — ihr liegt bei rund 8.000 €. Und die Quellen sagen ausdrücklich, dass manuelle Ausschlüsse legitim sind, *„when data clearly supports the decision"*. Bei 0,3 % Zufallswahrscheinlichkeit ist das gegeben.

**Aber:** Wenn ihr Platzierungen einschränkt, verkleinert sich der Auktionspool und **die Feed-CPMs steigen wahrscheinlich**. Meine Rechnung „1.000 € besseres Ergebnis" ging von gleichbleibender Feed-Leistung aus. Realistisch sind eher **600–700 €**.

Und: Bei manueller Auswahl darf Meta trotzdem bis zu **5 % des Budgets** auf abgewählten Flächen ausgeben.

### Einschränkung 3: Cross-Placement-Assists sind nicht messbar

Meta rechnet den Kauf der zuletzt gesehenen Platzierung zu. Wer erst eine Story sieht und dann über den Feed kauft, macht den Feed gut und Stories schlecht — obwohl Stories vorgearbeitet hat. Bei einer Frequenz von 2,87 in eurer besten Anzeigengruppe sehen Leute mehrfach Anzeigen, also gibt es diesen Effekt.

**Wie groß er ist, weiß niemand.** Sauber messen ginge nur mit einem Holdout-Test, den euer Volumen nicht hergibt. Das bleibt ein Restrisiko meiner Empfehlung.

### Einschränkung 4 — die unbequemste: Konsolidierung allein reicht nicht

Ich habe geschrieben, Konsolidierung bringe euch aus der Lernphase. Das stimmt so nicht.

Bei 272 €/Tag und aktueller CPA von 87 € macht ihr **3,1 Käufe pro Tag = 22 pro Woche**. Selbst wenn alles in einer einzigen Anzeigengruppe läuft, liegt ihr bei 22 von 50.

**Um die Lernphase wirklich zu verlassen, müsste die CPA auf rund 38 € fallen** — dann ergeben 272 €/Tag genau 50 Käufe pro Woche.

Konsolidierung bringt euch von 1,6 auf 22 pro Anzeigengruppe. Das ist eine Verbesserung um das Vierzehnfache und der mit Abstand größte Struktur-Hebel — aber es ist kein Freifahrtschein. Erst CPA-Senkung plus Konsolidierung gemeinsam lösen es.

---

## Teil 3 — Die korrigierte Struktur

### So würde ich es aufsetzen

**Eine Kampagne. Eine Anzeigengruppe. 200 €/Tag. Drei bis vier Creatives.**

| | |
| :-- | :-- |
| **Kampagne** | CBO, Ziel Käufe |
| **Anzeigengruppen** | **1** — Broad, DE + CH, Frauen 18–65, kein detailliertes Targeting |
| **Budget** | 200 €/Tag (Formel: 28 € × 50 ÷ 7) |
| **Platzierungen** | Manuell: Feed + Instagram Reels. Stories aus, bis 9:16-Assets fertig sind |
| **Creatives** | 3–4, die bereits geliefert haben |
| **Optimierung** | Käufe |

**Alles andere aus.** Konkret: AI ABO TEST, CBO TEST 2 und AZA CBO 27.07 laufen parallel mit zusammen 13 Anzeigengruppen — das muss auf eine zusammenschrumpfen.

Welche Creatives mitkommen, nach Leistung im August:

| Creative / Anzeigengruppe | CPA | ROAS |
| :-- | --: | --: |
| Image Broad Most Aware offer | 56,06 € | **0,936** |
| Kaiserschnitt | 58,63 € | 0,681 |
| Creative 58 Broad | 61,48 € | 0,503 |
| Adset 2 – AI (Variation 1) | 66,57 € | 0,593 |

Diese vier in **eine** Anzeigengruppe. Der Rest raus.

### Was ihr davon erwarten dürft

Nicht sofort Profitabilität. Realistisch:

- Weniger Streuung von Tag zu Tag, weil ein Topf statt dreizehn
- CPA von 87 € auf geschätzt **60–70 €** durch Platzierungen und Budgetkonzentration
- Zum ersten Mal auswertbare Daten auf Creative-Ebene

Von 60–70 € auf die nötigen 28 € kommt ihr **nicht über Meta-Einstellungen**. Der Rest muss aus Warenkorbwert, Conversion Rate und Checkout kommen.

---

## Teil 4 — Der Weg zu 50k

Jetzt zum Ziel. Ich rechne es ehrlich durch, weil die Zahl mehr verlangt, als du vielleicht erwartest.

### Was 50.000 € Monatsumsatz bedeuten

| | heute | Ziel |
| :-- | --: | --: |
| Monatsumsatz | ~4.700 € | **50.000 €** |
| Warenkorbwert | 39,60 € | 50 € |
| Bestellungen/Monat | ~118 | **1.000** |
| Bestellungen/Tag | ~4 | **33** |
| Werbebudget/Monat bei CPA 25 € | 8.150 € | **25.000 €** |
| Werbebudget/Tag | 272 € | **833 €** |

**Ihr braucht das Dreifache des Budgets und eine CPA, die ein Drittel der heutigen ist.**

### Warum die Reihenfolge nicht verhandelbar ist

Bei CPA 87 € und 833 €/Tag würdet ihr **rund 570 € pro Tag verlieren** — über 17.000 € im Monat. Skalierung multipliziert die Stückrechnung. Ist sie negativ, multipliziert sie den Verlust.

**Es gibt keinen Weg zu 50k, der nicht zuerst über die Stückrechnung führt.**

### Die realistische Zeitachse

**Phase 1 — Stückrechnung reparieren (jetzt bis ca. Mitte September)**
Budget bei 200–270 €/Tag halten, nicht erhöhen. Ziel: CPA unter 30 €.
Die vier Hebel: Platzierungen, Konsolidierung, Warenkorbwert auf 50 €, Checkout-Abschluss auf 65 %.
Erfolgskriterium: **7 Tage in Folge blended ROAS über 1,4.**

**Phase 2 — Lernphase knacken (ca. 2–4 Wochen)**
Bei CPA 28 € und 200 €/Tag erreicht ihr rechnerisch 50 Käufe/Woche. Zum ersten Mal optimiert Meta wirklich. Erwartungsgemäß fällt die CPA dann von allein weiter.

**Phase 3 — Skalieren (ab Oktober)**
Budget alle 48–72 Stunden um **maximal 20 %** erhöhen. Über vier Wochen lässt sich das Budget so fast verdreifachen, ohne die Lernphase zurückzuwerfen.

Von 270 € Tagesbudget aus:

| Woche | Tagesbudget |
| :-- | --: |
| Start | 270 € |
| +2 Wochen | ~470 € |
| +4 Wochen | ~810 € |
| +5 Wochen | ~970 € |

**Ihr könnt das nötige Budgetniveau in etwa fünf Wochen erreichen** — wenn die CPA hält. Das ist der Punkt, an dem die meisten scheitern: ROAS fällt beim Skalieren fast immer etwas. Steuert deshalb nicht auf Kampagnen-ROAS, sondern auf **MER** (Gesamtumsatz ÷ Gesamtwerbeausgaben) über das ganze Konto.

**Rechnerisch ist 50k bis Jahresende erreichbar** — aber nur, wenn Phase 1 im September steht. Jede Woche, die ihr weiter bei CPA 87 € fahrt, kostet euch nicht nur Geld, sondern verschiebt den Skalierungsstart nach hinten.

---

## Teil 5 — Was ich morgen früh machen würde

**Vor dem Frühstück, kostet nichts:**

1. Alles aus außer **einer** Kampagne mit **einer** Anzeigengruppe, 200 €/Tag, vier Creatives.
2. In dieser Anzeigengruppe: manuelle Platzierungen, nur Feed + Instagram Reels.
3. Shopify: automatische Nachfass-Mails für abgebrochene Checkouts aktivieren.

**Diese Woche:**

4. Bundle als vorausgewählte Option auf der Produktseite.
5. Lieferzeit im Checkout verbessern, Garantie und Bewertungen dort sichtbar machen.
6. Die 9:16-Assets fertigstellen — dann ist Stories einen sauberen Neutest wert.

**Und dann vier Tage nichts anfassen.** Bei einer Anzeigengruppe und 200 €/Tag habt ihr nach vier Tagen etwa 28 Käufe in einem Topf — zum ersten Mal seit Monaten eine Zahl, aus der man etwas lesen kann.

---

## Quellen

- [Meta Ads Learning Phase: 50 Events Per Week Explained](https://adlibrary.com/posts/meta-ads-learning-phase-50-events-guide)
- [The 50-Conversions-a-Week Rule: How Meta's Learning Phase Really Works in 2026 – Pigeon Digital](https://www.pigeondigital.com/insight/facebook-ads-learning-phase-50-conversions-rule-2026)
- [How Many Ad Sets Per Campaign in Meta Ads? 2026 Structure Guide – Vizup](https://www.tryvizup.com/blog/how-many-ad-sets-per-campaign-in-meta-ads-2026)
- [How to Exit the Meta Ads Learning Phase Fast and Start Scaling Profitably in 2026 – Modern Marketing Institute](https://www.modernmarketinginstitute.com/blog/how-to-exit-the-meta-ads-learning-phase-fast-and-start-scaling-profitably-in-2026)
- [Meta Advantage+ Placements: When to Use Them (2026) – AdNabu](https://blog.adnabu.com/facebook/meta-advantage-plus-placements/)
- [Meta Ads Placements: Optimize Feed, Stories & Reels ROI – Benly](https://benly.ai/learn/meta-ads/meta-ads-placements-optimization)
- [Meta Ads Placement Control 2026 – TheOptimizer](https://theoptimizer.io/blog/meta-ads-placement-control-in-2026-how-to-actually-block-placements-its-not-as-simple-anymore)
- [Meta Ads Scaling Strategy 2026 – CausalFunnel](https://www.causalfunnel.com/blog/how-to-scale-facebook-ads-effective-meta-ads-scaling-strategy-for-2026/)
- [Scaling Meta Ads: Vertical & Horizontal Growth Strategies 2026 – Benly](https://benly.ai/learn/meta-ads/scaling-meta-ads-guide)

*Hinweis zur Quellenqualität: Metas 50-Conversions-Vorgabe und die 20-%-Budgetregel sind über mehrere unabhängige Quellen konsistent und decken sich mit Metas eigener Dokumentation. Die Zahlen zur Advantage+-Überlegenheit stammen von Meta selbst und sind entsprechend interessengefärbt. Die Empfehlungen zur Anzahl der Anzeigengruppen sind Praktikerwissen ohne kontrollierte Studien — sie sind über Quellen hinweg einheitlich, aber nicht wissenschaftlich belegt.*
