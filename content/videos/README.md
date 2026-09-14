# Videos

Ein Ordner je Video, benannt `<laufende-nummer>-<slug>`, zum Beispiel `01-half-life-2-ravenholm`.

## Inhalt eines Video-Ordners

```
01-half-life-2-ravenholm/
├── steckbrief.md        ← aus templates/video-steckbrief.md
├── skript.md            ← aus templates/skript-vorlage.md
├── thumbnail.md         ← aus templates/thumbnail-briefing.md
├── beschreibung.md      ← fertiger YouTube-Text inkl. Kapitelmarken
└── recherche/           ← Notizen, Zitate, Quellenauszüge
```

Videodateien, Rohmaterial und Bilddaten gehören **nicht** ins Repository — nur Text. Der Ablageort für Material wird im Steckbrief vermerkt.

## Anlegen

1. Ordner erstellen
2. Vorlagen aus [`templates/`](../../templates/) hineinkopieren und umbenennen
3. Zeile im [Redaktionsplan](../redaktionsplan.md) ergänzen
