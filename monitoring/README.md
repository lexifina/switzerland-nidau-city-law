<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Nidau: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 05:59 UTC, Nidau: Systematische Sammlung (nidau.tlex.ch): 26 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 32 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Nidau: Systematische Sammlung (nidau.tlex.ch)](https://nidau.tlex.ch/) | `<act>/` | täglich | 2026-11-28 05:59 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:59](checks/2026-11.md#ch-lexwork-nidau-city-20261128t055919z) | lexwork-nidau-city | 26 | 0 | 0 | 0 | 32 (0) | keine Änderung `verify-differ` | — |
| [2026-11-27 06:03](checks/2026-11.md#ch-lexwork-nidau-city-20261127t060341z) | lexwork-nidau-city | 23 | 0 | 0 | 0 | 32 (0) | keine Änderung `verify-differ` | — |
| [2026-11-26 06:10](checks/2026-11.md#ch-lexwork-nidau-city-20261126t061012z) | lexwork-nidau-city | 26 | 0 | 0 | 0 | 32 (0) | keine Änderung `verify-differ` | — |
| [2026-11-25 06:30](checks/2026-11.md#ch-lexwork-nidau-city-20261125t063051z) | lexwork-nidau-city | 40 | 19 | 0 | 0 | 32 (0) | Änderungen gefunden `verify-differ` | [34](https://github.com/lexifina/switzerland-nidau-city-law/compare/745d0d24dd07...8b56545ebb44) |
| [2026-11-24 14:44](checks/2026-11.md#ch-lexwork-nidau-city-20261124t144412z) | lexwork-nidau-city | 28 | 19 | 0 | 0 | 51 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 12:11](checks/2026-11.md#ch-lexwork-nidau-city-20261124t121103z) | lexwork-nidau-city | 101 | 51 | 0 | 0 | 51 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
