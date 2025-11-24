![New Project](https://github.com/ReaperAnon/CALIBER-Damage-Overhaul/assets/63963239/11598e7d-0f1b-4c08-b47a-024cb4ab7601)

### [Synthesis Install](https://github.com/Mutagen-Modding/Synthesis/wiki/Installation)
### [How to Use](https://github.com/Mutagen-Modding/Synthesis/wiki/Typical-Usage#adding-patchers)

The mod can be found either by searching for CALIBER on the patcher list or added via the .synth file found [here](https://github.com/ReaperAnon/CALIBER-Damage-Overhaul/releases/tag/meta).

### Consider donating if you enjoy my work:
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A6P3CRK)

## Details
A dynamically generated mod to change how ballistic weapon damage works in Fallout 4.

The bulk of the damage is dependent on the ammunition itself instead of being a statistic that is part of the weapon, making weapons that shoot the same ammunition perform similarly to each other with some minor variations in-between.

There are some blanket changes to weapon types to differentiate them a bit more as well, such as rifles having more range by default and dealing slightly higher damage (so for example, an SMG firing a 9mm cartridge will have more damage than a handgun, somewhat trying to simulate barrel length contributing to muzzle velocity). The default settings can of course be changed and are optional.

## Functionality
The mod changes the damage of all ballistic weapons to only deal 10% of their normal damage, leaving a bit of differentiation between weapons and transferring most of the damage to the actual ammunition being used.

By default the mod supports Munitions, the Munitions Ammo Addon and Caliber Complex. All ammos have damage values defined in the mod's configuration menu which can be changed at will along with the different weapon type buffs.

The default ammo damage balance is based on my Unleveled Commonwealth mod (check the suggested mods section below), but SCOURGE or Hardcore Health Overhaul will still be better than vanilla. 

## Pros Compared To True Damage

- The damage modifier attachment options many mods offer keep working as they were intended to.
- Ammo type modifications like "hollow points" and "armor piercing" ammo types function as intended, making using ammo types that increase your damage wortwhile instead of just pumping armor piercing.
- Weapon receiver upgrades are made useful by changing their damage increasing effects into recoil mitigation instead. Heavier receivers will now reduce your active recoil with any given weapon while lighter receivers will increase it. This also means automatic receivers will have higher recoil which is a much better way to balance them.
- Damage changes are removed from attachments that rechamber the weapon. You won't get a double debuff from swapping ammo types to something weaker or an extra buff if you switch to something stronger.
- The descriptions of weapon attachments are changed automatically to match the new functionality. It's not perfect but it works >90% of the time.
- Critical hits deal a normal amount of damage and won't instantly kill foes.
- Vehicle health doesn't have to be changed as they won't instantly blow up in a single shot from a weak weapon anymore.
- Damage boosting perks still work (in case you like them, you can still use mods to change or remove them, including True Damage's perks module).
- Can easily change ammo damage without having to open xEdit, including copying someone else's patcher settings file.
- Option to make ammo balancing automatic by choosing a target race and setting the amount of shots to kill as desired instead of setting manual damage values.

## Known Issues
The settings menu is really slow, it didn't crash if you click on it, you just need to let Synthesis sit in the background a bit until it populates it and lets you change the options. It's not really something I can work around unless I turn the mod into its own application, which would kill the convenience of using it through Synthesis, making the whole thing kinda pointless.

As stated earlier, the attachment descriptions aren't always perfect. I didn't use AI to regenerate them so sometimes you might find something that isn't quite right, but I tested it with like 50 weapon mods installed and it worked pretty well. They're not hard to fix in xEdit.

The attachment changes aren't absolutely perfect because it's impossible to differentiate what the author's intent was. What this means is that for example a "gauss" attachment that greatly increases damage will end up decreasing recoil instead.
It's a situational problem but it's there.

The mods I know that do things like this are the Battlefield 4 .44 Magnum (has a gauss barrel), a unique gauss version of the Service Rifle from Deadpool and the FN FAL - SA58 from Wanaming0 (has an electric receiver attachment, the radiation one works fine). Weapons that change the ammo type to 2mm EC instead of just boosting damage work just fine.

## Requirements
The mod **requires the [Spell Perk Item Distributor (SPID) mod for Fallout 4](https://www.nexusmods.com/fallout4/mods/48365)** to make the weapon range, armor piercing, etc changes apply to NPCs as well (they're applied via a hidden perk). If you don't care about that you don't actually need to install it, it will still work for the player and the main damage and ammo changes work for everyone regardless.

## Suggested Mods

## Ammunitions Frameworks
- **[Munitions - Ammo Expansion Project](https://www.nexusmods.com/fallout4/mods/66051):** For me, it's the best framework and the modern standard for expanding caliber variety in Fallout 4. The patcher includes support for it's addons **[Munitions - Additional Ammo](https://www.nexusmods.com/fallout4/mods/69583)** and **[Munitions - Advanced Calibers](https://www.nexusmods.com/fallout4/mods/81931)**.

- **[Caliber Complex](https://www.nexusmods.com/fallout4/mods/50111?):** It's a good alternative, have lots of ammunitions to use from, but in my opinion it was superseded by **Munitions**. If you are going to use it, it's suggested to use along with its **[Cover Penetration Framework](https://www.nexusmods.com/fallout4/mods/55959)** patch.

 ## Utilities/Bugfixes 
- **[Unused Ammo Remover](https://github.com/ReaperAnon/UnusedAmmoRemover):** If you don't like Caliber Complex because it spams your game with ammo, use the Unused Ammo Remover mod which is another Synthesis patcher. It removes all ammo that is unused in your game both from the leveled list and also from crafting (if you have an ammo crafting mod installed).

- **[Armor Penetration Fix](https://www.nexusmods.com/fallout4/mods/73849):** By default the ammo penetration effect is broken in Fallout 4, so it's suggested you download this as you're probably using some mods along with this that make use of the effect.

## NPC Balancing

- **[SCOURGE](https://www.nexusmods.com/fallout4/mods/60917)**: SCOURGE works by randomising NPC stats using a normal/Gaussian distribution curve. Whenever a new NPC spawns it will have its stats randomised based on the values configured through the MCM. This results in all NPCs being different the way everyone is different in real life.

- **[Unleveled Commonwealth](https://github.com/ReaperAnon/Unleveled-Commonwealth):** Without some mod to rebalance enemies, weapons will be overpowered in the early game and weak in the late-game. I suggest using the Unleveled Commonwealth mod which is another Synthesis patcher, similar to how SCOURGE works but more compatible and retains relative enemy balancing instead of randomizing NPC stats. Also doesn't require any other mods to function.

- **[Hardcore Health Overhaul](https://www.nexusmods.com/fallout4/mods/68655)**: This mod removes Fallout 4’s excessive bullet sponges by giving all enemies and the player realistic, fixed health and resistance values. Humans range from 100–250 HP, big creatures scale much higher, and robots rely on armor rather than huge health. Critical hits matter more, auto-healing is essentially disabled, melee damage is rebalanced, and major creatures like Deathclaws and Super Mutants are made faster and deadlier.

## Credits

### [Mutagen](https://github.com/Mutagen-Modding/Synthesis) - for Synthesis.

### [ReaperAnon](https://github.com/ReaperAnon) - for the original patcher.


