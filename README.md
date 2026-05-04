# ✦ D&D 5e Spell Calculator

A browser-based spell management tool for **Dungeons & Dragons 5th Edition** — helps players pick, track, and organize their spells according to PHB rules, with automatic limit calculation per class and level.

🔗 **[Live demo →](https://alicetheowl.github.io/dnd-items-calculator/)** *(update link when deployed)*

---

## Features

- 🧙 **Character setup screen** — choose your class, level, and spellcasting ability modifier before you start
- ⚙️ **Three spellcasting mechanics** supported:
  - **Known** (Bard, Sorcerer, Warlock, Ranger) — tracks known spells with PHB limits
  - **Prepared** (Cleric, Druid, Paladin) — calculates max prepared spells from your level + modifier
  - **Spellbook** (Wizard) — tracks spells in the book separately from prepared ones, plus scroll bonuses
- 📖 **Full PHB spell database** — cantrips through level 9, covering all core classes (Bard, Cleric, Druid, Paladin, Ranger, Warlock, Wizard, Sorcerer)
- 🔍 **Search & filters** — filter by name, spell school, level tab, or component type (concentration, ritual, no material component)
- 📊 **Visual limit bars** — colour-coded progress bars warn you when you're approaching or exceeding your spell limits
- ✨ **"Always prepared" spells** — mark subclass/domain spells separately from your regular choices
- 📜 **Spell detail popup** — click any spell to see full description, components, duration, casting time, and range
- 📱 **Responsive** — works on mobile and desktop

---

## Supported Classes

| Class | Mechanic |
|---|---|
| Bard | Known |
| Cleric | Prepared |
| Druid | Prepared |
| Paladin | Prepared |
| Ranger | Known |
| Warlock | Known |
| Wizard | Spellbook |
| Sorcerer | Known |

---

## Usage

1. Open the page — you'll see the **character setup screen**
2. Pick your class (mechanics are auto-selected per PHB)
3. Enter your level and spellcasting modifier
4. Click **Начать ▶** to open the spell browser
5. Add spells using the buttons on each row — they'll appear in the selection panel on the right
6. The limit bars update live as you pick spells

---

## Tech stack

Pure HTML + CSS + JavaScript — no frameworks, no dependencies, no build step.

---

## License

MIT — free to use, fork, and adapt for your own campaigns.
