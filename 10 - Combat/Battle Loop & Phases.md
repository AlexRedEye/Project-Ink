---
type: system
domain: combat
---

# Battle Loop & Phases

## Battle Phases (State Machine)
1. **StartBattle**
2. **RoundStart**
3. **TurnStart**
4. **ChooseAction** (Player or AI)
5. **ChooseTarget**
6. **ResolveAction**
7. **TurnEnd**
8. **CheckEndBattle**
9. Loop → next actor / next round

## Notes
- Separate **selection** from **resolution** (modular UI, AI, autoplay).
- Emit combat events (see [[10 - Combat/Combat Events Log]]).
