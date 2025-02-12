# Welcome to Kaspak!
This repo is for my new and improved MCBE utility pack, started as a fork, to be a minimal utility for redstone development.
If you're just here for the pack, no problem! You can find them in the `build/` directory. 

The `src/` directory holds the contents of the latest version in a readable format, making it easier to see what's under the hood! :3
> [!TIP]
> If you want to use the pack directly on Windows or Android devices, simply change the file extension from `.zip` to `.mcpack`

## Features!
### Directional Indicators
Hoppers, droppers, dispensers, *and* observers all have minimal line indicators to show what direction they're facing. Hoppers and observers work flawlessly, with color changes to specify when the hoppers are locked or the observers fire.
The droppers and dispensers have a known quirk (stemming from having to use `blockshape` attributes), where the side exactly opposite of the face is not accurate. Until I am aware of an alternative, there is unfortunatley nothing I can do. :(

### Seperate Comparator/Repeater Textures
In the vanilla game, the textures for both are copies of one another. Now they are not, with a *tiny* tweak to make them easier to identify on the side and bottom.

### "Illegal" Blocks
There are a handful of blocks that Mojang doesn't intend for their users to have, so as a result, they have not been given textures or easily readable names.
The `Air`, `End Gateway`, and `End Portal` blocks now have real textures, with those AND `Flowing/Static Lava`, `Flowing/Static Water`, and `Bubble Columns` now having readable names.

### Visibly Sticky
Most sides of the sticky piston (much like comparators/repeaters) are copies of its non-sticky variant. This pack changes the piston arm's side and bottom's base texture to set itself apart, making them easier to differentiate between.

### Stems
Although rather niche, the pumpkin and melon stems have been changed to be orange and green, repectively.

### Non-Obtrusive
Scaffolding and water are no longer nightmares to try and look through, and sounds you'll likely hear often have been turned down a tad to minimize the madness.
The enchantment glint, pumpkin overlay, and off-hand `totems of undying` are not nearly as 'in-your-face', and particles have been "hollowed-out" in an attempt to be a bit easier to see beyond.
Tangentially, but still worth noting, is that TNT is not only quieter, but also emits less particles.
