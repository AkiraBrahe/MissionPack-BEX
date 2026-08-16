
# Mission Pack for BEX (Adapted from BTA)

## Contents

This archive contains **7 new mission types** originally created by Kaiotik for BattleTech Advanced (BTA) and adapted for BattleTech Extended (BEX), along with new Duel maps:
* **Assassinate (Switch):** An assassination contract that turns into a high-stakes VIP extraction.
* **Battle Royale:** A 6-way free-for-all, arena-style combat scenario.
* **Defend Base (Scramble):** A base defense contract where your forces are scattered randomly across the map.
* **Defend Base (Split):** A base defense contract requiring you to defend two separate bases simultaneously.
* **Defense in Depth:** A large-scale engagement to defend multiple bases on an extended map, occasionally supported by allies.
* **Organized Retreat:** A lengthy contract that starts as a standard base defense and evolves into a multi-convoy escort.
* **Warzone:** An endurance contract where your forces must survive up to ten waves of enemies, sometimes alongside allied reinforcements.

## Installation

* Unpack the **MissionControl** mod folder from this archive directly into your `Battletech\Mods` folder.
* (Optional) Extract **ColourfulFlashpoints** to color-code both ComStar missions and the new mission types on the mission select screen.
* (Optional) Extract **Solaris7** to add 12 game worlds across the starmap featuring special Battle Royale missions. Win a rare 'Mech for every 5-win streak achieved within each weight class (Light, Medium, Heavy, Assault).
  * The mod folder contains a ZIP file with the full version of Solaris 7, including the Solaris League matches. This version of the mod requires a new game start.
  
## Change Notes

* **v0.1.0 (Initial Release):**
  * Ported all files directly from the latest version of BattleTech Advanced (BTA).
  * Renamed several new contract types for better consistency:
    * `BattleRoyaleV2` ? `BattleRoyale`
    * `DefenceInDepth` ? `DefenseInDepth`
    * `SplitDefense` ? `Split_DefendBase`
    * `TheSwitch_Assassinate` ? `Switch_Assassinate`
  * Cleaned up all `contractTypeBuilds` and `encounterLayers` files, streamlining the `Author`, `Name`, and `FriendlyName` fields.
  * Standardized encounter layers to use the camelCase naming convention instead of acronyms.

* **v0.1.1:**
  * Implemented various minor adjustments to the `contracts` files.
  * Clamped `maxNumberOfPlayerUnits` to a maximum limit of 4.
