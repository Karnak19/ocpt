---
description: Audit entire repo for over-engineering
---

Audit the entire repository for over-engineering, not just the current diff. Look for: dead code, speculative abstractions, reinvented stdlib, dependencies doing what native features do, unnecessary interfaces/factories/configs, boilerplate nobody asked for. One line per finding: <file>:<line>: <tag> <what to cut>. <replacement>. Tags: delete, stdlib, native, yagni, shrink. Group by file. End with total lines removable.
