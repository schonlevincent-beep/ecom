# Prompt — Advertorial-Landingpage "Das Hautjournal"

*Kopieren, Platzhalter in [KLAMMERN] ersetzen, den Whistleblower-Native-Text unten anhängen, dann an Claude / v0 / Lovable geben.*

---

## PROMPT (ab hier kopieren)

Du baust eine Advertorial-Landingpage als **eine einzige, vollständige HTML-Datei** (CSS und minimales JS inline, keine externen Abhängigkeiten außer Google Fonts). Die Seite ist der Klick-Ziel einer Facebook-Native-Ad. Der komplette Ad-Text steht am Ende dieses Prompts — lies ihn zuerst vollständig, denn die Seite muss sich anfühlen wie die **direkte Fortsetzung** dieses Textes, nicht wie eine neue Seite.

### Die Publikation

Die Seite erscheint auf **"Das Hautjournal"** — einem unabhängigen redaktionellen Magazin für Hautgesundheit. Der Leser muss den Eindruck haben, einen ernsthaften Fachartikel zu lesen, nicht eine Werbeseite. Das ist die wichtigste Designentscheidung der ganzen Seite: **Sie sieht aus wie Journalismus, nicht wie E-Commerce.**

- Kopfzeile: schlichtes Wort-Logo "Das Hautjournal", darunter eine feine Trennlinie, optional eine dezente Rubrikleiste ("Hautbarriere · Wirkstoffe · Erfahrungsberichte")
- Über der Überschrift eine Rubrik-Kennzeichnung: "Erfahrungsbericht" oder "Aus der Praxis"
- Unter der Überschrift eine Autorenzeile mit Platzhalter: `[AUTORENFOTO]` (rund, klein), Name `[AUTORIN]`, Funktion "Kosmetikerin, 32 Jahre Berufserfahrung", Datum, "Lesezeit: ca. 9 Minuten"
- **Wichtig:** Keine erfundenen Presse-Logos, keine "Bekannt aus"-Leiste, keine erfundenen Institute. Seriosität entsteht durch Zurückhaltung, nicht durch Behauptungen.

### Absolute Regel zur Markennennung

Der Name **Azaléa** und das Produkt **Retinal Peptide** dürfen erst im letzten Abschnitt der Seite auftauchen — im Angebotsblock. Bis dahin: kein Markenname, kein Produktbild, kein Kaufbutton, keine Preise, keine Rabatt-Banner. Wer vorher scrollt, sieht ausschließlich redaktionellen Inhalt. Das ist nicht verhandelbar; es ist der ganze Trick des Formats.

### Was der Text leisten muss

Der Leser kommt aufgeladen an: Er hat gerade eine lange, persönliche Geschichte über eine Kosmetikerin gelesen, die 32 Jahre lang geschwiegen hat. Die Seite darf diese Temperatur **nicht** abkühlen.

1. **Kein Neustart.** Der erste Absatz setzt dort an, wo die Anzeige aufhört. Nicht "Willkommen", nicht "Viele Frauen kennen das". Eher: Sie erzählt weiter, sie geht ins Detail, sie zeigt, was sie in der Anzeige nur andeuten konnte.
2. **Neuer Informationsgewinn.** Die Seite darf die Anzeige nicht nacherzählen. Sie muss liefern, was in der Anzeige fehlte: die genaue Mechanik, die Zahlen, die Erfahrungsberichte anderer, die konkrete Anwendung.
3. **Offene Schleifen.** Jede Zwischenüberschrift stellt eine Frage oder deutet etwas an, das erst im nächsten Abschnitt aufgelöst wird. Der Leser soll nie einen natürlichen Ausstiegspunkt finden.

### Aufbau der Seite (in dieser Reihenfolge)

1. **Überschrift** — im Ton eines Fachartikels, nicht eines Werbeversprechens. Keine Ausrufezeichen, keine Superlative.
2. **Vorspann** (2–3 Sätze, größere Schrift, andere Farbe) — greift die Anzeige auf und macht sofort ein neues Versprechen, was der Leser hier erfährt.
3. **Teil 1 — Was ich in 10.000 Karteien gesehen habe.** Sie erzählt weiter, wird konkreter. Muster statt Einzelfall. Hier arbeitest du mit Wiedererkennung: eine Liste von Anzeichen, in der sich der Leser selbst findet (Rötungen, die nicht weggehen · Brennen bei milden Cremes · fahler Teint · Haut reagiert auf alles · Fältchen, die früher kommen als sie sollten).
4. **Teil 2 — Warum niemand es dir sagt.** Der Interessenkonflikt der Branche, ohne Verschwörungston. Der Villain ist ein Geschäftsmodell, das von monatlichen Terminen und dem nächsten Produkt lebt — nicht "die Bösen".
5. **Teil 3 — Was in deiner Haut wirklich passiert.** Der Mechanismus, sachlich und verständlich: Hautbarriere, Cortisol und nächtliche Regeneration, warum Feuchtigkeit allein nichts repariert ("Wasser in ein Sieb füllen"). Hier ein Platzhalter `[GRAFIK: Hautbarriere intakt vs. geschwächt]` mit Bildunterschrift.
6. **Teil 4 — Warum die meisten Produkte scheitern.** Die Leiter der gescheiterten Lösungen: mildere Produkte, Weglassen, Peelings, teure Sets. Warum jedes davon nur beruhigt statt zu erneuern.
7. **Teil 5 — Der eine Unterschied: Retinal statt Retinol.** Die eigentliche Enthüllung. Retinol braucht zwei Umwandlungsschritte im Körper, bei jedem geht Wirkung verloren; Retinal braucht einen. Peptide als zweite Hälfte: Retinal signalisiert Erneuerung, Peptide signalisieren Aufbau. Gleichzeitig statt nacheinander. Hier gehören die belastbaren Zahlen hin: `[STUDIENZAHLEN EINSETZEN — z. B. 12 % weniger feine Linien nach 8 Wochen, Anteil empfindliche Haut ohne Reizung, Quelle: Journal of Drugs in Dermatology 2024]`. Quelle immer sichtbar nennen.
8. **Teil 6 — Erfahrungsberichte.** Siehe eigener Abschnitt unten.
9. **Teil 7 — Was du realistisch erwarten kannst.** Eine ehrliche Zeitleiste (Woche 1–2 Eingewöhnung, Woche 4, Woche 8, Woche 12) und ein Absatz "Für wen das nichts ist". Ehrlichkeit an dieser Stelle ist der stärkste Vertrauensbeweis der ganzen Seite.
10. **Teil 8 — Das Angebot.** Erst hier fällt zum ersten Mal ein Markenname. Siehe eigener Abschnitt unten.
11. **FAQ** — 6–8 Fragen im Aufklapp-Format, in der Sprache echter Einwände ("Brennt es?", "Wann sehe ich etwas?", "Kann ich es mit meiner Routine kombinieren?", "Warum nicht Retinal und Peptide getrennt kaufen?", "Ist das auch für empfindliche Haut geeignet?", "Was ist in der Schwangerschaft?").
12. **Fußzeile** — Impressum-Links, Hinweis zur Werbekennzeichnung, medizinischer Disclaimer.

### Erfahrungsberichte (Social Proof)

3–4 Blöcke, gestaltet wie redaktionelle Leserstimmen, nicht wie Shop-Bewertungen:

- Jeder Block: `[FOTO PLATZHALTER 1:1]` als grauer Kasten mit Beschriftung, **darunter zwingend eine Bildunterschrift in kleiner Schrift**: `Name, Alter, Ort` — z. B. "Sabrina M., 34, Hamburg"
- Darunter das Zitat in etwas größerer Serifenschrift, ausgezeichnet als echtes Zitat
- Darunter eine feine Zeile: "Anwendung seit [X] Wochen"
- **Keine Sternebewertungen** in diesem Abschnitt — Sterne machen aus dem Artikel eine Shopseite. Sterne kommen erst im Angebotsblock.
- Ein Block sollte bewusst zurückhaltend formuliert sein ("nicht über Nacht, aber nach sechs Wochen sah ich es") — ein zu perfekter Chor wirkt gekauft.
- Kommentar für die Redaktion als HTML-Kommentar einfügen: `<!-- Nur echte, dokumentierte Kundenstimmen verwenden. Keine erfundenen Namen. -->`

### Der Angebotsblock

- Optischer Bruch zum Artikel: leicht abgesetzter Hintergrund, Rahmen, klar erkennbar als Angebot (auch aus Transparenzgründen)
- Überleitungssatz aus dem Artikel heraus, sinngemäß: "Ich werde oft gefragt, welches Produkt ich meine. Es geht mir nicht um eine Marke, sondern um die Form des Wirkstoffs. Die Formulierung, die ich meiner Tochter gegeben habe, ist diese:"
- **Erst hier:** `[PRODUKTBILD AZALÉA RETINAL PEPTIDE]` als großer Platzhalter, Produktname, kurze Wirkstoffangabe
- Preisblock: `[STREICHPREIS]` durchgestrichen, `[AKTIONSPREIS]` groß, Badge "-40 %"
- Vertrauenselemente in einer Reihe: 30 Tage Geld-zurück-Garantie · Versand aus [LAND] · dermatologisch getestet `[nur wenn belegbar]`
- Ein Button, deutlich, mit handlungsorientiertem Text (nicht "Jetzt kaufen", eher "Zum Retinal Peptide"). Ziel-URL Platzhalter: `[PRODUKT-URL]`
- Direkt unter dem Button die Sterne + Bewertungsanzahl `[4,8/5 · X Bewertungen]`
- Darunter klein: Preisangaben-Hinweis und Schwangerschaftshinweis

### Copywriting-Prinzipien (CashVertising)

Wende beim Schreiben folgende Prinzipien an, aber unsichtbar — der Text darf nie nach Werbetext klingen:

- **Lebenskräfte (LF8):** Bediene primär *Freiheit von Schmerz und Unsicherheit* und *soziale Anerkennung / attraktiv sein*. Der emotionale Kern ist nicht "schöne Haut", sondern "sich im eigenen Gesicht wiedererkennen" und "nicht mehr das Gefühl haben, dass nichts hilft".
- **Angst richtig einsetzen:** Angst wirkt nur, wenn direkt eine konkrete, machbare Handlung folgt. Nie Angst ohne Ausweg im selben Abschnitt. Und: **keine medizinische Angstmache.** Keine Krankheitsandeutungen, keine irreversiblen Schäden, keine "deine Haut altert unaufhaltsam"-Drohungen. Die legitime Dringlichkeit ist sachlich: Solange die Barriere nicht aktiv aufgebaut wird, bleibt der Kreislauf bestehen — das reicht völlig.
- **Ego-Morphing:** Der Leser soll sich in den Erfahrungsberichten selbst sehen — gleiches Alter, gleicher Alltag, gleicher Frust.
- **Means-End-Chain:** Immer von der Eigenschaft zum Endnutzen durchziehen: Retinal → ein Umwandlungsschritt → mehr Wirkung bei weniger Reizung → Haut erneuert sich → man erkennt sich wieder.
- **Inoculation / Einwandvorwegnahme:** Den größten Einwand aussprechen, bevor der Leser ihn denkt — hier: "Du hast gerade gelesen, dass Produkte das Problem sind, und jetzt kommt ein Produkt." Diesen Widerspruch offen benennen und auflösen (es geht um die Wirkstoffform, nicht um die Marke). Wenn du das auslässt, verliert die Seite ihre glaubwürdigsten Leser.
- **Zentrale Verarbeitungsroute:** Hautpflege ist eine Entscheidung mit hoher Beteiligung. Der Leser will Argumente, nicht Stimmung. Gib ihm Zahlen, Mechanik und Quellen — Emotion trägt nur den Rahmen.
- **Spezifität schlägt Superlative:** "12 % weniger feine Linien nach 8 Wochen" ist stärker als "sichtbar glattere Haut".

### Ton und Sprache

Deutsch, Du-Ansprache, ruhig, erwachsen. Erzählt aus der Ich-Perspektive der Kosmetikerin, durchgehend dieselbe Stimme wie in der Anzeige. Kurze Absätze (2–4 Zeilen), viele Zeilenumbrüche — das wird auf dem Handy gelesen. Keine Emojis, keine Ausrufezeichen, keine Marketingfloskeln ("Revolution", "Geheimwaffe", "endlich"). Wo es passt, ein einzelner Satz als eigener Absatz zur Betonung.

### Design

- Mobile First — 90 % des Traffics kommt aus dem Facebook-Feed auf dem Handy
- Lesetypografie: Serifenschrift für den Fließtext (z. B. Lora oder Source Serif), serifenlose Schrift für Überschriften und UI, Schriftgröße mindestens 18 px, Zeilenhöhe 1,7, Textspalte maximal 680 px
- Farben: gebrochenes Weiß als Hintergrund, sehr dunkles Grau für Text (kein reines Schwarz), ein einziger zurückhaltender Akzent (gedämpftes Salbeigrün oder Sandton). Kein Rot, kein Gelb, keine Verlaufsflächen.
- Bildplatzhalter: hellgraue Kästen mit gestricheltem Rahmen, mittig die Beschriftung des benötigten Bildes und das Seitenverhältnis, damit die Redaktion sie später ersetzen kann
- Zitate im Text: linker Balken in Akzentfarbe, kursiv, größer
- Ein dezenter Lesefortschrittsbalken oben — verstärkt den Artikel-Charakter und die Sogwirkung
- Kein Sticky-Kaufbutton im oberen Seitenbereich. Optional: ein unaufdringlicher Sticky-Balken, der **erst ab 70 % Scrolltiefe** erscheint
- Keine Pop-ups, keine Countdown-Timer, keine Exit-Intent-Overlays — jedes dieser Elemente zerstört die redaktionische Glaubwürdigkeit, die die ganze Seite trägt

### Rechtliches und Compliance (verbindlich)

- Nie: "heilt", "beseitigt", "Falten verschwinden", "wirkt bei jedem". Immer: "verbessert", "unterstützt", "bei mir", "in Studien zeigte sich"
- Studienangaben nur mit Quelle; keine erfundenen Zahlen, keine erfundenen Zitate, keine erfundenen Namen
- **Schwangerschaftshinweis** im FAQ und im Angebotsblock: Retinoid — in Schwangerschaft und Stillzeit nicht anwenden
- SPF-Hinweis: Vitamin A abends, morgens Sonnenschutz
- Rabattangabe nach § 11 PAngV: niedrigster Gesamtpreis der letzten 30 Tage als Referenz
- Werbekennzeichnung im Fußbereich, z. B. "Dieser Beitrag enthält Werbung"
- Impressum-, Datenschutz- und Widerrufslinks in der Fußzeile
- Medizinischer Disclaimer: ersetzt keine ärztliche Beratung

### Technisches

- Eine einzige HTML-Datei, valides HTML5, semantische Tags (`article`, `section`, `figure`, `figcaption`, `blockquote`)
- Ladezeit ist umsatzrelevant: keine schweren Bibliotheken, Schriften mit `display=swap`
- Alle Platzhalter klar als HTML-Kommentar markiert, damit sie leicht zu finden sind
- CTA-Links mit `data-`Attribut versehen, damit später ein Klick-Event getrackt werden kann
- Kommentar-Block am Dateianfang mit einer Liste aller zu ersetzenden Platzhalter

Gib am Ende nur die fertige HTML-Datei aus, ohne Erklärungen davor oder danach.

---

**HIER DEN VOLLSTÄNDIGEN WHISTLEBLOWER-ANZEIGENTEXT EINFÜGEN:**

```
[NATIVE-AD-TEXT KOMPLETT EINFÜGEN]
```

---

## Hinweise für euch (nicht Teil des Prompts)

- Der Prompt erzeugt die Struktur und einen kompletten Textentwurf. Die Erfahrungsberichte müsst ihr durch echte Kundenstimmen ersetzen — erfundene Namen unter Fotos sind der schnellste Weg zu einer Abmahnung und zu einem Meta-Konto-Problem.
- Testet die Seite gegen die PDP: gleiche Ad, zwei Ziele, ATC-Rate vergleichen. Das ist die eigentliche Frage, die ihr beantworten wollt.
- Denkt daran, auf der neuen Seite dieselben Pixel-Events auszulösen wie im Shop (mindestens ViewContent), sonst verliert ihr das Signal komplett.
