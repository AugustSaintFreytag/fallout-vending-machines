# Saint's Vending Machines

A mod for Fallout: New Vegas and Tale of Two Wastelands that adds full interactivity to vending machines placed around the wasteland. Currently supports Nuka-Cola machines only. Written in NVSE, lightweight, ESPLess.

## About

The mod allows players to interact with vending machines to purchase a variety of products from procedurally generated stock, classic Nuka-Cola, and less frequently, Quantum, Quartz, or Victory.

- Activating a vending machine will open a purchase menu based on the machine's stock.
- The machine sells stocked products at fixed prices for *Pre-War Money*.
- Stock is procedurally generated, seeded from the machine's object coordinates.
- Stock is *not* stored in the savefile but generates the same for all players.
- Pricing for products is fixed, one *Pre-War Money* is equal to $10 (assuming 2077 inflation).
- Vending machines have an infinite number of their stocked items for convenience's sake.
- Sneak-activating a vending machine allows you to unlock it and loot it regularly.

## Compatibility

Broadly compatible with all mods. New container-type placed Nuka-Cola vending machines will be compatible automatically, statics will not be replaced. Uses [KEYWORDS](https://www.nexusmods.com/newvegas/mods/83088) to determine what is a vending machine.

**Owned machines:** Vending machines placed in certain communities may be marked as owned. Looking at a locked and owned vending machine will mark the "Use" text as red but activating it will *not* count as a crime (like breaking in or stealing). You can freely use an owned vending machine as long as you're not sneak-activating it.

**Loot menus:** For better compatiblity with loot menu mods (JLM, Loot Menu, etc.), all vending machines are *locked by default*. The lock level set is between very easy and medium, based on the player's luck. If unlocked by the player, vending machines may re-lock after a couple of days to make interaction easier. Looting without opening the container will not activate it and purchasing would be unergonomic. This change makes the vending process more streamlined and also makes acquiring Nuka-Cola en masse slightly less trivial. Once unlocked, the loot menu interaction will be used instead. Once empty, the machine will provide its regular interaction again.

## Future

- Special variants of Nuka-Cola like Ice Cold and Nuka & Rum.
- Support for Sunset Sarsaparilla for the Mojave.

## Requirements

Built with xNVSE and its typical extensions, JIP NVSE, JohnnyGuitar.

## License

This mod was created by Saint for free use by the Fallout mod community under the MIT license. Inspired by ["Vending Machines Vend"](https://www.nexusmods.com/newvegas/mods/87668) created by [Fantafaust](https://www.nexusmods.com/newvegas/users/3060508). It may be shared, modified, or redistributed as part of mod packs with basic attribution.