# ISI Build Bundles

A 7 Days to Die (7D2D) mod that bundles the shapes needed to build specific horde bases.

## Included Bases

- [WaywardEko - The Eko Box](https://www.youtube.com/watch?v=mvx9sxO_FZQ)

- [WaywardEko - Eko Craft](https://www.youtube.com/watch?v=szxHF5YGD44)
- [WaywardEko - Spiral Sentry](https://www.youtube.com/watch?v=Evp-3gU4P24)

- [WaywardEko - Switchback](https://www.youtube.com/watch?v=Bv4Lk7UkkV4)
- [WaywardEko - Seeker's Bane](https://www.youtube.com/watch?v=jEMnP7sHEzo)
- [WaywardEko - The Spark](https://www.youtube.com/watch?v=GcciKSy9z_M)
- [WaywardEko - The Foundry: Horde Base](https://www.youtube.com/watch?v=k89FE_6P9fA)
- [WaywardEko - The Foundry: Crafting Base](https://www.youtube.com/watch?v=UT6BViqGJkg)

## Example

![Switchback - Description](images/ekoSwitchDescription.png)
![Switchback - Day 07 Shapes](images/ekoSwitch07.png)
![Switchback - Day 14 Shapes](images/ekoSwitch14.png)
![Switchback - Day 21 Shapes](images/ekoSwitch21.png)
![Switchback - Day 28 Shapes](images/ekoSwitch28.png)
![Switchback - All Shapes](images/ekoSwitchAll.png)

## Design Decisions

- Alternating Colors (Makes it easy to see where one build stops and another starts)
  - Every Creator gets a light and dark shade
  - Builds are sorted alphabetically (localization trumps item/recipe name) so if a build is added in the middle, you will need to recolor all of the later builds

- Shapes only (This is just a tool for finding the right shape)
  - Do not include material costs (no point boxing and unboxing)
  - Do not include components (no point boxing and unboxing)

- No Bundles of Bundles
  - Some builds require upgrading between steps. It doesn't make sense to wrap later concrete bundles around wood bones.

## TODO

- recipe lists - steps v shapes

- Verify Counts (Build The Base)

- Localization
  - Shorten, so it does not squish excessively
  - Figure out a Max Width

- Publish

- Stage Bundles?
