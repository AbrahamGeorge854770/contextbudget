# contextbudget

Quick token/cost estimates for prompt budgeting

Built for my own use; public in case it helps someone.

## Highlights

- Per-model pricing table in JSON
- Reports input/output tokens and USD estimate
- Zero dependencies
- Heuristic token estimate (~4 chars/token)

## Usage

```bash
python cost.py prompt.txt --model gpt-4o-mini --expect-out 500
```

## Getting started

```bash
# stdlib only
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Makefile
├── SECURITY.md
├── cost.py
└── pricing.json
```
