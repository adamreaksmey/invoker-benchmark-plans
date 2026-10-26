# Invoker benchmark plans

YAML plans used by the Invoker arms in the [orchestration benchmark](https://github.com/adamreaksmey/invoker-orchestration-benchmark).

## Layout

Each project folder has three plans:

| File | Arm | Meaning |
| --- | --- | --- |
| `arm-b-invoker-codex-uniform.yaml` | B | Invoker + Codex, all steps on `gpt-reserve` |
| `arm-c-invoker-codex-mixed.yaml` | C | Invoker + Codex, mixed model routing |
| `arm-e-invoker-cursor.yaml` | E | Invoker + Cursor workers (`grok-4.5`) |

Projects:

- `P1-ledger` — full-stack personal-finance app
- `P2-shortener` — HTTP link shortener
- `P3-wiki` — Markdown wiki / search service
- `P4-csv-cli` — CSV report CLI

Arms A (continuous Codex) and D (continuous Cursor) are not Invoker plans and are not included here.

Combined report: see `INVOKER-ORCHESTRATION-BENCHMARK-COMBINED.docx` in the Invoker workspace / harness report.
