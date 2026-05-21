# UK MOB Builderbot Assistant

This repository documents four Builderbot agents used by the UK Clearpay Merchant Onboarding team in Slack.

## Agents

| Agent | Documentation | Raw Builderbot Prompt | Purpose |
|---|---|---|---|
| Rolling Reserve Calculator | [Docs](agents/rolling-reserve-calculator.md) | [Prompt](prompts/rolling-reserve-calculator.prompt.md) | Extracts fulfilment breakdowns and calculates rolling reserve outputs. |
| Merchant Eligibility Assistant | [Docs](agents/merchant-eligibility-assistant.md) | [Prompt](prompts/merchant-eligibility-assistant.prompt.md) | Provides policy-aligned second opinions on merchant vertical, business attributes, risk rating, and eligibility. |
| Merchant Due Diligence | [Docs](agents/merchant-due-diligence.md) | [Prompt](prompts/merchant-due-diligence.prompt.md) | Fetches Trustpilot and fulfilment indicators for merchant domains. |
| Proof of Inventory Checker | [Docs](agents/proof-of-inventory-checker.md) | [Prompt](prompts/proof-of-inventory-checker.prompt.md) | Reviews merchant Proof of Inventory documents against onboarding requirements and flags dropshipping or suspicious indicators. |

## Repository Structure

- `agents/` contains cleaned, maintainable documentation for each Builderbot agent.
- `prompts/` contains the raw prompt text used by Builderbot when answering queries.

## Usage

Use the files in `prompts/` when copying prompt text into Builderbot. Use the files in `agents/` when reviewing, maintaining, or discussing the agent logic.

## Notes

- These agents may include internal policy guidance and escalation instructions.
- Agent outputs should follow the exact response formats defined in each file.
- Pricing, reserve terms, and sensitive risk methodology should not be disclosed to merchants unless explicitly allowed by policy.
