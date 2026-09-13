# Current Rules
---
- No pop up camp manager allowed (or start with no camps/points, and allow setting them up).
- No traders allowed.
- No limited bounties allowed.
- No Palico.
- No Support Ship Shop.
- Only High Rank Hunts allowed.
- Square's referring to monsters are all large monsters.
- Talismans and Mantles are banned.
- No supply items.
- Investigations and Field surveys are not allowed.

# Mod Effects
---
 - Monsters drop:
   - Gold cert
   - Silver cert
   - Hard (red) armor sphere
   - Monster specific cert, or a mega potion if there isn't one.
   - Tail (part) carves changed to mega potions.
   - They'll always appear in this order, so if something is giving you a mega potion when it should be giving you some cert, let me know.
 - Large monster carves are mega potions.
 - Recipes are set so:
   - Weapons/armor/weapon forging are all 5k.
   - Armor upgrades are 500 per level.
   - Weapons/armor use a monster cert, or a gold cert for the rest.
   - Only the last weapon upgrade is available, no upgrade needed.
   - Kinsects craft/upgrade with one silver cert.
   - Hope/expedition/ore and other non-monster tree weapons require 3 golden certs to upgrade.
     - Exceptions:
       - "Paralysis Tree" changed to Lala B. (It uses Lala parts for most of it, just doesn't have the mon in the name.)

# Installation
---
- DL `Bingo Brawlers.zip`.
- Install through Fluffy Mod Manager.

# Save Setup
---
This save template is a mostly-complete starting point. It is intended for use as an initial pass for you to further customize and finish.

To import/overwrite your current save with the Bingo save template:
- Install REFramework (hereafter 'REF').
- Install https://www.nexusmods.com/monsterhunterwilds/mods/2522
- Save `Bingo Save Import.json` somewhere. I'd suggest the game dir as the importer opens with that as the initial directory.
- Edit the JSON; change the name under `_BasicData.CharName` (or Ctrl+F `CHANGE_MY_NAME`) to whatever you want, else your name will become `CHANGE_MY_NAME` on import.
- Load up the game; load into the save you wish to alter.
- Open REF (`insert` key by default).
- Expand `Script Generated GUI`.
- Expand `Save Data Import/Export`.
- Press `Refresh Saves List`.
- Select the same save slot you just loaded the game into!
- Expand and check only these import items:<br>
![Import Settings](Import%20Settings.png)
- Click `Import`, select `Bingo Save Import.json` from wherever you put it.
- Save and return to the title screen.
- Load back into your save. This should now be prepped and ready for bingo.

This json will:
- Re-lock all camps.
- Set Zenny/points to 0.
- Remove/override all equipment so you only have HR Bone / Alloy armor and all R7 Hope weapons.
- Removes all items, gems, parts, etc; all that remains is:
  - Pouch: 10 potions, 10 mega potions, 5 Rations, 2 Well-done steaks.
  - Box: 10 Nullberries, 2 Antidotes, 2 Hot drinks, 2 Cold drinks, 3 Lifepowders, 2 Max Potions, 1 Ancient potion
- Ammo types are available, but at 0. You can't really remove them without completely breaking things.

Things you will need to do after import:
- Change palico to standby.
- Customize items sets, item wheels, settings, whatever.
- Save, exit, and backup your now-prepped save file.

Save location if you don't know:<br>
`Steam\userdata\{your Steam ID}\2246340\remote\win64_save`