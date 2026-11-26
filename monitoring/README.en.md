<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Aargau only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:37 UTC, Aargau: systematic collection (gesetzessammlungen.ag.ch): 111 addresses read; 0 added, 1 changed, 0 removed; changes found; 66 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Aargau: systematic collection (gesetzessammlungen.ag.ch)](https://gesetzessammlungen.ag.ch/) | `<act>/` | daily | 2026-11-26 05:37 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:34](checks/2026-11.md#ch-lexwork-aargau-20261126t053453z) | lexwork-aargau | 111 | 0 | 1 | 0 | 66 (0) | changes found | — |
| [2026-11-25 05:28](checks/2026-11.md#ch-lexwork-aargau-20261125t052825z) | lexwork-aargau | 348 | 106 | 1 | 0 | 65 (0) | changes found | [308](https://github.com/lexifina/switzerland-aargau-law/compare/2c0ba20e1ae3...a01fc47b704f) |
| [2026-11-24 14:26](checks/2026-11.md#ch-lexwork-aargau-20261124t142624z) | lexwork-aargau | 151 | 106 | 0 | 0 | 169 (0) | the check failed | — |
| [2026-11-24 12:53](checks/2026-11.md#ch-lexwork-aargau-20261124t125348z) | lexwork-aargau | 176 | 114 | 2 | 0 | 169 (0) | the check failed | — |
| [2026-11-24 11:50](checks/2026-11.md#ch-lexwork-aargau-20261124t115002z) | lexwork-aargau | 473 | 166 | 0 | 0 | 167 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
