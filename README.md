# Saint's Vending Machines

A mod for Fallout: New Vegas and Tale of Two Wastelands that adds full interactivity to vending machines placed around the wasteland. Currently supports Nuka-Cola machines only. Written in NVSE, lightweight, ESPLess.

## About

This mod introduces the ability to interact with vending machines to purchase a variety of products from procedurally generated stock, classic Nuka-Cola, and less frequently, Quantum, Quartz, or Victory. Very rarely, machines may also offer Ice Cold Nuka-Cola or even Rum and Nuka. Written in xNVSE/JIP, lightweight, ESPLess. Safe to add or remove at any time.

- Activating a vending machine will open a purchase menu, based on the machine's stock.
- The machine sells stocked products at fixed prices for *Pre-War Money*.
- Stock is procedurally generated, seeded from the machine's object coordinates.
- Stock is *not* stored in the savefile but generates the same for all players.
- Vending machines found outdoors typically stock less and won't have rare variants.
- Every product has a fixed price, with more rare variants selling for more.
- Prices are displayed as 1 Pre-War Money = $10 (assuming 2077 inflation).
- If a vending machine stocks a product, it will not run out (for convenience).
- Sneak-activating a vending machine allows you to unlock it and loot it regularly.

Concept and code by Saint, original artwork by Mezu (#mezulino).

## Compatibility

Broadly compatible with all mods. New container-type placed Nuka-Cola vending machines will be compatible automatically, statics will not be replaced. Uses [KEYWORDS](https://www.nexusmods.com/newvegas/mods/83088) to determine what is a vending machine.

**Tale of Two Wastelands:** All vending machine container ids for Fallout 3 and New Vegas are already included, works out of the box in the Capital Wasteland and the Mojave.

**Owned machines:** Vending machines placed in certain communities may be marked as owned. Looking at a locked and owned vending machine will mark the "Use" text as red but activating it will *not* count as a crime (like breaking in or stealing). You can freely use an owned vending machine as long as you're not sneak-activating it.

**Loot menus:** For better compatiblity with loot menu mods (JLM, Loot Menu, etc.), all vending machines are *locked by default*. The lock level set is between very easy and medium, based on the player's luck. If unlocked by the player, vending machines may re-lock after a couple of days to make interaction easier. Looting without opening the container will not activate it and purchasing would be unergonomic. This change makes the vending process more streamlined and also makes acquiring Nuka-Cola en masse slightly less trivial. Once unlocked, the loot menu interaction will be used instead. Once empty, the machine will provide its regular interaction again.

Creatively, I think this makes a lot of sense in-universe, real world vending machines are also generally locked. You can think of the sold stock of what's inside the machine and think of its loot as what's accessible after opening the front.

## Roadmap

- **Planned:** Support for Sunset Sarsaparilla machines in the Mojave.
- **Planned:** Configurable pricing for stocked products via INI file.
- **Considered:** Add support for Nuka-World Imports items.
- **Done:** Rare chance for variants like Ice Cold and Nuka & Rum.
- **Done:** Stock overrides for world spaces by name (e.g. Megaton).

## Requirements

Requires xNVSE and its typical extensions, JIP NVSE, JohnnyGuitar, and KEYWORDS.

## License

This mod was created by Saint for free use by the Fallout mod community under the MIT license. Inspired by ["Vending Machines Vend"](https://www.nexusmods.com/newvegas/mods/87668) created by [Fantafaust](https://www.nexusmods.com/newvegas/users/3060508). It may be shared, modified, or redistributed as part of mod packs with basic attribution.