# Actuary Skills Library

A collection of domain-specific skills, personas, and CLI tools designed to give AI coding agents actuarial expertise. 

These skills are optimized for **OpenClaw**, **Claude Code**, and **Cursor**, allowing AI assistants to act as pricing actuaries, reserving actuaries, IFRS 17 consultants, and more.

## Included Skills

### 📊 Pricing Actuary (`skills/pricing-actuary`)
Equips the AI with the ability to calculate pure premiums, apply loadings, and build pricing models.
- **Tools Included:** `scripts/premium_calculator.py` - Calculate pure vs gross premiums based on frequency, severity, and loading parameters.

### 💰 Reserving Actuary (`skills/reserving-actuary`)
Equips the AI to project future cash flows, handle IBNR claims, and use methods like Chain Ladder and Expected Loss Ratio.
- **Tools Included:** `scripts/chain_ladder.py` - Generate Age-to-Age (link) ratios and project Ultimate Claims and IBNR Reserves from a run-off triangle.

### 📋 IFRS 17 Specialist (`skills/ifrs17-specialist`)
Equips the AI to navigate the IFRS 17 standard, focusing on the General Measurement Model (GMM), PAA, and VFA.
- **Tools Included:** `scripts/csm_calculator.py` - Calculate Fulfillment Cash Flows (FCF), Risk Adjustment (RA), Initial CSM, and Loss Components for Onerous Contracts.

### 📉 Risk Management Actuary (`skills/risk-management-actuary`)
Equips the AI to calculate Economic Capital, Value at Risk (VaR), Conditional Tail Expectation (CTE), and perform Stochastic Monte Carlo simulations for ALM.
- **Tools Included:** `scripts/monte_carlo_var.py` - Simulates portfolio paths using Geometric Brownian Motion (GBM) to calculate empirical VaR and CTE.

### 🧬 Life Valuation Actuary (`skills/life-valuation-actuary`)
Equips the AI to calculate the present value of life insurance and annuities using standard decrement models (Mortality & Interest).
- **Tools Included:** `scripts/life_table_apv.py` - Calculates Actuarial Present Values (Term Life, Whole Life, Annuity Due) given a constant interest rate and mortality assumption.

## Installation (OpenClaw)

Clone this repository into your workspace, and copy the desired `SKILL.md` into your agent's knowledge base or load it contextually:

```bash
git clone https://github.com/muhammadilham1998-crypto/actuary-skills.git
```

## Example Usage

Run the Python pricing calculator tool directly:

```bash
python3 actuary-skills/skills/pricing-actuary/scripts/premium_calculator.py \
  --frequency 0.02 \
  --severity 50000 \
  --fixed-expense 150 \
  --variable-expense 0.20 \
  --profit-margin 0.10
```

Run the Monte Carlo VaR Calculator:
```bash
python3 actuary-skills/skills/risk-management-actuary/scripts/monte_carlo_var.py \
  --initial-value 1000000 \
  --drift 0.08 \
  --volatility 0.20 \
  --horizon 1.0 \
  --simulations 50000 \
  --confidence 0.99
```

## Contributing
This is a fresh repository built from scratch to explore AI-assisted actuarial modeling. Pull requests and feature suggestions (like adding new decrement models or stochastic ALM tools) are welcome!
