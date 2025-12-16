---
type: data-model
domain: combat
---

# Action Model

## Purpose
Actions are **data-driven behaviors** executed by the combat engine.

---

## Core Action Fields
- action_id
- name
- description
- target_type (enemy, ally, self)
- tags (damage, heal, buff, etc.)
- resource_cost (optional)

---

## Execution Flow
1. CanExecute(actor, context)
2. GetValidTargets()
3. Execute()
4. Emit combat events

---

## MVP Action Types
- Basic Attack
- Guard
- Character Special

---

## References
- Loop: [[10 - Combat/Battle Loop & Phases]]
- Targeting: [[10 - Combat/Targeting Rules]]
- Resolver: [[10 - Combat/Damage & Mitigation]]
