# UPSide Security Landscape

Public-source research corpus of **UPSide Academy cohorts 1–4 (2024–2026)**.

> **Day 0 note:** the repository began as an **AI-assisted scaffold**, not as a completed analysis. I had not personally reviewed most collected sources in depth when the initial structure, dataset, classifications, and hypotheses were created. They are starting points to be checked, corrected, understood, and technically verified over time. See [`docs/day-0-ai-scaffold.md`](docs/day-0-ai-scaffold.md).

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
│   ├── evidence-policy.md
│   └── day-0-ai-scaffold.md
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

## Verification states

The project separates **source quality** from **my own level of verification**:

- **0 — AI-scaffolded:** collected/classified/proposed by AI; not personally verified yet
- **1 — Source-checked:** I personally opened the relevant source and confirmed the recorded claim
- **2 — Understood:** I can explain the concept and answer basic follow-up questions in my own words
- **3 — Technically verified:** I verified at least part of it through code, reproduction, protocol documentation, tests, or equivalent technical evidence

These states are not quality scores. They show how far I personally verified the material.

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
AI-assisted scaffold / first-pass hypothesis
        ↓
Personal source check
        ↓
Understand in my own words
        ↓
Correction log
        ↓
Longitudinal analysis
        ↓
Technical deep dive / reproduction
        ↓
Explicit unknowns
        ↓
Expert calibration
```

## Status

This is a living corpus. Missing repositories, slide decks, videos, alias mappings, and cohort attribution should remain explicit `unknown`/`not_found_publicly` values until verified.

The initial Day 0 material should not be read as proof that I had already understood or validated every item. The point of the repository is to preserve the transition from **AI-assisted first pass → personal verification → correction → technical understanding → remaining uncertainty**.
