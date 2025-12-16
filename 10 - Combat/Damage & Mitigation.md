---
type: rules
domain: combat
---

# Damage & Mitigation

## MVP Formula (concept)
1. Start with `BaseDamage` (usually ATK or ability power)
2. Apply RPS modifier from [[10 - Combat/RPS Advantage System]]
3. Apply Guard reduction (if guarding)
4. Subtract DEF
5. Clamp minimum damage (>= 1)
6. Apply to HP

## Guard (MVP)
- Guard reduces incoming scaled damage (example: 50%)
- Guard expires when unit acts again (or at TurnStart)

## References
- Unit stats: [[20 - Data Models/Unit Model]]
- Statuses: [[10 - Combat/Status Effects System]]
