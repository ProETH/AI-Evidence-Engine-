# AI Evidence Engine

AI Evidence Engine is an explainable AI Trading Skill designed for the CoinW AI Trading Skill Challenge.

Instead of making trading decisions based on a single indicator, AI Evidence Engine evaluates multiple independent evidence sources, validates their quality, dynamically adjusts their importance, and generates an explainable trading recommendation with a measurable confidence score.

The objective is not simply to produce Buy or Sell signals, but to answer the most important question:

> **Is there enough reliable evidence to justify this trade?**

---

# Why AI Evidence Engine?

Most trading systems rely on one or two indicators.

AI Evidence Engine follows a different philosophy.

Every trading decision should be supported by multiple independent evidence sources before an AI Agent executes an order.

The framework improves transparency, explainability, and risk awareness while remaining flexible across different market conditions.

---

# Core Features

- Multi-Evidence Trading Framework
- Explainable AI Decisions
- Dynamic Evidence Weighting
- Asset-Specific Adaptation
- AI Agent Compatible
- Risk-Aware Decision Process
- Transparent Confidence Score

---

# Evidence Sources

Current version supports evaluation of:

- Capital Commitment
- Spot Volume
- Open Interest
- Funding Rate
- Whale Activity
- Liquidity Quality
- Token Events
- Market Trend

Additional evidence modules can be integrated in future releases.

---

# AI Decision Workflow

```
Market Data
      │
      ▼
Evidence Collection
      │
      ▼
Evidence Validation
      │
      ▼
Dynamic Weighting
      │
      ▼
Confidence Calculation
      │
      ▼
Explainable AI Decision
```

---

# Example Output

```
Decision:
BUY

Evidence Score:
89 / 100

Data Quality:
93%

Decision Confidence:
91%

Evidence Summary:

✓ Capital Commitment confirmed

✓ Spot Volume confirmed

✓ Open Interest increasing

✓ Healthy Funding Rate

✓ Whale accumulation detected

✓ No critical token unlock
```

---

# Why Dynamic Weighting?

Different assets behave differently.

For example:

- Bitcoin and Ethereum typically rely more on derivatives confirmation such as Open Interest and Funding Rate.

- Small-cap assets may rely more heavily on Capital Commitment, Whale Activity, and Token Events.

Instead of using fixed rules, AI Evidence Engine allows AI Agents to dynamically adjust evidence importance according to market structure, liquidity, volatility, and asset characteristics.

---

# Repository Structure

```
AI-Evidence-Engine
│
├── README.md
├── SKILL.md
├── LICENSE
└── examples
    └── example.md
```

---

# Future Roadmap

Future versions may include:

- On-chain analytics
- Developer activity
- AI News analysis
- Cross-exchange capital flow
- Portfolio-level evidence
- Adaptive evidence learning

---

# Disclaimer

This project is provided for educational and demonstration purposes only as part of the CoinW AI Trading Skill Challenge.

It does not constitute investment advice, financial advice, or a recommendation to buy or sell any digital asset.

Users should always conduct independent research and apply appropriate risk management before making trading decisions. 
