# Skript-Richtlinien

> **Status:** Entwurf — abgeleitet aus [00-konzept.md](00-konzept.md).

Weil es (vorerst) keinen Sprecher gibt, ist das Skript kein Sprechtext, sondern eine **Zweispalten-Partitur**: links was zu sehen/hören ist, rechts der eingeblendete englische Text. Die Vorlage dafür ist [`templates/skript-vorlage.md`](../templates/skript-vorlage.md).

## Textmenge

On-Screen-Text wird gelesen, nicht gehört. Als Faustregel:

- **Lesezeit:** ca. 2,5 Wörter pro Sekunde, plus 0,5 Sek. Vor- und Nachlauf pro Einblendung
- **Pro Einblendung:** max. 14 Wörter / 2 Zeilen
- **Pro Minute Video:** grob 45–70 Wörter — deutlich weniger als ein gesprochenes Skript (≈150 Wörter/Min.)
- **Ein 8-Minuten-Video** liegt damit bei etwa 350–500 Wörtern Gesamttext

Wenn ein Gedanke mehr Text braucht, ist er meistens nicht zu Ende gedacht — oder er gehört ins Bild statt in den Text.

## Textfreie Zonen

Diese Abschnitte laufen bewusst ohne oder mit fast keinem Text:

- Hook (0:00–0:20): höchstens ein Kurzinsert, das Bild trägt
- Kapitel 4 „Den Moment wirken lassen": idealerweise 0 Wörter
- die letzten ~5 Sekunden vor dem Schlussbild

## Aufbau eines Kapitels

Jedes Kapitel im Skript bekommt:

1. **Zeitfenster** (Richtwert aus dem Konzept)
2. **Visual:** welches Gameplay/welche Cutscene, ungefähre Quellenstelle
3. **Audio:** Originalton, Musikstück, Stille
4. **Text:** die exakten englischen Einblendungen, wortwörtlich wie sie im Video stehen
5. **Notiz:** Schnitthinweise, alles was nicht ins Video kommt

## Sprachliche Regeln für die Einblendungen

- Präsens, aktiv: „The music drops out." statt „The music has been faded out."
- keine Füllwörter: `actually`, `basically`, `honestly`, `just` streichen
- keine Meta-Sprache: nicht „In this video we look at …"
- keine Wertung ohne Beleg — jede Behauptung hat ein Bild darunter, das sie stützt
- Zahlen und Jahreszahlen nur, wenn sie etwas erklären

## Qualitätscheck vor dem Schnitt

- [ ] Hook funktioniert stumm und ohne Vorwissen
- [ ] Kapitel 3 erklärt **warum**, erzählt nicht nach
- [ ] keine Einblendung länger als 2 Zeilen
- [ ] Kapitel 4 ist textfrei
- [ ] Titel und Thumbnail verraten keine entscheidende Wendung ([Spoiler-Regel](00-konzept.md#spoiler))
- [ ] kein Satz, den man ohne Verlust streichen könnte
- [ ] Gesamttext unter der Wortzahl-Faustregel
