---
type: system
domain: combat
status: mvp
---

# AI Behavior

## Purpose
Enemy AI should feel intentional, not random,
while remaining simple and predictable.

---

## MVP AI Rules

### Action Selection Priority
1. Use Special if conditions are met
2. Guard if HP is low or threatened
3. Basic Attack otherwise

### Target Selection
- Prefer weakest valid target
- Respect targeting rules (taunt, frontline later)

---

## AI Design Principles
- No hidden information
- No perfect play
- AI should make “human-like” mistakes occasionally

---

## Difficulty Scaling (Later)
- Increase decision quality, not raw stats
- Add conditional logic per enemy archetype

---

## References
- Actions: [[10 - Combat/Actions System]]
- Targeting: [[10 - Combat/Targeting Rules]]
