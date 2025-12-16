---
type: system
domain: combat
---

# Actions System

## MVP Action Set
- **Basic Attack**
- **Guard**
- **Special** (character-specific)

## Action Architecture (modular)
Actions should be data-driven via [[20 - Data Models/Action Model]] and resolved by [[10 - Combat/Damage & Mitigation]].

### Action lifecycle
1. `CanExecute(actor, ctx)`
2. `GetValidTargets(actor, ctx)` → [[10 - Combat/Targeting Rules]]
3. `Execute(actor, targets, ctx)` → emits events

## Action Tags (for scaling)
- SingleTarget / AoE
- Damage / Heal / Buff / Debuff
- GeneratesResource / ConsumesResource
- RequiresCondition

## References
- Loop: [[10 - Combat/Battle Loop & Phases]]
- Events: [[10 - Combat/Combat Events Log]]
