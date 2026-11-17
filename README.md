# Sterling Hunter

A WoW Forever add-on for hunters that buys your ammo for you at vendors, warns you before you run out, and reminds you when a travel aspect is still on in combat.

> **A personal add-on.** I built this for my own needs and share it as is. Support will not be provided, and issues or feature requests may not be answered.

## What it does

**Ammo auto-buy**
- Buys ammo the moment you open a vendor that sells it
- Picks arrows or bullets from your ranged weapon (bow and crossbow use arrows, gun uses bullets)
- Skips ammo you can't use yet, such as ammo above your level
- Never buys weaker ammo than what you already use (optional)
- Fills your quiver or ammo pouch, or keeps a set number of stacks
- Keeps a gold floor, and asks first before a big purchase
- Equips the new ammo after you close the vendor if it bought a different kind
- Hold Shift while opening a vendor to skip it that time

**Low ammo warning**
- A warning in the middle of your screen, with a sound, when you drop below a set number of shots
- A second warning when you run out

**Aspect reminder**
- Warns you at the start of combat, and every few seconds after, if Aspect of the Cheetah or Aspect of the Pack is still on

## Settings

**Ammo tab**
- Auto-buy on or off
- Which ammo: current ammo only, best usable, or your own priority list (names or item IDs, best first)
- Never downgrade
- How much: fill the ammo bag, or a number of stacks (can spill into regular bags if you allow it)
- Gold to keep, and the amount that needs a confirm
- Equip new ammo after the vendor

The top of the tab shows your weapon, your ammo and how many shots you have, and whether your quiver or pouch fits your weapon.

**Alerts tab**
- Low ammo warning on or off, the number of shots it warns at, and its sound
- Aspect reminder on or off, for Cheetah and Pack separately, and its sound
- Test buttons for both warnings

## Commands

| Command | What it does |
|---|---|
| `/sth` | Open or close the window |
| `/sth buy` | Buy ammo now (with a vendor open) |
| `/sth dry` | Show what it would buy, without buying |
| `/sth reset` | Move the window back to the middle of the screen |

Buy and dry run are also buttons on the Ammo tab.

## Install

Add this URL in WowUp: **Get Addons > Install from URL**

```
https://github.com/SterlingAddons/SterlingHunter
```

Or download the zip from [Releases](https://github.com/SterlingAddons/SterlingHunter/releases) and put the `SterlingHunter` folder in `_forever_\Interface\AddOns`. Restart the game after a first install.

## More from Sterling

- [Sterling Quest Sync](https://github.com/SterlingAddons/SterlingQuest) (formerly Sterling Quest Tracker): follow a friend's session and keep quest logs in sync. Works with the optional **Sterling Quest Sync Companion** app.
- [Sterling Loot Tracker](https://github.com/SterlingAddons/SterlingLoot): see who picked Need, Greed or Pass on every roll, with a roll history and gear sources.

## License

MIT. See [LICENSE](LICENSE).

Built by Sterling with the help of Claude.
