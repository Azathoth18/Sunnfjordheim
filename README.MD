# Creatures of Origins

New enemies mod created to be used on the **SUNNFJORDHEIM** server.

[![Discord](https://i.imgur.com/uE6umQE.png)](https://discord.gg/vMRwKGm5r7) Personal Discord – updates and development news
[![Discord](https://i.imgur.com/uE6umQE.png)](https://discord.gg/qNvuzeFR7n) **SUNNFJORDHEIM** Community Server

---

## Technical Information & Usage

<details>
This mod is designed to be cloned using MonsterDB. While it can function as a standalone, please keep the following points in mind:
Armor Rendering: Armors that add an ArmorMat (such as the Troll Set) will not render correctly without MonsterDB, as the material isn't properly copied to the mob model. Using MonsterDB fixes this issue.
F1 Menu Integration: If a cloned mob's prefab name starts with RZ_, you can configure it directly via the F1 Creatures menu.
Slot Conflict Warning: Avoid adding items to the same slots in both the F1 menu (CreaturesOrigins) and MonsterDB. For example, if you equip ArmorLegs in both places for the same mob, it may cause glitches or unpredictable behavior.
Damage & Stats: A mob's power and damage output are inherited directly from its equipped items.
Gender System: If the mob's name ends with F (Female) or M (Male), the CreaturesOrigins system for custom colors, hair, and beards will be automatically applied.
Spawning: These creatures do not spawn naturally in the world. You must spawn them manually.

</details>

---

## Prefab List Reference

<details>
<summary><strong>Prefab List Reference</strong></summary>

| Category    | Male Prefab       | Female Prefab     |
| ----------- | ----------------- | ----------------- |
| Undead      | RZ_NOMUERTOM      | RZ_NOMUERTOF      |
| Black Orcs  | RZ_ORCONEGROM     | RZ_ORCONEGROF     |
| Green Orcs  | RZ_ORCOVERDEM     | RZ_ORCOVERDEF     |
| Vile Orcs   | RZ_ORCOVIL        | —                 |
| High Elves  | RZ_ELFOM          | RZ_ELFOF          |
| Night Elves | RZ_ELFODELANOCHEM | RZ_ELFODELANOCHEF |
| Draeneis    | RZ_DRAENEIM       | RZ_DRAENEIF       |
| Niflborns   | RZ_NiflbornM      | RZ_NiflbornF      |
| Jotuns      | RZ_JotunM         | RZ_JotunF         |
| Muspelheim  | RZ_MuspelheimM    | RZ_MuspelheimF    |
| Tiefling    | RZ_TielfingM      | RZ_TielfingF      |
| Myrmidons   | RZ_Mirmidon       | RZ_MirmidonF      |
| Trolls      | RZ_TrollM         | RZ_TrollF         |
| Dwarves     | RZ_ENANO          | —                 |

</details>

---

## HairColorIndex Reference

<details>
<summary><strong>HairColorIndex Reference</strong></summary>

| Index | Color Description             | Index | Color Description    |
| ----: | ----------------------------- | ----: | -------------------- |
|     0 | Black                         |    15 | Dark Bluish Gray     |
|     1 | Very Light Blonde / Pale Gold |    16 | Deep Dark Green      |
|     2 | Light Brown / Honey           |    17 | Magenta              |
|     3 | Very Dark Brown / Near Black  |    18 | Cyan                 |
|     4 | Dull Medium Brown             |    19 | Lime                 |
|     5 | Light Ash Brown               |    20 | Purple               |
|     6 | Bright Golden Blonde          |    21 | Neon Orange          |
|     7 | Dark Blonde / Wheat           |    22 | Electric Blue        |
|     8 | Ash Blonde / Beige            |    23 | Neon Red             |
|     9 | Auburn / Reddish Brown        |    24 | Pure White           |
|    10 | Dark Red / Mahogany           |    25 | Ice Bluish White     |
|    11 | Copper / Fire Red             |    26 | Glacier Light Blue   |
|    12 | Dark Gray                     |    27 | Intense Glacier Blue |
|    13 | Medium Gray / Grizzled        |    28 | Cold Grayish Blue    |
|    14 | Cold White / Snow             |    29 | Cold White / Snow    |

</details>

---

## Roadmap & Planned Features
<details>
<summary><strong>Roadmap & Planned Features</strong></summary>

* **Custom Cloning System**: Investigation into a built-in cloning system native to the mod.
* **New Creatures**: Expansion of the roster with even more unique mobs.
* **Enhanced Audio & FX**: Improved sound effects and custom creature voices.
* **New Loot Tables**: Unique drops and items per creature type.
* **Custom Animations**: New movement and attack animations.
* **Underwater Combat**: Enabling Myrmidons to fight effectively underwater (compatible with diving mods).
</details>

---

## Changelog

<details>
<summary><strong>1.0.1</strong></summary>
* Added new enemy mobs to the roster
* Integrated custom hair and beard systems
* Improved control over creature elements and settings
<summary><strong>1.0.0</strong></summary>
* Initial release
</details>

---

## Special Thanks & Acknowledgments

<details>
<summary><strong>Special Thanks & Acknowledgments</strong></summary>

* **Rusty** – Guidance on mob configuration, hair systems, and attack patterns
* **cookiexmilk** – Teaching me how to create mobs and answering countless questions
* **Ulvar Hræfr** – Constant feedback and testing to optimize the mod
* **MidnightsFX** – Teaching many of the implementations used today
* **Shawesome** – Race system knowledge and constant support; this mod exists thanks to your teachings
* **Davidmandalorian** – Advice, opinions, and continued support
* **Valheim Modding & OdinPlus** – For always answering community questions with patience
* **Sunnfjordheim Community** – Thank you for providing the space to test ideas and for the constant support

</details>
