---
type: data-model
domain: combat
---

# Unit Model

## Identity
- unit_id
- unit_name
- rarity (if needed later)

## Combat Stats
- HP / MaxHP
- ATK
- DEF
- SPD
- RPS Type: FORCE / GUARD / SKILL ([[10 - Combat/RPS Advantage System]])

## Runtime State
- current_hp
- guarding (bool)
- status_effects[] ([[10 - Combat/Status Effects System]])
- cooldowns/resources (if used later)

## Links
- Actions: [[10 - Combat/Actions System]]
- Math: [[10 - Combat/Damage & Mitigation]]
