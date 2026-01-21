# Celtic Independence Overhaul

Welcome to the documentation for Celtic Independence Overhaul, a mod for Anno 117.

This mod provides alternative systems and buildings to remove the Roman-ness from Celtic islands in Albion and give them more unique feeling. It also changes the overall needs structure between Celts, Roman-Celts and Latium so that instead of the Celts and Roman-Celts both independently supplying Latium, the Celts supply the Roman-Celts, and the Roman-Celts supply Latium.

You can download the mod on mod.io here: [Celtic Independence Overhaul.](https://www.mkdocs.org)

To report bugs or give feedback you can either leave a comment on the mod.io page, or [open an issue on github.](https://www.mkdocs.org)


## Key Feature Overview
* Aqueducts are no longer useful on Celtic islands. They are replaced by new systems
* New public buildings to replace Roman ones on Celtic islands
* Public buildings only affect matching residence type, with a new Roman-Celtic residence to make this work for waders
* Albion needs are a lot more self-sufficient. Only need to import olive oil and optionally wine
* New needs for Celts: wicker baskets and ornamented ponies
* Celts now make and consume bread, Roman-Celts now make and consume beer
* Chariots now made by nobles. Iron added to chariots and ceremonial shields
* Latium residences now consume sausages instead of cheese and wigs instead of cloaks


## Detailed Feature List
* Celtic mines are now boosted by mealhouses, which are supplied by Celtic meals made from cheese, beer and beef roasts
* Celtic farms are now boosted by fertiliser silos, which are unlocked at 4k Epona devotion along with fertiliser
* Ochs farms output fertiliser as an additional good, but it can also be produced directly by fertiliser pits in marshes
* Farms and mines that are used by both Celts and Roman-Celts (iron/hemp) now have 2 versions so you can match the boost system to the island type
* The very Roman theatre and gambling house have been replaced with Celtic alternatives, the wickerman and the sacred tree
* Public buildings now only affect Celtic or Roman-Celtic houses of the matching type. Public building stats have been combined to account for this
* To allow the above for waders, a new Roman-Celtic wader residence has been added. They are mostly the same but use the tavern instead of the bardic hall
* The Latium market has been added. You can use either it or the existing Celtic version to supply the market need. They had to be split into separate buildings because the Albion market is rotated 90 degrees from the Latium one, which means it doesn't work as a skin
* The Fanum is now a Celtic public building and Roman-Celts have the Sanctuary instead. This helps fix the weird layout mismatch since the Fanum is the same size as the other Celtic public buildings but not the Roman-Celtic ones
* Celts now need and can make bread, but instead of wheat they have rye farms. To support this, wheat has been changed to grain and the rye farm also outputs grain. This way rye can also be used in animal farm silos
* Roman-Celts now need and can make beer, but less efficiently from grain (wheat)
* Celts can now also make wine but with less efficiency at the final vintner stage
* Ceremonial shields have been moved to tier 3 to replace fine glass and are now made from iron, wood and dye. Smiths/aldermen now consume wicker baskets in place of ceremonial shields. These are made from reeds and dye
* Chariots are now produced and consumed by Nobles and are made from wood, iron and horses. They replace Fine Glass
* Instead of chariots, aldermen now produce and consume ornamented ponies made from bronze and ponies
* Roman-Celts now consume torcs instead of soap and cloaks instead of togas
* Equites and patricians now consume sausages instead of cheese and wigs instead of cloaks
* Paved roads can now also be unlocked and built with granite instead of concrete
* Albion shrines are now built with tiles instead of concrete


## WIP (work in progress) Features
* More tweaks to building graphics are planned. Don't expect too much. Mostly just some tree swaps, colour tweaks, and maybe roof swaps if I can get them working.
* The balancing is probably problematic as you get to end-game. I used existing consumption rates from the same tier but this doesn't account for the massive shift to Roman-Celts supplying everything to Latium instead of it being split with the Celts. This is a pain to test because you actually just need to play the save a long time and build up all the islands, so I welcome any feedback from players. I can easily tweak consumption rates and production times but I need data to base those decisions on.


## Known Issues
* The needs attributes shown in the build menus are not always accurate now that there is 2 versions of some needs in the same region (bread/beer/torcs/cloaks). Always refer to the stats on individual residences for the correct values. I don't think this can be fixed currently because the game "auto" generates the tooltips and wasn't designed with needs providing different stats in the same region.
