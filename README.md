# UPSide Security Landscape

Public-source research corpus of **UPSide Academy cohorts 1–4 (2024–2026)**.

This repository is designed as both:

1. a longitudinal map of UPSide Academy security research/projects, and
2. a reproducible learning/portfolio project that records what was verified, revised, or left unknown.

## Research questions

- How have UPSide Academy project themes changed across cohorts 1–4?
- Which attack surfaces and methodologies recur, disappear, or become more specialized?
- How do outputs evolve from guides/threat models into tools, benchmarks, datasets, and infrastructure?
- Which final projects survive beyond graduation as public research, conference talks, repositories, or follow-up work?
- Where does AI-assisted analysis help, and where does primary-source verification change the initial interpretation?

## Corpus structure

```text
.
├── README.md
├── data/
│   ├── projects.csv
│   └── sources.csv
├── docs/
│   └── evidence-policy.md
├── baseline/
│   ├── what-i-know.md
│   ├── what-i-think-i-know.md
│   ├── what-i-dont-know.md
│   └── first-hypotheses.md
├── corrections/
│   └── revision-log.md
├── experiment/
├── limits/
│   └── questions-for-experts.md
├── interview-bank/
│   └── wrong-answer-log.md
├── raw/ai-first-pass/
├── notes/
└── failed/
```

## Evidence policy

Every claim should be traceable to a source and assigned an evidence level.

- **A** — UPSide / Dunamu / Theori / conference official material
- **B** — participant's own GitHub, blog, portfolio, or presentation material
- **C** — reputable media quoting or reproducing organizer material
- **D** — inference requiring verification

`not_found_publicly` means that a public artifact was not located in the current search. It does **not** mean that the artifact does not exist.

See [`docs/evidence-policy.md`](docs/evidence-policy.md).

## Initial dataset

The first dataset contains the **16 identified cohort final projects** plus source records for official cohort pages, technical articles, public repositories, videos, conference follow-ups, and alumni research.

### Cohort 1

- 다섯공주들 — **Scouter X**
- Gamza.net — **Uniswap v4 Hook Security Tooling**
- 시추코기 — **Paymaster Threat Modeling**
- DeepHigh — **Lending Protocol Threat Modeling Framework / Attack Library**

### Cohort 2

- UMA — **Account Abstraction + Cross-chain Audit & Threat Modeling**
- Chain Stalker — **Perp DEX Money-Laundering Effectiveness Analysis**
- 베어문 — **Berachain PoL Threat Analysis & Security Guideline**
- Stak Audit Flow — **Smart Contract AI Audit Agent**

### Cohort 3

- Funarchy — **Prediction Market Audit & Threat Modeling**
- 우리는 월렛(wallet) 그래 — **Social Login Wallet SDK Security Review**
- Giwa second — **Project Bonghwa: GIWA Verified Address Tracking & Reputation**
- Koracle — **GIWA Security Oracle Infrastructure**

### Cohort 4

- 지갑방위대 — **Pre-signing Personal Policy Management / Unintended Signature Prevention**
- Bench-Clearing — **Web3 Audit AI Agent Benchmark**
- bonda — **Blockchain Data Availability Ecosystem Threat Modeling**
- Chain Spiral — **DeFi Risk Visualization Map / Exposure Intelligence**

## Working workflow

```text
Own first-pass hypothesis
        ↓
AI-assisted classification
        ↓
Official source / GitHub / protocol docs
        ↓
Correction log
        ↓
Longitudinal analysis
        ↓
Technical deep dive
        ↓
Expert calibration
```

## Status

This is a living corpus. Missing repositories, slide decks, videos, alias mappings, and cohort attribution should remain explicit `unknown`/`not_found_publicly` values until verified.
