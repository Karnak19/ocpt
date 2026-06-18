---
description: Show ponytail commands and usage
---

Available ponytail commands:

- `/ponytail [lite|full|ultra|off]` — Switch intensity level (default: full)
- `/ponytail-review` — Review current diff for over-engineering
- `/ponytail-audit` — Audit entire repo for over-engineering
- `/ponytail-debt` — Harvest ponytail: shortcuts into a debt ledger
- `/ponytail-help` — This help message

Levels:
- **lite** — Build what's asked, name the lazier alternative
- **full** — The ladder enforced. Stdlib and native first. Default.
- **ultra** — YAGNI extremist. Deletion before addition.
- **off** — Disable ponytail for this session

Environment: Set `PONYTAIL_DEFAULT_MODE` to change the default level.
