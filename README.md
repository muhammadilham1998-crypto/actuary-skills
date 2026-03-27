# Actuary Skills Library

A collection of domain-specific skills, personas, and CLI tools designed to give AI coding agents actuarial expertise. 

These skills are optimized for **OpenClaw**, **Claude Code**, and **Cursor**, allowing AI assistants to act as pricing actuaries, reserving actuaries, or product developers.

## Included Skills

### 📊 Pricing Actuary (`skills/pricing-actuary`)
Equips the AI with the ability to calculate pure premiums, apply loadings, and build pricing models.
- **Tools Included:** `scripts/premium_calculator.py` - Calculate pure vs gross premiums based on frequency, severity, and loading parameters.

### 💰 Reserving Actuary (`skills/reserving-actuary`) *(Coming Soon)*
Equips the AI to project future cash flows, handle IBNR (Incurred But Not Reported) claims, and use methods like Chain Ladder.

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

## Contributing
This is a fresh repository built from scratch to explore AI-assisted actuarial modeling. Pull requests and feature suggestions (like adding new decrement models or IFRS 17 tools) are welcome!
