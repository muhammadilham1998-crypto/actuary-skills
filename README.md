# Actuary Skills Library

A collection of domain-specific skills, personas, and CLI tools designed to give AI coding agents actuarial expertise. 

These skills are optimized for **OpenClaw**, **Claude Code**, and **Cursor**, allowing AI assistants to act as pricing actuaries, reserving actuaries, IFRS 17 consultants, and more.

## Included Skills

### 📊 Pricing Actuary (`skills/pricing-actuary`)
Equips the AI with the ability to calculate pure premiums, apply loadings, and build pricing models.
- **Tools Included:** `scripts/premium_calculator.py` - Calculate pure vs gross premiums based on frequency, severity, and loading parameters.

### 💰 Reserving Actuary (`skills/reserving-actuary`)
Equips the AI to project future cash flows, handle IBNR (Incurred But Not Reported) claims, and use methods like Chain Ladder and Expected Loss Ratio.
- **Tools Included:** `scripts/chain_ladder.py` - Generate Age-to-Age (link) ratios and project Ultimate Claims and IBNR Reserves from a run-off triangle.

### 📋 IFRS 17 Specialist (`skills/ifrs17-specialist`)
Equips the AI to navigate the IFRS 17 standard, focusing on the General Measurement Model (GMM), PAA, and VFA.
- **Tools Included:** `scripts/csm_calculator.py` - Calculate Fulfillment Cash Flows (FCF), Risk Adjustment (RA), Initial CSM, and Loss Components for Onerous Contracts.

## Installation (OpenClaw)

Clone this repository into your workspace, and copy the desired `SKILL.md` into your agent's knowledge base or load it contextually:

```bash
git clone https://github.com/muhammadilham1998-crypto/actuary-skills.git
```

## Example Usage

Run the Python reserving calculator tool directly with JSON run-off triangle data:

```bash
python3 actuary-skills/skills/reserving-actuary/scripts/chain_ladder.py \
  --json-data '[[100, 150, 175, 180], [110, 168, 192, null], [115, 176, null, null], [122, null, null, null]]'
```

Run the IFRS 17 Initial CSM Calculator:
```bash
python3 actuary-skills/skills/ifrs17-specialist/scripts/csm_calculator.py \
  --pv-premiums 150000 \
  --pv-claims 110000 \
  --pv-expenses 15000 \
  --risk-adj 5000
```

## Contributing
This is a fresh repository built from scratch to explore AI-assisted actuarial modeling. Pull requests and feature suggestions (like adding new decrement models or stochastic Monte Carlo tools) are welcome!
