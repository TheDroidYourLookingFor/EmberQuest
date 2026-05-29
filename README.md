![EmberQuest](banner.svg)

# 🎮 EmberQuest | EverQuest-inspired idle RPG

An EverQuest-inspired idle/incremental RPG that runs in a single HTML file. No build step, no install, no server — open `index.html` in any modern browser and start adventuring.

**▶ Play it now: [thedroidyourlookingfor.github.io/EmberQuest](https://thedroidyourlookingfor.github.io/EmberQuest/)**

EmberQuest is a love-letter to classic MMOs: 16 races, 16 classes, 19 zones spanning levels 1–88, a runeword crafting system, alternate advancement, prestige, and an auto-battle ("AFK") mode for when you'd rather watch your character grind than do it yourself.

## Features

**Classic character creation.** Pick from 16 races (Human, Goliath, Aasimar, Wood/High/Dark/Half Elf, Dwarf, Troll, Ogre, Halfling, Gnome, Lizardfolk, Tabaxi, Bullywug, Dragonborn) and 16 classes (Warrior, Cleric, Paladin, Ranger, Death Knight, Druid, Monk, Bard, Rogue, Shaman, Necromancer, Wizard, Conjurer, Enchanter, Beastmaster, Berserker). Up to 24 character slots per save..

**Combat.** Turn-based combat with HP, MP, attack, defense, weapon procs, item sets, and class-specific signature skills. Damage rolls, criticals, resists, and a colored combat log for damage, heals, loot, and level-ups.

**19 zones, level 1–88.** From the Newbie Yard through Blackburrow, Unrest Manor, Cazic-Thule, Plane of Hate, Mistmoore Catacombs, Plane of Storms, Plane of Fire, all the way to the Citadel of Eternity. Each zone has its own mob roster, XP and gold multipliers, and a rare-drop chase item.

**Loot, affixes, and item sets.** Random gear drops with prefix/suffix affix rolls, three-piece set bonuses, weapon procs, and rarity tiers. Equipment slots cover weapon, off-hand, chest, legs, feet, ring, and charm.

**Runes and runewords.** Collect runes (El, Tir, Tal, Ort, Sol, Dol), socket them into eligible gear, and discover runeword recipes that evolve through five tiers with experience. Transmute lower runes upward when you need a specific one.

**Spellbook and spell gems.** Casters memorize spells into gem slots and meditate to recover mana, just like the source material. Each class gets a signature skill plus learned spells.

**Quests and elite hunt contracts.** Standard kill quests, a class epic quest with a legendary spell reward, and a rotating elite-contract system with chain tiers, cycles, and AFK pinning so your idle character keeps grinding the right target.

**AFK / Auto-Battle.** Toggle AFK on and your character will auto-fight, auto-loot, auto-rest, auto-pot, and auto-buy supplies according to a goal (Balanced, XP, Gold, Loot). Configurable potion thresholds and skill priorities. Returning from a long offline session simulates the elapsed time.

**Alternate Advancement (AA).** Unlocks at level 51. Spend AA points on archetype trees (melee, tank, healer, caster), unique class nodes, and a class capstone.

**Prestige.** At level 100, prestige to reset progress in exchange for permanent perks.

**Shop, crafting, and refining.** A village merchant, a crafting bench for runewords and salvage, a targeted reroll, an occultist reforge, and focused transmute recipes. Faction with the merchant shifts prices.

**Save management.** Multiple character slots, autosave to localStorage, manual save, and JSON export/import so you can back up your characters or move them between devices.

## Getting Started

**Just play in your browser:** [thedroidyourlookingfor.github.io/EmberQuest](https://thedroidyourlookingfor.github.io/EmberQuest/)

**Or run it locally:**

1. Clone or download this repo.
2. Open `index.html` in a browser (Chrome, Firefox, Safari, or Edge — anything recent).
3. On the character-select screen, click any "Create a New Character" slot.
4. Pick a race, then a class, name your character, and enter the world.
5. Save data lives in your browser's localStorage. Export to JSON from the topbar to back it up.

That's it. No npm install, no build, no server.

## Controls and Tips

- **Combat tab** is the main play view: see your current target, the combat log, and the manual Attack/Heal/Find Mob/Flee buttons.
- **Zones tab** is where you travel between hunting grounds — higher zones give more XP and gold but hit harder.
- **Inventory** opens the paperdoll and bags. Drag items, equip them, install runes, and manage containers.
- **Shop** is the village merchant. Buy potions, gear, and containers. Sell junk in bulk.
- **Spells** is the spellbook and gem-slot manager — only visible to caster classes.
- **AA** and **Prestige** tabs unlock at levels 51 and 100 respectively.
- **AFK panel** on the right configures your auto-battle behavior. Save and load named profiles to switch playstyles.
- Set up an **AFK-pinned elite contract** on the Quests tab if you want auto-battle to chase a specific mob.

## Tech

- A single hand-written `index.html` (~10k lines, ~390 KB) containing the markup, CSS, and JavaScript inline. No dependencies, no framework, no build pipeline.
- Tabler Icons loaded from CDN for in-game iconography.
- All state persists in `localStorage` under the key `EmberQuest_slots`.
- Character avatars on the select screen are procedurally generated SVG keyed off the race config.
- The in-game UI is restyled to evoke the classic EverQuest stone-panel windows: dark translucent panels with light bevels, gold serif titles, sunken bars, and bright-green stat readouts.

## Compatibility

Any modern browser with `localStorage` and CSS gradient support — practically anything from the last decade. The UI is desktop-first but the character-select screen reflows on narrow viewports, and the in-game grid is responsive enough to play on a tablet.

## Saving and Backups

EmberQuest saves automatically to your browser's localStorage every few seconds. **Clearing your browser data will erase your characters**, so use the **Export** button on the topbar to download a JSON backup. Drop the JSON back into the **Import** dialog to restore it on the same browser or a different one.

When importing, EmberQuest will offer to create a backup export of your current save first — leave that checkbox on unless you're sure.

## Roadmap

EmberQuest is a labor-of-love side project, so the roadmap is loose:

- More zones beyond level 88
- More runewords and a runeword discovery codex
- Group/guild simulation
- Additional class epic-quest chains
- More elite contract variants

## Credits and Inspiration

EmberQuest is a fan tribute to **EverQuest** (1999, Verant Interactive / Sony Online Entertainment / Daybreak), with mechanics, race/class names, zone names, and visual style borrowed from the source material in the spirit of homage. It is not affiliated with or endorsed by the EverQuest IP holders.

UI icons from [Tabler Icons](https://tabler-icons.io/).

## License

GNU General Public License v3.0. See [LICENSE](LICENSE) for the full text.

In short: you're free to use, modify, and redistribute EmberQuest, but any distributed derivative must also be GPL-3.0 and ship its source.

## Contributing

Bug reports and PRs welcome. The codebase is a single HTML file, so most contributions are just CSS or JS additions inside the existing `<style>` and `<script>` blocks. Open an issue first if you're planning a larger feature so we can align on direction.
