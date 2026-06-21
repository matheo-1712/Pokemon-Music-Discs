<div align="center">

# 🎵 Pokémon Music Discs

**A Minecraft datapack & resourcepack** that adds **21 custom music discs** inspired by the Pokémon universe, all craftable in survival mode.

[![Minecraft](https://img.shields.io/badge/Minecraft-1.21-green?style=for-the-badge&logo=minecraft)](https://minecraft.net)
[![Cobblemon](https://img.shields.io/badge/Compatible-Cobblemon-blue?style=for-the-badge)](https://cobblemon.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

🌐 **[Version française → README.md](README.md)**

</div>

---

## 📋 Table of Contents

- [📦 Installation](#-installation)
- [🎮 Usage](#-usage)
- [🛠️ Crafting Recipes](#️-crafting-recipes)
- [🎵 Music List](#-music-list)
- [🗂️ Project Structure](#️-project-structure)
- [⚙️ Compatibility](#️-compatibility)
- [❓ Troubleshooting](#-troubleshooting)
- [👥 Contributors](#-contributors)

---

## 📦 Installation

> [!IMPORTANT]
> This pack serves **two roles** at once: a **resourcepack** (textures & sounds) and a **datapack** (recipes & functions). Both must be active for full functionality.

### Step 1 — Resourcepack

1. Place the `Cobblemon-RLM-music` folder into:
   ```
   .minecraft/resourcepacks/
   ```
   *(or into the `resourcepacks/` folder of your Modrinth profile)*
2. Launch Minecraft → **Options → Resource Packs** → enable `Cobblemon-RLM-music`

### Step 2 — Datapack

A symbolic link is already set up for you in the world folder. If you create a **new world**, copy the folder into:
```
saves/<world_name>/datapacks/
```
Then in-game:
```
/reload
```

### Step 3 — Verify

```
/datapack list
```
You should see: `[file/Pokemon-Music-Discs (world)]`

---

## 🎮 Usage

### Using a disc

1. Craft the desired disc (see [Crafting Recipes](#️-crafting-recipes))
2. **Right-click** a **Jukebox** with the disc in hand
3. The music plays 🎶

> [!TIP]
> You can stop the music by **right-clicking the Jukebox** with an empty hand.

---

## 🛠️ Crafting Recipes

> [!NOTE]
> All discs share the same crafting pattern: **8 Paper + 1 unique ingredient** in a crafting table (shapeless recipe — item order doesn't matter).

```
[ Paper ] [ Paper ] [ Paper ]
[ Paper ] [INGREDIENT] [ Paper ]
[ Paper ] [ Paper ] [ Paper ]
```

### Recipe Table

| 🎵 Disc | 🔑 Central Ingredient | 🎨 Theme |
|---|---|---|
| **Elsa Mina Battle** | `minecraft:packed_ice` | ❄️ Electric / Fairy |
| **Red's Theme** | `minecraft:red_dye` | 🔴 Legendary |
| **Timo's Battle** | `minecraft:white_dye` | ⚪ Battle |
| **Volo, The Seeker** | `minecraft:amethyst_shard` | 💜 Arceus / Hisui |
| **Cynthia Theme** | `minecraft:diamond` | 💎 Sinnoh Champion |
| **Corvault Battle** | `minecraft:echo_shard` | 🩵 Dragon |
| **Diantha's Challenge** | `minecraft:purple_dye` | 🌸 Kalos Champion |
| **DJM Dialga Final Theme** | `minecraft:clock` | 🕐 Time Legendary |
| **Final Boss (EV)** | `minecraft:nether_star` | ⭐ Final Boss |
| **Gladion's Battle** | `minecraft:black_dye` | ⚫ Alola Rival |
| **Guzma's Battle** | `minecraft:spider_eye` | 🕷️ Team Skull |
| **Gym Battle (SL)** | `minecraft:blaze_powder` | 🔥 Scarlet/Violet Gym |
| **Gym Battle (EB)** | `minecraft:gold_ingot` | 🟡 Sword/Shield Gym |
| **Iris The Champion** | `minecraft:dragon_breath` | 🐉 Unova Champion |
| **Jasmine's Battle** | `minecraft:pink_dye` | ⚙️ Steel |
| **Penny's Battle** | `minecraft:emerald` | 💚 Team Star |
| **Red & Blue's Theme** | `minecraft:lapis_lazuli` | 🔵 Legendary Rivals |
| **Team Star Battle** | `minecraft:coal` | ⭐ Team Star |
| **Ultra Necrozma** | `minecraft:glowstone_dust` | ✨ Ultra Space |
| **Travis's Battle** | `minecraft:honeycomb` | 🍯 Battle |
| **Zacian Illusion** | `minecraft:prismarine_crystals` | 🧊 Fairy |

---

## 🎵 Music List

<details>
<summary><b>📜 Show all 21 tracks</b></summary>

| # | English Name | French Name | Sound ID |
|---|---|---|---|
| 1 | Elsa Mina Battle | Elsa Mina Battle | `dp_music:elsa_mina_battle` |
| 2 | Red's Theme | Thème de Rouge | `dp_music:red_battle` |
| 3 | Timo's Battle | Combat de Timo | `dp_music:timmy_battle` |
| 4 | Volo, The Seeker | Volo, le Chercheur | `dp_music:volo_battle` |
| 5 | Cynthia Theme | Thème de Cynthia | `dp_music:cynthia_battle` |
| 6 | Corvault Battle | Corvault en Bataille | `dp_music:corvault_battle` |
| 7 | Diantha's Challenge | Le Défi de Dianthéa | `dp_music:dianthea_battle` |
| 8 | DJM Dialga Final Theme | DJM Dialga Thème Final | `dp_music:djm_dialga_final_theme` |
| 9 | Final Boss (EV) | Boss Final (EV) | `dp_music:final_boss_ev` |
| 10 | Gladion's Battle | Combat de Gladio | `dp_music:gladio_battle` |
| 11 | Guzma's Battle | Combat de Guzma | `dp_music:guzma_battle` |
| 12 | Gym Battle (SL) | Combat d'Arène (SL) | `dp_music:gym_battle_sl` |
| 13 | Gym Battle (EB) | Combat d'Arène (EB) | `dp_music:gym_battle_eb` |
| 14 | Iris The Champion | Iris, la Championne | `dp_music:iris_battle` |
| 15 | Jasmine's Battle | Combat de Jacinthe | `dp_music:jacinthe_battle` |
| 16 | Penny's Battle | Combat de Penny | `dp_music:penny_battle` |
| 17 | Red & Blue's Theme | Thème Rouge & Bleu | `dp_music:red_blue_battle` |
| 18 | Team Star Battle | Combat Team Star | `dp_music:teamstar_battle` |
| 19 | Ultra Necrozma | Ultra-Necrozma | `dp_music:ultranecrozma_battle` |
| 20 | Travis's Battle | Combat de Travis | `dp_music:travis_battle` |
| 21 | Zacian Illusion | L'Illusion de Zacian | `dp_music:zacian_illusion` |

</details>

---

## 🗂️ Project Structure

```
Cobblemon-RLM-music/
│
├── 📄 pack.mcmeta                    # Pack metadata (format 48)
│
├── 📁 assets/                        # Resourcepack
│   ├── 📁 minecraft/models/item/
│   │   └── music_disc_13.json        # custom_model_data overrides → models
│   ├── 📁 pokemon_disc/
│   │   ├── 📁 lang/
│   │   │   ├── en_us.json            # English translations
│   │   │   └── fr_fr.json            # French translations
│   │   ├── 📁 models/item/discs/     # 21 JSON models
│   │   └── 📁 textures/item/discs/   # 21 PNG textures (16×16)
│   └── 📁 rp_music/
│       ├── sounds.json               # Sound event declarations
│       └── 📁 sounds/records/        # .ogg audio files
│
└── 📁 data/                          # Datapack
    ├── 📁 dp_music/
    │   ├── 📁 functions/
    │   │   └── give_disc.mcfunction  # /function dp_music:give_disc
    │   └── 📁 jukebox_song/          # 22 jukebox song definitions
    └── 📁 pokemon_disc/
        └── 📁 recipe/                # 21 disc recipes + 1 skull recipe
```

---

## ⚙️ Compatibility

| Criteria | Value |
|---|---|
| **Minecraft Version** | `1.21` |
| **Loader** | Vanilla / Forge / Fabric / NeoForge |

---

## ❓ Troubleshooting

<details>
<summary><b>🔧 Crafting recipes don't work</b></summary>

1. Make sure the pack is placed in `saves/<world>/datapacks/`
2. Run `/reload` in-game
3. Check with `/datapack list` that `[file/Pokemon-Music-Discs (world)]` appears
4. Check the logs: `logs/latest.log`

</details>

<details>
<summary><b>🔇 Music doesn't play</b></summary>

1. Make sure the `Cobblemon-RLM-music` resourcepack is **enabled** in Options → Resource Packs
2. The pack may have been auto-disabled due to `pack_format` mismatch
3. Verify `assets/rp_music/sounds.json` exists
4. Test with `/playsound rp_music:corvault_battle record @p`

</details>

<details>
<summary><b>🏷️ Disc name shows raw key (<code>item.dp_music.xxx</code>)</b></summary>

The `minecraft:item_name` component in recipes must use this format:
```json
"minecraft:item_name": "{\"translate\":\"item.dp_music.xxx\"}"
```
Not just `"item.dp_music.xxx"` (literal string).

</details>

<details>
<summary><b>🎨 Textures are missing</b></summary>

1. Press **F3+T** to reload resource packs
2. Verify PNG files exist in `assets/pokemon_disc/textures/item/discs/`
3. Check that `assets/minecraft/models/item/music_disc_13.json` contains the `custom_model_data` overrides

</details>

---

## 👥 Contributors

<div align="center">

|                                             Avatar                                              |      Name       |     Role     |
|:-----------------------------------------------------------------------------------------------:|:---------------:|:------------:|
| <img src="https://github.com/matheo-1712.png" width="64" height="64" style="border-radius:50%"> | **matheo-1712** | ⚙️ Developer |

</div>

> [!NOTE]
> Want to contribute? Feel free to open a pull request or suggest new Pokémon music tracks!

---

<div align="center">

🌐 [Version française](README.md) · 📂 [Project Structure](#️-project-structure) · 🔝 [Back to top](#-pokémon-music-discs)

</div>
