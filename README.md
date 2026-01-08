# AutoQuant: Crypto Perpetual Futures Infrastructure

![Status](https://img.shields.io/badge/Status-Private_Implementation-critical)
![Research](https://img.shields.io/badge/Research-KDD%20%2F%20KBS-blue)
![License](https://img.shields.io/badge/Copyright-All_Rights_Reserved-red)

> **⚠️ ACCESS NOTICE:** > **Core implementation is PRIVATE.** This repository is a **documentation-only portfolio** demonstrating engineering standards and architectural principles. It does **NOT** contain runnable strategies, backtesting engines, or proprietary alpha factors.

---

## 🏆 WEEX AI Wars Entry: AlphaGuardian

This repository serves as the **conceptual and engineering framework** for the project **"AlphaGuardian"**, submitted to the **WEEX AI Wars Hackathon**.

* **Submission Focus**: **Auditable AI Strategy & Risk Governance**.
* **Key Innovation**: Implementing the **STRICT T+1 Protocol** (from my ESWA/KDD research) to eliminate look-ahead bias in high-frequency crypto trading.
* **Live Demo**: Please refer to the video submission/demo link provided in the DoraHacks platform.

---

## 🔗 Key Resources

* **📄 Research Preprint (arXiv)**: [https://doi.org/10.48550/arXiv.2512.22476](https://doi.org/10.48550/arXiv.2512.22476)
* **👨‍💻 Resume (CV)**: [`resume/CV.pdf`](resume/CV.pdf)
* **📧 Contact**: [kh.deng@foxmail.com](mailto:kh.deng@foxmail.com)

---

## 🛠 Engineering Capabilities (High-Level)

Derived from academic research and industrial practice, focusing on **Auditability** and **Robustness**:

* **Strict T+1 Semantics**:
    * Rigid separation of `Generation (t)` and `Execution (t+1)` to enforce no-lookahead constraints.
    * Semantic validators to reject any signal leaking future information.
* **High-Fidelity Cost Simulation**:
    * Accounting for **Tiered Fees**, **Dynamic Slippage** (Volatility-aware), and **Funding Rates**.
    * "Cost Stress Tests" to verify strategy viability under extreme market conditions.
* **Knowledge-Driven Governance**:
    * **Live Guard**: Real-time monitoring of "Semantic Drift" between backtest and live execution.
    * **Autonomous Kill-Switch**: Pre-defined logic to halt trading when statistical properties deviate from the baseline.

---

## 📦 Delivered Modules & Scopes

*While the core engine is private, the following modules represent my standard for deliverable engineering:*

1.  **Slippage Model Upgrade**: Spread/Volume-aware models with unit tests and calibration reports.
2.  **Audit Accounting System**: Granular breakdown of PnL (Fees vs. Slippage vs. Funding) for sensitivity analysis.
3.  **Robust Evaluation Tooling**: Walk-forward validation pipelines and ranking export utilities.
4.  **Semantic Validators**: Automated checks for data alignment and signal integrity.

---

## ✅ Engagement & Acceptance Standard

* **Defined Scope**: Clear acceptance criteria established before implementation.
* **Verifiable Evidence**: Reproducible verification instructions and test reports accompanying all deliverables.
* **Rollback-Friendly**: Minimal invasive changes with atomic commits.

---

## ⚖️ Verification & IP

* **Non-Executable**: This portfolio is intentionally designed as a static showcase. For technical details on the underlying algorithms, please refer to the linked **Research Preprint**.
* **Private Demo**: Private implementation walk-throughs or additional verification evidence can be provided upon request for potential employers or collaborators.

**Copyright (c) 2026 Kaihong Deng. All rights reserved.**
