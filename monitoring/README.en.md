<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Nidau only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:59 UTC, Nidau: systematic collection (nidau.tlex.ch): 26 addresses read; 0 added, 0 changed, 0 removed; no change; 32 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Nidau: systematic collection (nidau.tlex.ch)](https://nidau.tlex.ch/) | `<act>/` | daily | 2026-11-28 05:59 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:59](checks/2026-11.md#ch-lexwork-nidau-city-20261128t055919z) | lexwork-nidau-city | 26 | 0 | 0 | 0 | 32 (0) | no change `verify-differ` | — |
| [2026-11-27 06:03](checks/2026-11.md#ch-lexwork-nidau-city-20261127t060341z) | lexwork-nidau-city | 23 | 0 | 0 | 0 | 32 (0) | no change `verify-differ` | — |
| [2026-11-26 06:10](checks/2026-11.md#ch-lexwork-nidau-city-20261126t061012z) | lexwork-nidau-city | 26 | 0 | 0 | 0 | 32 (0) | no change `verify-differ` | — |
| [2026-11-25 06:30](checks/2026-11.md#ch-lexwork-nidau-city-20261125t063051z) | lexwork-nidau-city | 40 | 19 | 0 | 0 | 32 (0) | changes found `verify-differ` | [34](https://github.com/lexifina/switzerland-nidau-city-law/compare/745d0d24dd07...8b56545ebb44) |
| [2026-11-24 14:44](checks/2026-11.md#ch-lexwork-nidau-city-20261124t144412z) | lexwork-nidau-city | 28 | 19 | 0 | 0 | 51 (0) | the check failed | — |
| [2026-11-24 12:11](checks/2026-11.md#ch-lexwork-nidau-city-20261124t121103z) | lexwork-nidau-city | 101 | 51 | 0 | 0 | 51 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
