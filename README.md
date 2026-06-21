<div align="center">

# 🎵 Pokémon Music Discs

**Un datapack & resourcepack Minecraft** qui ajoute **21 disques de musique** personnalisés inspirés de l'univers Pokémon, craftables en survie.

[![Minecraft](https://img.shields.io/badge/Minecraft-1.21-green?style=for-the-badge&logo=minecraft)](https://minecraft.net)
[![Cobblemon](https://img.shields.io/badge/Compatible-Cobblemon-blue?style=for-the-badge)](https://cobblemon.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

🌐 **[English version → README_EN.md](README_EN.md)**

</div>

---

## 📋 Sommaire

- [📦 Installation](#-installation)
- [🎮 Utilisation](#-utilisation)
- [🛠️ Crafts des disques](#️-crafts-des-disques)
- [🎵 Liste des musiques](#-liste-des-musiques)
- [🗂️ Structure du projet](#️-structure-du-projet)
- [⚙️ Compatibilité](#️-compatibilité)
- [❓ Dépannage](#-dépannage)
- [👥 Contributeurs](#-contributeurs)

---

## 📦 Installation

> [!IMPORTANT]
> Ce pack remplit **deux rôles** simultanément : **resourcepack** (textures & sons) et **datapack** (recettes & fonctions). Les deux doivent être actifs pour un fonctionnement complet.

### Étape 1 — Resourcepack

1. Placez le dossier `Cobblemon-RLM-music` dans :
   ```
   .minecraft/resourcepacks/
   ```
   *(ou dans le dossier `resourcepacks/` de votre profil Modrinth)*
2. Lancez Minecraft → **Options → Resource Packs** → activez `Cobblemon-RLM-music`

### Étape 2 — Datapack

Un lien symbolique est déjà créé pour vous dans le monde. Si vous créez un **nouveau monde**, copiez le dossier dans :
```
saves/<nom_du_monde>/datapacks/
```
Puis en jeu :
```
/reload
```

### Étape 3 — Vérification

```
/datapack list
```
Vous devriez voir : `[file/Pokemon-Music-Discs (world)]`

---

## 🎮 Utilisation

### Utiliser un disque

1. Craftez le disque souhaité (voir la section [Crafts des disques](#️-crafts-des-disques))
2. Faites un **clic droit** sur un **Jukebox** avec le disque
3. La musique se lance 🎶

> [!TIP]
> Vous pouvez interrompre la musique en faisant un **clic droit sur le Jukebox** avec la main vide.

---

## 🛠️ Crafts des disques

> [!NOTE]
> Tous les disques se craftent de la même façon : **8 Papiers + 1 ingrédient unique** dans une table de craft (recette sans forme — l'ordre des items n'a pas d'importance).

```
[ Papier ] [ Papier ] [ Papier ]
[ Papier ] [INGRÉDIENT] [ Papier ]
[ Papier ] [ Papier ] [ Papier ]
```

### Tableau des recettes

| 🎵 Disque | 🔑 Ingrédient central | 🎨 Thème |
|---|---|---|
| **Elsa Mina Battle** | `minecraft:packed_ice` | ❄️ Électrik / Fée |
| **Red's Theme** | `minecraft:red_dye` | 🔴 Légendaire |
| **Timo's Battle** | `minecraft:white_dye` | ⚪ Combat |
| **Volo, The Seeker** | `minecraft:amethyst_shard` | 💜 Arceus / Hisui |
| **Cynthia Theme** | `minecraft:diamond` | 💎 Championne Sinnoh |
| **Corvault Battle** | `minecraft:echo_shard` | 🩵 Dragon |
| **Diantha's Challenge** | `minecraft:purple_dye` | 🌸 Championne Kalos |
| **DJM Dialga Final Theme** | `minecraft:clock` | 🕐 Légende Temporelle |
| **Final Boss (EV)** | `minecraft:nether_star` | ⭐ Boss Final |
| **Gladion's Battle** | `minecraft:black_dye` | ⚫ Rival Alola |
| **Guzma's Battle** | `minecraft:spider_eye` | 🕷️ Team Skull |
| **Gym Battle (SL)** | `minecraft:blaze_powder` | 🔥 Arène Écarlate/Violet |
| **Gym Battle (EB)** | `minecraft:gold_ingot` | 🟡 Arène Épée/Bouclier |
| **Iris The Champion** | `minecraft:dragon_breath` | 🐉 Championne Unys |
| **Jasmine's Battle** | `minecraft:pink_dye` | ⚙️ Acier |
| **Penny's Battle** | `minecraft:emerald` | 💚 Team Star |
| **Red & Blue's Theme** | `minecraft:lapis_lazuli` | 🔵 Rivaux Légendaires |
| **Team Star Battle** | `minecraft:coal` | ⭐ Team Star |
| **Ultra Necrozma** | `minecraft:glowstone_dust` | ✨ Ultra-Espace |
| **Travis's Battle** | `minecraft:honeycomb` | 🍯 Combat |
| **Zacian Illusion** | `minecraft:prismarine_crystals` | 🧊 Féerique |

---

## 🎵 Liste des musiques

<details>
<summary><b>📜 Voir les 21 musiques disponibles</b></summary>

| # | Nom (FR) | Nom (EN) | Sound ID |
|---|---|---|---|
| 1 | Elsa Mina Battle | Elsa Mina Battle | `dp_music:elsa_mina_battle` |
| 2 | Thème de Rouge | Red's Theme | `dp_music:red_battle` |
| 3 | Combat de Timo | Timo's Battle | `dp_music:timmy_battle` |
| 4 | Volo, le Chercheur | Volo, The Seeker | `dp_music:volo_battle` |
| 5 | Thème de Cynthia | Cynthia Theme | `dp_music:cynthia_battle` |
| 6 | Corvault en Bataille | Corvault Battle | `dp_music:corvault_battle` |
| 7 | Le Défi de Dianthéa | Diantha's Challenge | `dp_music:dianthea_battle` |
| 8 | DJM Dialga Thème Final | DJM Dialga Final Theme | `dp_music:djm_dialga_final_theme` |
| 9 | Boss Final (EV) | Final Boss (EV) | `dp_music:final_boss_ev` |
| 10 | Combat de Gladio | Gladion's Battle | `dp_music:gladio_battle` |
| 11 | Combat de Guzma | Guzma's Battle | `dp_music:guzma_battle` |
| 12 | Combat d'Arène (SL) | Gym Battle (SL) | `dp_music:gym_battle_sl` |
| 13 | Combat d'Arène (EB) | Gym Battle (EB) | `dp_music:gym_battle_eb` |
| 14 | Iris, la Championne | Iris The Champion | `dp_music:iris_battle` |
| 15 | Combat de Jacinthe | Jasmine's Battle | `dp_music:jacinthe_battle` |
| 16 | Combat de Penny | Penny's Battle | `dp_music:penny_battle` |
| 17 | Thème Rouge & Bleu | Red & Blue's Theme | `dp_music:red_blue_battle` |
| 18 | Combat Team Star | Team Star Battle | `dp_music:teamstar_battle` |
| 19 | Ultra-Necrozma | Ultra Necrozma | `dp_music:ultranecrozma_battle` |
| 20 | Combat de Travis | Travis's Battle | `dp_music:travis_battle` |
| 21 | L'Illusion de Zacian | Zacian Illusion | `dp_music:zacian_illusion` |

</details>

---

## 🗂️ Structure du projet

```
Cobblemon-RLM-music/
│
├── 📄 pack.mcmeta                    # Métadonnées du pack (format 48)
│
├── 📁 assets/                        # Resourcepack
│   ├── 📁 minecraft/models/item/
│   │   └── music_disc_13.json        # Overrides custom_model_data → modèles
│   ├── 📁 pokemon_disc/
│   │   ├── 📁 lang/
│   │   │   ├── en_us.json            # Traductions anglaises
│   │   │   └── fr_fr.json            # Traductions françaises
│   │   ├── 📁 models/item/discs/     # 21 modèles JSON
│   │   └── 📁 textures/item/discs/   # 21 textures PNG (16×16)
│   └── 📁 rp_music/
│       ├── sounds.json               # Déclaration des événements sonores
│       └── 📁 sounds/records/        # Fichiers audio .ogg
│
└── 📁 data/                          # Datapack
    ├── 📁 dp_music/
    │   ├── 📁 functions/
    │   │   └── give_disc.mcfunction  # /function dp_music:give_disc
    │   └── 📁 jukebox_song/          # 22 définitions de chansons
    └── 📁 pokemon_disc/
        └── 📁 recipe/                # 21 recettes + 1 craft crâne
```

---

## ⚙️ Compatibilité

| Critère | Valeur |
|---|---|
| **Version Minecraft** | `1.21` |
| **Loader** | Vanilla / Forge / Fabric / NeoForge |

---

## ❓ Dépannage

<details>
<summary><b>🔧 Les crafts ne fonctionnent pas</b></summary>

1. Vérifiez que le pack est bien dans `saves/<monde>/datapacks/`
2. Exécutez `/reload` en jeu
3. Vérifiez avec `/datapack list` que `[file/Pokemon-Music-Discs (world)]` apparaît
4. Consultez les logs : `logs/latest.log`

</details>

<details>
<summary><b>🔇 La musique ne se lance pas</b></summary>

1. Vérifiez que le resourcepack `Cobblemon-RLM-music` est **activé** dans Options → Resource Packs
2. Le pack a peut-être été désactivé automatiquement si `pack_format` était incorrect
3. Vérifiez que le fichier `assets/rp_music/sounds.json` est présent
4. Testez avec `/playsound rp_music:corvault_battle record @p`

</details>

<details>
<summary><b>🏷️ Le nom du disque affiche la clé brute (<code>item.dp_music.xxx</code>)</b></summary>

Le composant `minecraft:item_name` dans la recette doit utiliser le format :
```json
"minecraft:item_name": "{\"translate\":\"item.dp_music.xxx\"}"
```
Et non pas simplement `"item.dp_music.xxx"` (string littérale).

</details>

<details>
<summary><b>🎨 Les textures n'apparaissent pas</b></summary>

1. Appuyez sur **F3+T** pour recharger les resource packs
2. Vérifiez que les fichiers PNG existent dans `assets/pokemon_disc/textures/item/discs/`
3. Vérifiez que `assets/minecraft/models/item/music_disc_13.json` contient les overrides `custom_model_data`

</details>

---

## 👥 Contributeurs

<div align="center">

|                                             Avatar                                              |      Name       |     Role     |
|:-----------------------------------------------------------------------------------------------:|:---------------:|:------------:|
| <img src="https://github.com/matheo-1712.png" width="64" height="64" style="border-radius:50%"> | **matheo-1712** | ⚙️ Developer |


</div>

> [!NOTE]
> Envie de contribuer ? N'hésitez pas à ouvrir une pull request ou à suggérer de nouvelles musiques Pokémon !

---

<div align="center">

🌐 [English README](README_EN.md) · 📂 [Structure du projet](#️-structure-du-projet) · 🔝 [Retour en haut](#-pokémon-music-discs)

</div>
