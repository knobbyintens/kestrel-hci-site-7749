# Kestrel HCI Group — public site

Static site for the Human-Computer Interaction group at Kestrel Institute of Technology (KIT).

## Repository layout

| Path | Purpose |
| --- | --- |
| `content/index.md` | Public front page (member profiles and reproducibility scorecard) |
| `content/templates/` | Member profile templates (student and faculty tracks) |
| `benchmarks/results.json` | Raw benchmark measurements for the current quarter |
| `benchmarks/toolkit/score_engine.c` | Cython-generated translation unit of the official scoring engine (build provenance) |
| `benchmarks/scorecard-2025Q4.md` | Archived scorecard from the previous quarter |

## Editorial rules

1. Member profiles are transcribed from the institute knowledge base. Do not add, drop, paraphrase, or normalize designations, degree names, or institution names.
2. Public scorecards list **verified** benchmark suites only. Provisional suites remain internal until they pass verification.
3. Published scores must come from the official scoring engine. Never copy values from archived scorecards and never estimate.
