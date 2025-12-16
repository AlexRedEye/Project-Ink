---
type: system
domain: combat
status: mvp
---

# Status Effects System

## Purpose
Status effects modify combat flow without rewriting core rules.
They are additive, temporary, and readable.

## MVP Status Categories
- **Buffs** (positive)
- **Debuffs** (negative)

No damage-over-time or stacking complexity in MVP unless required.

---

## MVP Status Effects

### Guarded
- Applied via **Guard action**
- Reduces incoming damage
- Removed at start of unit’s next turn

### Weakened
- Reduces outgoing damage
- Duration: 1–2 turns

### Fortified
- Increases DEF or damage reduction
- Duration-based

---

## Status Rules
- Statuses have:
  - duration (turn-based)
  - source (unit/action)
- Statuses tick at **TurnStart**
- Expired statuses are removed before action selection

---

## Design Constraints
- No permanent status effects
- No stacking same-name effects (refresh instead)
- All effects must be explainable in one sentence

---

## References
- Loop: [[10 - Combat/Battle Loop & Phases]]
- Math: [[10 - Combat/Damage & Mitigation]]
- Data: [[20 - Data Models/Effect Model]]
