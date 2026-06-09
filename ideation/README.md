<h1>IDEATION</h1>

---

**Contents**:

- [Feeback on Phase 1 to Work on](#feeback-on-phase-1-to-work-on)
  - [Questioning the Use of LLM](#questioning-the-use-of-llm)
  - [Terminology Revision](#terminology-revision)
  - [Need for Tighter Control in Financial Decision](#need-for-tighter-control-in-financial-decision)
  - [Potential Direction: Control-Tower Decisions](#potential-direction-control-tower-decisions)
- [Addressing Feedback on Phase 1](#addressing-feedback-on-phase-1)
  - [POINT: Terminology Revision](#point-terminology-revision)
  - [POINT: Need for Tighter Control in Financial Decisions](#point-need-for-tighter-control-in-financial-decisions)

---

# Feeback on Phase 1 to Work on
> **`phase-1` branch for reference**: [`phase-1`](https://github.com/warriorsofnoobia/dbx-agentic-ai-project--ideation/tree/phase-1)

## Questioning the Use of LLM
- Use of LLM for our use-case may not not ideal
- May be okay at a smaller scale, but is not scalable
- Time-series models may be better for forecasting purposes

## Terminology Revision
Terminology must be revised:

- Disruption
- Reasoning model

Align it with common technological use-cases.

## Need for Tighter Control in Financial Decision
Financial operations

=> Higher risk

=> More desire for control

*Hence, fully autonomous agent may be less favoured here.
*

## Potential Direction: Control-Tower Decisions
Potentially more valuable use-case:

*Automating warehouse control-tower decisions.*

# Addressing Feedback on Phase 1
## POINT: Terminology Revision

| Old Term | New Term(s) | Remarks/References |
| --- | --- | --- |
| Disruption | Supply Chain Disruption (SCD) | [*What is Supply Chain Disruption?*, **www.hyperbots.com/glossary**](https://www.hyperbots.com/glossary/supply-chain-disruption); this term covers: demand/supply shocks, transportation/logistical disruptions, natural disaster-related disruption, etc. |
| Reasoning Model | Reasoning Model | This is the correct term, but for clarity, it is better to specify its subcategories: predictive model, LLM. The "AI agent" is the overall system that consists of reasoning model(s) and tool-calling capabilities. |

## POINT: Need for Tighter Control in Financial Decisions
**Suggested approach**:

For ensuring tight governance of decision-making format, constraint definition and constraint fulfillment, we have established a separation between the AI layer and the programmatic layer (see: ).