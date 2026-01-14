# Comparative Analysis of Accelerated Resource-Adequacy Queues (ARQs)

> **A first-principles technical analysis of U.S. interconnection queues as financial instruments, quantifying the systemic risks of AI-driven load growth and capital repricing.**

---

## 📄 Overview

This repository contains the technical report **"Comparative Analysis of Accelerated Resource-Adequacy Queues,"** prepared by **Justin Candler** (Nous Enterprises LLC).

The U.S. electrical grid is facing a collision between antiquated interconnection procedures and an exponential rise in demand from AI data centers and electrification. This dissertation-level analysis argues that interconnection queues have evolved from administrative waiting lines into complex **financial instruments** that actively reprice the cost of capital for energy developers.

By analyzing queue designs across major ISOs (SPP, MISO, PJM, CAISO, ERCOT), this report quantifies how administrative choices—such as deposit structures, study cadences, and governance models—directly inflate the Weighted Average Cost of Capital (WACC) and transfer billions in costs to ratepayers.

## 🔑 Key Findings

The analysis moves beyond qualitative policy debate to provide hard numbers on the financial impact of queue design:

* **Capital Cost Repricing:** Fast-track queue designs shift project **WACC by 50–150 basis points**, inflating the Levelized Cost of Energy (LCOE) by **$3–$8/MWh**.
* **Ratepayer Impact:** The present value of systemic ratepayer impacts ranges from **$1.1 billion to $2.7 billion** across different RTOs over a 20-year horizon.
* **The AI-Grid Collision:** With AI data center load projected to grow by **+85% by 2030**, current queue structures risk "locking in" critical infrastructure delays in hubs like Northern Virginia and Texas.
* **Policy Efficiency:** The report identifies a "Pareto Frontier" of design, finding **SPP** and **MISO** models to be the most efficient at balancing speed and cost, while others incur high costs without proportional speed benefits.

## 📊 Methodology

This research employs a mixed-methodological approach bridging financial econometrics, queueing theory, and policy analysis:

1.  **Stochastic Financial Modeling:** Uses Monte Carlo simulations ($10^4$ draws) to model uncertainty in project cash flows, queue delays, and upgrade costs.
2.  **Elasticity-Weighted Divergence Score ($\mathcal{D}_i$):** A novel metric developed to quantify the "structural distance" of any queue program from a normative baseline.
3.  **Entropic Equity Metrics:** Introduces "Queue Survival Entropy" ($S_r$) to measure the fairness of queue access, distinguishing between "lottery-like" queues and deterministic gate-keeping.

## 📂 Repository Structure

```text
.
├── Comparative_Analysis_ARQ.pdf       # The full technical report
├── tex/
│   ├── main.tex                       # LaTeX source file
│   ├── references.bib                 # Bibliography
│   └── appendices/                    # Additional appendices (Risk, Climate, Security)
└── README.md                          # This file
