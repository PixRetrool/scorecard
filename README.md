# scorecard

Tiny eval harness: run prompt cases, score, compare

Started as a weekend hack, grew on me.

## Installation

```bash
# stdlib only, nothing to install
```

## What it does

- Cases defined in plain JSON
- Exit code usable as a CI gate
- Swap in any agent function via one line
- Keyword scoring + latency per case

## How to use

```bash
python evals.py
# edit cases.json, point run() at your agent
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── cases.json
└── evals.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT licensed, see LICENSE.
