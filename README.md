# AutoQuant

![Status](https://img.shields.io/badge/Status-Private_Implementation-critical)
![Focus](https://img.shields.io/badge/Focus-Crypto_Perpetual_Futures-blue)
![License](https://img.shields.io/badge/Copyright-All_Rights_Reserved-red)

**Public portfolio for AutoQuant (crypto perpetual futures research infrastructure).**

> **⚠️ ACCESS NOTICE:**
> * **Core implementation is private** and intentionally not included (no runnable strategy/backtest engine).
> * This repo only contains high-level, non-actionable information to demonstrate engineering capability (**no code that can reproduce the system**).

---

## 🔗 Links

* **Preprint (arXiv)**: [https://doi.org/10.48550/arXiv.2512.22476](https://doi.org/10.48550/arXiv.2512.22476)
* **Resume (LaTeX)**: [`resume/resume.tex`](resume/resume.tex)
* **Resume (PDF)**: [`resume/CV.pdf`](resume/CV.pdf)
* **Contact**: [kh.deng@foxmail.com](mailto:kh.deng@foxmail.com)

---

## ❓ What This Repository Is (and Is Not)

* **✅ Is**: A documentation-only portfolio that explains engineering principles and deliverable standards.
* **❌ Is not**: A runnable trading system, a backtesting engine, strategy source code, parameter search pipeline, or reproducible research workflow.

---

## 📂 Portfolio Contents

* `README.md`: Capabilities, deliverables, and engagement standards.
* `resume/`: CV sources and PDF.
* `NOTICE.md`: IP and disclosure notice.

---

## 🛠 Engineering Capabilities (High Level)

* **No-lookahead backtesting semantics**: Strict $t \to t+1$ style execution constraints.
* **Execution-cost modeling**: Fees, slippage, and funding rates integrated as part of evaluation.
* **Robust evaluation**: Walk-forward style validation and auditability mindset.

---

## 📦 Typical Paid Deliverables (Scoped Modules)

* **Slippage model upgrade**: Spread/volatility/volume-aware models with unit tests and calibration notes.
* **Cost accounting breakdown**: Granular PnL analysis (fees/slippage/funding) for audits and sensitivity checks.
* **Robust evaluation tooling**: Walk-forward validation pipelines and ranking exports.
* **Data/semantic validators**: Alignment checks, no-lookahead verification, and acceptance reports.

---

## 🤝 Engagement / Acceptance Standard

1.  **Clear scope + acceptance criteria** before implementation.
2.  **Reproducible verification instructions** and test evidence (as applicable).
3.  **Minimal, rollback-friendly changes**.

---

## ⚖️ Verification & IP

* **Verification**: This portfolio is intentionally non-executable. For public technical details, please refer to the preprint. Private implementation walk-throughs or additional evidence can be provided on request.
* **Intellectual Property**: Copyright (c) 2026 Kaihong Deng. All rights reserved.
