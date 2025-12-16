---
type: data-model
domain: combat
---

# Effect Model

## Purpose
Defines buffs, debuffs, and temporary modifiers.

---

## Core Fields
- effect_id
- name
- type (buff/debuff)
- duration
- stat_modifiers
- visual_tag (for UI)

---

## Behavior
- Effects tick at TurnStart
- Effects expire cleanly
- Effects emit add/remove events

---

## Constraints
- No permanent effects in MVP
- Effects should not directly deal damage

---

## References
- Statuses: [[10 - Combat/Status Effects System]]
- Events: [[10 - Combat/Combat Events Log]]
