# Upstate Diner Dash — Platformer Game Design Plan

## Concept Overview

**Title:** _Upstate Diner Dash_
**Genre:** 2D Side-Scrolling Platformer
**Setting:** A beloved, retro diner tucked along Route 9 in upstate New York — think vinyl booths, chrome counter stools, a crackling jukebox, and hand-painted specials on the chalkboard.
**Tone:** Warm, nostalgic, slightly quirky. Think Edward Hopper meets Earthbound.

---

## Story

You play as **Casey**, a local kid who grew up spending every weekend at **Mel's Silver Spoon Diner** — the heart of their small upstate town. One autumn evening, the diner is struck by a freak storm that scatters magical "memory tokens" (old coins, jukebox slugs, diner receipts) across five surreal, dreamlike versions of the diner and surrounding town.

Casey must platform through each level to recover the tokens and restore the diner — and the community memories tied to it — before the storm washes everything away.

---

## Core Gameplay

### Movement & Mechanics
- Standard platformer controls: run, jump, double-jump (off a stool or booth seat)
- **Slide** under counters and through service hatches
- **Tray Balance** mechanic: carry a diner tray to unlock certain paths; dropping it alerts enemies
- **Jukebox Power-Up:** collect a jukebox slug to enter a brief speed/invincibility mode synced to a musical sting

### Collectibles
| Item | Effect |
|---|---|
| Memory Tokens | Primary collectible, needed to unlock next level |
| Coffee Cups | Temporary speed boost |
| Pie Slices | Health restore |
| Jukebox Slugs | Activate power-up |
| Napkin Notes | Unlock lore / story snippets |

---

## Levels (5 Worlds)

### World 1 — The Diner (Normal)
The real diner before the storm. Tutorial level. Meet regulars: Gus the cook, Dottie the waitress, Earl the booth-potato.
- **Platforms:** counter stools, booths, shelving units, pie display cases
- **Hazards:** spilled coffee puddles (slippery), swinging kitchen doors
- **Boss:** A runaway dessert cart rolling back and forth across the counter

---

### World 2 — The Flooded Diner
The storm has pushed the Hudson River into the diner. Everything is waist-deep in water, with rising tides.
- **Platforms:** floating menus, overturned trays, bobbing salt shakers
- **Hazards:** river current sweeping items, electrical sparks from submerged appliances
- **Enemy:** Snapping turtles wearing little paper hats
- **Boss:** A giant catfish that swallowed the jukebox (it still plays music from inside)

---

### World 3 — Neon Night Diner
A retro-futuristic, neon-soaked version. The diner exists at permanent midnight in 1958. Everything glows.
- **Platforms:** neon sign letters (jump across "MEL'S"), chrome fixtures, spinning bar stools
- **Hazards:** flickering neon that temporarily blacks out sections of the level
- **Enemy:** Grease-slick shadows shaped like classic diner appliances
- **Boss:** The Jukebox itself — it's sentient, angry, and plays increasingly difficult attack patterns tied to song tempo

---

### World 4 — Autumn Harvest Diner (Outdoor / Rooftop)
The diner has magically expanded onto the roof and into the surrounding upstate foliage. Maple trees, apple orchards, corn mazes spill out around the building.
- **Platforms:** tree branches, hay bales, tractor hoods, scarecrow arms
- **Hazards:** falling leaves that obscure vision, wind gusts, bees from an apple tree hive
- **Enemy:** Crows wearing tiny chef hats, dive-bombing Casey
- **Boss:** A giant pumpkin that rolls across the platform like a boulder

---

### World 5 — Memory Diner (Final)
A shimmering, half-real dreamscape stitched together from everyone's memories of the diner. Platforms flicker in and out of existence. Old photos from the diner walls come to life.
- **Platforms:** Memory fragments (glowing photo snapshots), floating booth cushions, ghostly counter
- **Hazards:** Forgetting zones — sections that erase your recent progress if touched
- **Enemy:** Memory Shadows — corrupted versions of the diner regulars
- **Boss:** The Storm itself, manifested as a swirling entity made of lost receipts, menus, and torn photographs

---

## Characters

| Character | Role |
|---|---|
| Casey | Player character — agile, determined, loves pie |
| Mel | The diner owner — gives Casey upgrades between worlds |
| Gus | The cook — teaches tray-carrying mechanics |
| Dottie | Waitress — hints at hidden collectible locations |
| Earl | Grumpy regular — optional challenge giver |

---

## Visual Style

- **Art Direction:** Pixel art, warm palette of amber, cream, turquoise, and cherry red
- **Backgrounds:** Hand-illustrated scrolling backgrounds — Catskill mountains, Hudson River, autumn foliage, Route 9 strip
- **UI:** Designed like a diner menu — health bar is a coffee cup fill level, score is "Today's Special" ticker

---

## Audio

- **Soundtrack:** Lo-fi jazz and doo-wop instrumentals per level; boss fights escalate to big band swing
- **SFX:** Sizzling grills, jukebox stings, coffee pours, silverware clinks
- **Voice:** Light, expressive grunts and sound effects only (no full VO)

---

## Tech Stack (Recommended)

| Component | Choice |
|---|---|
| Engine | Godot 4 (free, Python-like GDScript, great 2D support) |
| Art | Aseprite for pixel art |
| Audio | LMMS or GarageBand for soundtrack |
| Version Control | Git + GitHub |
| Export Targets | Web (itch.io), Windows, Mac |

---

## Development Phases

### Phase 1 — Prototype (4–6 weeks)
- [ ] Basic player movement, jump, slide
- [ ] One test level (World 1 layout)
- [ ] Collectible system (tokens, coffee)
- [ ] Basic enemy with patrol AI

### Phase 2 — Core Worlds (8–10 weeks)
- [ ] All 5 worlds built and playable
- [ ] All bosses implemented
- [ ] Tray balance mechanic
- [ ] Jukebox power-up

### Phase 3 — Polish (4–6 weeks)
- [ ] Full audio pass
- [ ] Cutscenes / story moments between worlds
- [ ] Save system
- [ ] Accessibility options (colorblind mode, control remapping)

### Phase 4 — Launch
- [ ] Playtesting & bug fixes
- [ ] Build for web + desktop
- [ ] Publish on itch.io

---

## Inspiration / References

- **Platformers:** Celeste, A Hat in Time, Shovel Knight
- **Tone/Aesthetic:** Night in the Woods, Earthbound, Diner Dash
- **Setting:** Edward Hopper's _Nighthawks_, upstate NY Route 9 diners, Catskill Mountain region

---

> _"Every town has a diner. Not every diner has magic."_
