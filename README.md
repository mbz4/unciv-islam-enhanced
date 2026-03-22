# Islam Enhanced

An [Unciv](https://github.com/yairm210/Unciv) extension mod that replaces the pick-and-mix belief system with a thematically coherent set of Islamic beliefs, all stacking on the Mosque building.

## Why

Unciv treats religions as empty containers you fill with generic mechanics. This feels odd when the religion already has a defined creed. This mod makes the "correct" choice for each belief slot self-evident — you still go through the picker (engine limitation), but every option maps onto an actual Islamic concept.

## Beliefs

| Slot | Name | Concept | Key effects |
|-----------|-----------------|----------------------|------------------------------------------|
| Pantheon | Tawhid | Oneness of God | Faith, Happiness, Culture from Shrines |
| Founder | Zakat | Obligatory almsgiving | Gold + Happiness per follower city |
| Follower | Five Pillars | The five obligations | Unlocks Mosque for faith purchase; Food, Happiness, Culture from Mosques |
| Follower | Bayt al-Hikmah | Scholarship | Science + Faith from Mosques; Science + Culture from Libraries |
| Enhancer | Da'wah | Invitation / outreach | Faster spread; Faith + Happiness per follower city |

**Pick order:** Five Pillars first (founding) to unlock Mosque purchase, then Bayt al-Hikmah (enhancement) to layer scholarship bonuses onto it.

## Installation

1. In-game: **Mods → Download mod from URL** → paste this repo's URL.
2. Manual: clone/download into your Unciv `mods/` directory.
3. Enable the mod, start a new game with Religion enabled, found Islam.

## Notes

- Beliefs are intentionally stronger than vanilla — the tradeoff for losing strategic flexibility.
- Run `Options → Locate mod errors` on first load; Unciv is strict about unique string syntax and will flag anything that needs adjusting.
- Unciv's parser accepts `//` comments in JSON. If a future version drops this, strip them from `Beliefs.json`.
- The mod ships without a custom icon; Unciv's base game already includes Islam with a crescent icon.

## Licence

Apache License 2.0 — see [LICENSE](LICENSE).
