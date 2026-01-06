# AutoQuant

Public portfolio for **AutoQuant** (crypto perpetual futures research infrastructure).

- **Core implementation is private** and intentionally not included (no runnable strategy/backtest engine).
- This repo only contains high-level, non-actionable information to demonstrate engineering capability (**no code that can reproduce the system**).

## Links

- Preprint (arXiv): https://doi.org/10.48550/arXiv.2512.22476
- Resume (LaTeX): `resume/resume.tex`
- Resume (PDF): `resume/CV.pdf`
- Contact: kh.deng@foxmail.com

## What This Repository Is (and Is Not)

- Is: a documentation-only portfolio that explains engineering principles and deliverable standards.
- Is not: a runnable trading system, a backtesting engine, strategy source code, parameter search pipeline, or reproducible research workflow.

## Portfolio Contents

- `README.md`: capabilities, deliverables, and engagement standard
- `resume/`: CV sources and PDF
- `NOTICE.md`: IP and disclosure notice

## Engineering Capabilities (High Level)

- No-lookahead backtesting semantics (t→t+1 style execution constraints)
- Execution-cost modeling (fees/slippage/funding) as part of evaluation
- Robust evaluation (e.g., walk-forward style validation) and auditability mindset

## Typical Paid Deliverables (Scoped Modules)

- Slippage model upgrade (spread/volatility/volume-aware) with unit tests and calibration notes
- Cost accounting breakdown (fees/slippage/funding) for audits and sensitivity checks
- Robust evaluation tooling (walk-forward style validation, ranking exports)
- Data/semantic validators (alignment, no-lookahead checks) and acceptance reports

## Engagement / Acceptance Standard

- Clear scope + acceptance criteria before implementation
- Reproducible verification instructions and test evidence (as applicable)
- Minimal, rollback-friendly changes

## Verification

- This portfolio is intentionally non-executable. For public technical details, please refer to the preprint.
- Private implementation walk-throughs or additional evidence can be provided on request.

## Intellectual Property

Copyright (c) 2026 Kaihong Deng. All rights reserved.
