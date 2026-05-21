# UK MOB Builderbot Assistant

This repository documents four Builderbot agents used by the UK Clearpay Merchant Onboarding team in Slack.

## Agents

| Agent | Purpose |
|---|---|
| [Rolling Reserve Calculator](agents/rolling-reserve-calculator.md) | Extracts fulfilment breakdowns and calculates rolling reserve outputs. |
| [Merchant Eligibility Assistant](agents/merchant-eligibility-assistant.md) | Provides policy-aligned second opinions on merchant vertical, business attributes, risk rating, and eligibility. |
| [Merchant Due Diligence](agents/merchant-due-diligence.md) | Fetches Trustpilot, WHOIS, and fulfilment indicators for merchant domains. |
| [Proof of Inventory Checker](agents/proof-of-inventory-checker.md) | Reviews merchant Proof of Inventory documents against onboarding requirements and flags dropshipping or suspicious indicators. |

## Usage

Each file in the `agents/` directory contains the prompt/canvas for a Builderbot agent. These are intended for internal operational use by the Merchant Onboarding team.

## Notes

- These agents may include internal policy guidance and escalation instructions.
- Agent outputs should follow the exact response formats defined in each file.
- Pricing, reserve terms, and sensitive risk methodology should not be disclosed to merchants unless explicitly allowed by policy.
