# Produktionsworkflow

> **Status:** Entwurf. Tools sind noch nicht festgelegt → [offene-fragen.md](offene-fragen.md).

Sieben Phasen von der Idee bis zum Upload. Jedes Video läuft durch alle sieben; der Stand wird im [Redaktionsplan](../content/redaktionsplan.md) geführt.

## 1. Idee

Eintrag im [Ideen-Backlog](../content/ideen-backlog.md): Spiel, vermuteter Finest Part, in einem Satz warum.

**Fertig, wenn:** der Eintrag steht und die Auswahlkriterien aus dem Konzept erfüllt sind.

## 2. Auswahl & Steckbrief

Ordner `content/videos/<nummer>-<slug>/` anlegen, [`templates/video-steckbrief.md`](../templates/video-steckbrief.md) ausfüllen: Format, Kernthese, Spoilergrenze, benötigtes Material.

**Fertig, wenn:** die Kernthese in einem Satz steht und Michael sie freigegeben hat.

## 3. Recherche

- eigenes Spielen / eigene Aufnahme, wo möglich
- Entwickler-Interviews, Post-Mortems, GDC-Talks, Making-ofs
- Soundtrack-Credits, Komponist, verwendete Stücke
- alle Quellen mit Link in den Steckbrief

**Fertig, wenn:** die Kernthese durch mindestens einen nachprüfbaren Punkt gestützt ist, der über das eigene Empfinden hinausgeht.

## 4. Skript

[`templates/skript-vorlage.md`](../templates/skript-vorlage.md) ausfüllen, dann Qualitätscheck aus den [Skript-Richtlinien](03-skript-richtlinien.md#qualitätscheck-vor-dem-schnitt).

**Fertig, wenn:** der Check vollständig abgehakt ist.

## 5. Material

Capture nach der Shotlist im Skript. Regeln:

- höchste verfügbare Auflösung/Framerate, unkomprimiert aufnehmen
- HUD ausblenden, wo es geht
- jede Szene mit Puffer davor und danach aufnehmen
- Originalton getrennt sichern, wenn das Spiel das erlaubt
- Dateinamen: `<slug>_<kapitel>_<beschreibung>.mp4`

**Fertig, wenn:** jede Zeile der Shotlist Material hat.

## 6. Schnitt

Rohschnitt nach Skript → Ton → Text-Inserts → Farbe → Schlussbild.

**Fertig, wenn:** das Video ohne Skript daneben verständlich ist und die Zielminutenzahl nicht künstlich gestreckt wurde.

## 7. Veröffentlichung

Titel, Thumbnail, Beschreibung, Kapitelmarken, Playlist nach [05-titel-thumbnail-beschreibung.md](05-titel-thumbnail-beschreibung.md).
Rechtliches gegen [06-rechtliches-und-musik.md](06-rechtliches-und-musik.md) prüfen.

**Fertig, wenn:** die Upload-Checkliste im Steckbrief vollständig ist.

## Statuswerte im Redaktionsplan

`Idee` → `Ausgewählt` → `Recherche` → `Skript` → `Material` → `Schnitt` → `Veröffentlicht`
