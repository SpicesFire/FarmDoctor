<p align="center"><img src="logo.png" width="128" alt="Farm Doctor logo"></p>

# Farm Doctor – why isn't my Minecraft farm working?

**Right-click your farm with the Farm Scanner and get a plain-words diagnosis: what's wrong, where, and how to fix it.**

Farm Doctor is a free Minecraft Java Edition mod that checks a farm against the real vanilla rules. Problem spots light up in the world, the mobs filling your mob cap glow through walls, and the action bar tells you if your AFK spot is right.

- **12 farm types:** mob, iron, raid (totems), gold, enderman, slime, witch, guardian, spawner, crops & plants, animals, villager breeder.
- **Fabric, Forge and NeoForge**, Minecraft 1.20.1 to 26.3.
- **8 languages:** English, Turkish, German, Spanish, French, Russian, Brazilian Portuguese, Simplified Chinese.
- **Free.** No account, no internet, no AI. Spawning rules stay 100% vanilla.

**Website and FAQ: https://spicesfire.com/farmdoctor/**

## How to use

1. Craft the **Farm Scanner**: iron nugget on top, stick – paper – stick in the middle, redstone at the bottom. (Or just type `/farmdoctor`.)
2. Right-click the spawning floor of your farm, or a block next to your villagers / crops / spawner.
3. Read the report: ✔ fine, ⚠ risky, ✖ stopping the farm.

**Shift + right-click** (or `/farmdoctor menu`) opens a clickable farm list sorted by what you want to farm. By default the doctor guesses the farm type from where you click. `/farmdoctor stop` hides the markers.

## What it checks

**Mob farms** – lit spots (hostile mobs need block light 0 since 1.18), floors mobs can't stand on (slabs, glass, leaves, buttons, rails, water), sky-exposed spots that eat the mob cap at night, mobs piling up, the mob cap and *where* the mobs filling it are, and a live AFK-distance read-out.

**Iron farms** – enough villagers within 10 blocks, claimed beds, sleep in the last 20 minutes, a zombie they can see, living golems blocking new ones.

**Raid farms** – is it a village, are raids on, do you have Bad Omen / Raid Omen, which wave it is.

**Slime / witch / guardian / gold / enderman** – slime chunk test (and the nearest one), below Y 40, inside the witch hut or ocean monument area, Nether and End rules, 3-block spaces for endermen.

**Spawners** – room around it, light 11 or less, 6+ mobs crowding it, the 16-block player range live on the action bar.

**Crops & plants** – dark crops, dry farmland, melon/pumpkin stems with no room, kelp that stopped growing, cane and cactus height, random tick speed.

**Animals & villager breeders** – who can breed, cooldowns, babies, deadly entity cramming, free beds and food.

## Download

Get the jar for your loader and Minecraft version from the [latest release](https://github.com/SpicesFire/FarmDoctor/releases/latest), or from https://spicesfire.com/farmdoctor/#get. Modrinth and CurseForge pages are in review.

| Loader | Minecraft | Needs |
|---|---|---|
| Fabric | 26.3, 26.1.2, 1.21.10, 1.20.1 | Fabric API |
| NeoForge | 26.3, 1.21.1 | – |
| Forge | 26.3, 1.20.1 | – |

Install it on the server (single player counts as one). Players should have it too so the messages appear in their language.

## Feedback

Found a farm it gets wrong? Open an issue with a screenshot of the report and your Minecraft version.

---

Made by [SpicesFire](https://spicesfire.com/). Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.
