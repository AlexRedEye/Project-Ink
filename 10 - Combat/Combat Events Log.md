---
type: system
domain: combat
---

# Combat Events Log

## Purpose
Combat emits events so UI and logging can subscribe without touching rules.

## MVP Events
- BattleStarted
- TurnStarted(actor)
- ActionChosen(actor, action)
- TargetSelected(targets)
- DamageDealt(actor, target, amount, effectiveness)
- Healed(actor, target, amount)
- StatusApplied(effect, target)
- UnitDefeated(unit)
- BattleEnded(winner)

## References
- Loop: [[10 - Combat/Battle Loop & Phases]]
- UI: [[50 - UI/Combat UI Flow]]
