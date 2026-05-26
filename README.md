# ⚡ Jujutsu Battlegrounds

A mobile-based multiplayer fighting game inspired by **Jujutsu Kaisen** and **Roblox Strongest Battlegrounds**.

## 🎮 Features

✅ **5-10 JJS Characters** - Each with 5 unique moves  
✅ **Black Flash Chains** - Timed perfect attacks for damage multipliers  
✅ **Combo System** - Rapid clicks for extended combos  
✅ **Mobile Controls** - Block, Hit, Dash, R (Special)  
✅ **Boss Battles** - 2-3 epic boss encounters  
✅ **Open World PvP** - Meet players and clash/brawl  
✅ **Emote Rewards** - 1 emote per 20 kills  
✅ **AI Boss System** - Dynamic attack patterns  

## 📁 Project Structure

```
Jujitsu-battlegrounds-/
├── README.md
├── config.lua              # Game configuration
├── src/
│   ├── characters/
│   │   ├── character_base.lua      # Base character class
│   │   ├── yuji_itadori.lua        # Character templates
│   │   ├── megumi_fushiguro.lua
│   │   ├── nobara_kugisaki.lua
│   │   ├── satoru_gojo.lua
│   │   └── ryomen_sukuna.lua
│   ├── combat/
│   │   ├── combo_system.lua        # Combo mechanics
│   │   ├── black_flash.lua         # Perfect timing system
│   │   └── damage_calculator.lua   # Damage formulas
│   ├── bosses/
│   │   ├── boss_base.lua           # Base boss class
│   │   ├── mahito_boss.lua         # Boss AI patterns
│   │   ├── jogo_boss.lua
│   │   └── sukuna_boss.lua
│   ├── ui/
│   │   ├── mobile_buttons.lua      # Mobile controls
│   │   ├── emote_system.lua        # Emotes UI
│   │   └── hud.lua                 # Game HUD
│   ├── multiplayer/
│   │   ├── matchmaking.lua         # PvP pairing
│   │   ├── brawl_system.lua        # Clash/brawl logic
│   │   └── world.lua               # Open world
│   └── main.lua                    # Entry point
└── docs/
    └── GAME_GUIDE.md               # Player guide
```

## 🕹️ Mobile Controls

| Button | Action |
|--------|--------|
| **Hit** | Basic attack (rapid click for combos) |
| **Block** | Reduce incoming damage |
| **Dash** | Dodge/move away |
| **R (Special)** | Use special ability |

## ⚡ Black Flash System

Perfect timed attacks trigger **Black Flash**:
- Deal **2x damage**
- Extend combo chain
- Build toward ultimate ability
- Visual/audio feedback on success

## 👥 Characters (5-10)

- **Yuji Itadori** - Balanced fighter
- **Megumi Fushiguro** - Shadow manipulator
- **Nobara Kugisaki** - Ranged attacker
- **Satoru Gojo** - Defensive specialist
- **Ryomen Sukuna** - High damage dealer
- *More characters coming soon...*

## 🔥 Bosses (2-3)

- **Mahito** - Transformation abilities
- **Jogo** - Fire domain specialist
- **Sukuna** - Ultimate boss fight

## 🎁 Reward System

- **Kills** → Progress toward emotes
- **Every 20 kills** → Unlock new emote
- **Bosses defeated** → Special rewards
- **PvP wins** → Ranked rewards

## 📖 Documentation

See `docs/GAME_GUIDE.md` for:
- Detailed mechanics
- Character guides
- Combat tips
- Combo tutorials

## 🚀 Getting Started

1. Load the game in Roblox Studio
2. Run `main.lua`
3. Select a character
4. Choose: Boss fight, PvP brawl, or Free roam
5. Master the Black Flash timing!

## 💡 Tips

- **Combos**: Rapid clicks = extended damage chains
- **Black Flash**: Time your attacks perfectly for 2x damage
- **Block**: Use wisely (drains mana)
- **Dash**: Escape dangerous situations
- **Emotes**: Flex after 20 kills! 😎

---

**Made with ❤️ for JJS fans**
