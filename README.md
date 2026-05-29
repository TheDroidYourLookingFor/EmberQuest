![EmberQuest](banner.svg)

# 🎮 EmberQuest | Old School MMO-inspired idle RPG

An Old School MMO-inspired idle/incremental RPG that runs in a single HTML file. No build step, no install, no server — open `index.html` in any modern browser and start adventuring.

**▶ Play it now: [thedroidyourlookingfor.github.io/EmberQuest](https://thedroidyourlookingfor.github.io/EmberQuest/)**

EmberQuest is a love-letter to classic MMOs: 16 races, 16 classes, 24 zones spanning the newbie fields to the endgame, a D&D-style six-ability-score system, a runeword crafting system, Alternate Ascension, prestige, mercenaries, pets, dungeons, and an auto-battle ("AFK") mode for when you'd rather watch your character grind than do it yourself.

## Features

**Classic character creation.** A guided three-step wizard: pick from 16 races (Human, Goliath, Aasimar, Wood/High/Dark/Half Elf, Dwarf, Troll, Ogre, Halfling, Gnome, Lizardfolk, Tabaxi, Bullywug, Dragonborn), then one of 16 classes (Warrior, Cleric, Paladin, Ranger, Death Knight, Druid, Monk, Bard, Rogue, Shaman, Necromancer, Wizard, Conjurer, Enchanter, Beastmaster, Berserker), then name your hero. Up to 24 character slots per account, and an optional **Hardcore (permadeath)** mode for those who like the stakes high.

**Six ability scores.** A D&D-style STR / DEX / CON / INT / WIS / CHA layer sits over the classic stats. Each class starts with a thematic spread that grows with level, and the ability modifiers feed real combat effects — Strength boosts attack, Dexterity adds crit and dodge, Constitution mitigates damage, Intelligence raises spell damage, Wisdom improves mana regen, and Charisma increases gold find. Gear and Alternate Ascension can raise your scores further.

**Combat.** Turn-based combat with HP, MP, attack, defense, weapon procs, item sets, and class-specific signature skills. Damage rolls, criticals, dodges, lifesteal, and a colored combat log for damage, heals, loot, and level-ups.

**24 zones.** From the Newbie Yard through Howlfang Burrow, Hollowmere Manor, Temple of Dread, the Abyss of Wrath, Vexgloom Labyrinth, Sythara Temple, Stormspire Bastion, and Ember Reach, all the way to the Citadel of Eternity and beyond. Each zone has its own mob roster, XP and gold multipliers, and a rare-drop chase item. Leveling is brisk early and deliberately slows past level 50 so the endgame has room to breathe.

**Loot, affixes, and item sets.** Random gear drops with prefix/suffix affix rolls — including the new D&D ability-score affixes — three-piece set bonuses, weapon procs, and rarity tiers up to Legendary. Equipment slots cover weapon, off-hand, chest, legs, feet, and charm.

**Runes and runewords.** Collect twelve runes (El, Tir, Tal, Ort, Sol, Dol, Kor, Bron, Lyr, Vald, Zhar, Morr) that drop in level-appropriate bands, and **choose exactly which owned rune to socket** into eligible gear. Discover and forge 17 runeword recipes — several of which grant special effects like crit, lifesteal, and gold/XP find on top of raw stats — and watch them evolve through five tiers with experience. Transmute lower runes upward when you need a specific one.

**Spellbook and spell gems.** Casters memorize spells into gem slots and meditate to recover mana, just like the source material. A clean Gem Loadout panel shows exactly what's ready to cast; the spell vendor and class epic reward fill out the rest. Each class gets a signature skill plus learned spells.

**Quests and elite hunt contracts.** Standard kill quests, a class epic quest with a legendary spell reward, and a rotating elite-contract system with chain tiers, cycles, and AFK pinning so your idle character keeps grinding the right target.

**Dungeons.** Delve a scaling dungeon with floor progression and selectable run modifiers for players who want a tougher, more focused grind than the open zones.

**Mercenaries, pets, and grouping.** Hire a contracted mercenary plus a roster of group mercenaries (paying upkeep over time), and issue a weapon to **each** of them to boost their damage. Tame pets that fight alongside you or grant passive bonuses. Group your own alternate characters together to share experience. Pets, mercenary weapons, and grouping all live on the **Group** tab.

**AFK / Auto-Battle.** Toggle AFK on and your character will auto-fight, auto-loot, auto-rest, auto-pot, and auto-buy supplies according to a goal (Balanced, XP, Gold, Loot). Configurable potion thresholds and skill priorities. Returning from a long offline session simulates the elapsed time.

**Alternate Ascension (AA).** Unlocks at level 51. Spend points on archetype trees (melee, hybrid, priest, caster), unique class nodes, a class capstone, and shared attribute nodes that raise your six ability scores. AA experience accrues slowly via a configurable XP-diversion slider.

**Prestige.** At level 100, prestige to reset progress in exchange for permanent perks.

**Shop, crafting, and refining.** A village merchant with tiered potions (Minor, Light, Greater, and Superior) that unlock and scale as you level, plus a crafting bench for runewords and salvage, a targeted reroll, an occultist reforge, and focused transmute recipes. Faction with the merchant shifts prices.

**Save management.** Multiple character slots, autosave to your browser, optional cloud sync via a signed-in account, manual save, and JSON export/import so you can back up your characters or move them between devices.

## Getting Started

**Just play in your browser:** [thedroidyourlookingfor.github.io/EmberQuest](https://thedroidyourlookingfor.github.io/EmberQuest/)

**Or run it locally:**

1. Clone or download this repo.
2. Open `index.html` in a browser (Chrome, Firefox, Safari, or Edge — anything recent).
3. (Optional) Create an account or sign in to enable cloud save sync across devices.
4. On the character-select screen, click any empty "Create a New Character" slot.
5. Pick a race, then a class, name your character, and enter the world.
6. Save data lives in your browser's localStorage (and the cloud, if signed in). Export to JSON from the topbar to back it up.

That's it. No npm install, no build, no server.

## Controls and Tips

- **Combat tab** is the main play view: see your current target, the combat log, and the manual Attack/Heal/Find Mob/Flee buttons.
- **Zones tab** is where you travel between hunting grounds — higher zones give more XP and gold but hit harder.
- **Inventory** opens the paperdoll and bags. Equip items, manage containers, and add sockets.
- **Runes tab** is where you socket chosen runes, forge runewords, and transmute.
- **Shop** is the village merchant. Buy tiered potions, gear, and containers. Sell junk in bulk.
- **Spells** is the spellbook and gem-slot manager, with a Gem Loadout panel — most relevant to caster classes.
- **Quests** holds your kill quests, class epic, and elite contracts; pin a contract here for AFK to chase.
- **Dungeon** lets you delve scaling floors with run modifiers.
- **Group** manages grouped alts, mercenaries, mercenary weapons, and pets.
- **AA** (Alternate Ascension) and **Prestige** tabs unlock at levels 51 and 100 respectively.
- **About** summarizes the game, credits, and links.
- **AFK panel** on the right configures your auto-battle behavior. Save and load named profiles to switch playstyles.

## Tech

- A single hand-written `index.html` (~16k lines, ~690 KB) containing the markup, CSS, and JavaScript inline. No dependencies, no framework, no build pipeline.
- Tabler Icons loaded from CDN for in-game iconography.
- State persists in your browser's `localStorage` (slot key `EmberQuest_slots`, shared bank under its own key), with optional cloud sync to a backend when you're signed in.
- Character avatars on the select screen are procedurally generated SVG keyed off the race config.
- The in-game UI is restyled to evoke classic 1990s MMO stone-panel windows: dark translucent panels with light bevels, gold serif titles, sunken bars, and bright-green stat readouts. A dedicated mobile layout is auto-detected on narrow screens.

## Compatibility

Any modern browser with `localStorage` and CSS gradient support — practically anything from the last decade. The interface adapts from a desktop three-column layout to a single-column, touch-friendly mobile layout (with safe-area handling) on phones and tablets.

## Saving and Backups

EmberQuest saves automatically to your browser's localStorage every few seconds, and to the cloud when you're signed in. **Clearing your browser data will erase local characters**, so use the **Export** button on the topbar to download a JSON backup. Drop the JSON back into the **Import** dialog to restore it on the same browser or a different one.

When importing, EmberQuest will offer to create a backup export of your current save first — leave that checkbox on unless you're sure.

## Roadmap

EmberQuest is a labor-of-love side project, so the roadmap is loose:

- More zones and a higher level cap
- A runeword discovery codex and still more runewords
- Guild simulation building on the existing group system
- Additional class epic-quest chains
- More elite contract and dungeon variants

## Credits and Inspiration

EmberQuest is a fan tribute to **Old School 1990s MMOs**, with mechanics, class fantasy, and visual style made in their spirit. Race names, the six ability scores, and much of the character flavor draw on tabletop **Dungeons & Dragons**.

UI icons from [Tabler Icons](https://tabler-icons.io/).

## License

GNU General Public License v3.0. See [LICENSE](LICENSE) for the full text.

In short: you're free to use, modify, and redistribute EmberQuest, but any distributed derivative must also be GPL-3.0 and ship its source.

## Contributing

Bug reports and PRs welcome. The codebase is a single HTML file, so most contributions are just CSS or JS additions inside the existing `<style>` and `<script>` blocks. Open an issue first if you're planning a larger feature so we can align on direction.
