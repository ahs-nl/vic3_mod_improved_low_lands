# Victoria 3 mod: Improved Lowlands

Improved Low Lands mod for Victoria 3, aiming to enhance realism and depth when playing "lowlandish"-cultured countries. Adding new countries, cultures, flags, uniforms, and leaders, but not changing the map, provincial, or population setup. Due to changes to the base game the mod is not compatible with achievements and ironman saves.

The mod aims to be standalone but completely functional on top of vanilla and any other mod, to be integrated at will by any other mod. It has been designed to work for v1.1.2 but should work under older and barring major design changes also under newer versions.

## Installation

Just pull or download from github, move to your mods directory, and add the mod to the game launcher.

Other sources to download
- Discord: _none_
- Steam Workshop: _none_
- Paradox Mods: _none_
- Paradox Forum: _none_

## Countries in scope

- Low Lands countries (Netherlands, Belgium, Luxembourg)
- Colonial regions (Suriname, South Africa, Dutch East Indies)
- Potential colonial regions (Australia, New Netherlands)
- _Idea for future additions_: further potential colonial region (New Netherlands, Formosa, ...)

## Features

- New/tweaked flags:
  - Historically-plausible flag definitions and CoA designs for most forms of government for all countries in scope
- New/tweaked releasable countries:
  - in the Netherlands (Netherlands, Frisia, Holland, Brabant, Limburg, Belgium, Flanders, Wallonia, Luxembourg)
  - in colonial regions (Dutch East Indies, Dutch West Indies, Suriname, Gold Coast, Ivory Coast)
  - in Southern Africa specifically (Namibia, South Africa, Cape Provice, Natal, Orange Free State, Transvaal, Stellaland, Lydensrust)
  - optional more far-fetched colonial regions (New Holland/Australia, Ceylon w.i.p., Formosa w.i.p., New Netherlands t.b.d.)
  - No Benelux: makes no sense historically, rather we have a United Netherlands for that
- New/tweaked country formation:
  - for Netherlands, Belgium, South Africa
- New/tweaked cultures:
  - addition of Frisian culture
  - deepening of Boer, Voortrekker, Dutch, Flemish, Wallonian cultures
  - embedding of [Victorian Flavor Mod](https://github.com/Radsterman/Victorian-Flavor-Mod)'s Voortrekker culture
- New historical uniforms:
  - tweaked graphical assets for Netherlands, Belgium, Boer, and Dutch East Indies
- New/tweaked historical leaders and political characters (some with DNA) at startup and for spawning
- Tweaked country startup in `history` files for scoped countries
- New colors ([wappenwiki](http://wappenwiki.org)-based) and flag emblems/designs for harmonious CoAs 
- Reworked map colours for scoped countries and cultures

## Design philosophy

- Fits seamlessly into any other mod
- Follows vanilla style for graphics and form
  - graphics: simple, no nonsense, historically plausible flags
  - form: similar coding syntax, no railroading, ...
  - no changes to the map or states, that is for other mods
- Does not overwrite vanilla files (beyond absolutely necessary, e.g. correcting errors)
- Strives for historical plausibility (no crazy flags, funny countries, imaginary uniforms)
  - colors follow WappenWiki-colors where possible, since country-specific colors were generally less involved and a harmonious consistent simple color system is preferred
  - for instance no crazy Dutch flags just because it looks good -- apart from small changes in shading it is very unrealistic to expect the Netherlands to change flag as its form of government changes, and using political symbols as the national flag makes no sense
- Uses PNG for image assets where possible, rather than DDS
  - PNG makes it so much easier to edit the files and embed in workflows (e.g. from inkscape) and works flawlessly in the game AFAIK (open to being corrected on this)

## Limitations

- No changes in provincial setup, leaving that to other mods (or depending submods, t.b.d.)
- No combat unit illustration graphics, in order not to overwrite vanilla `combat_unit_types` -- unfortunately

## Integrates well with...

This mod has been built with the option in mind to integrate with any mod and vanilla.
Integration with the following mods has been verified:
- [Victorian Flavor Mod](https://github.com/Radsterman/Victorian-Flavor-Mod)

## To do

- Add license
- Add screenshots

## Credits

- stolen some DNAs from the ecchi mod without yet asking for permission...
