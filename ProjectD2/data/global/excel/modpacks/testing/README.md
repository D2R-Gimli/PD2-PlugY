### Testing

* Updated: Season 10 (patch 5)
* Author: BetweenWalls / Kanzeon (post-Season 9)

Includes several developer-style cube recipes to assist in testing:
  * reroll any non-crafted item with Horadrim Orb
  * duplicate most items with Key, duplicate jewels with Jewel Fragments
  * use crafted items as ingredients for crafting recipes
  * generate set/unique items of a given base with Rancid (green) or Oil (gold) Potions
  * upgrade regular/magic item bases with Zakarum Orb
  * make items ethereal with Cartographer's Orb
  * upgrade regular item quality with Arcane Orb, and downgrade with Orb of Destruction
  * safely remove socketed gems/runes/jewels with Hel Rune
  * set the number of sockets with runes #1-6 based on the number of the rune used
  * roll specific corruption modifiers with Angelic Orb and a rune: runes #1-10 are for low-tier mods, runes #11-20 are for mid-tier mods, and runes #21-30 are for high-tier mods (see [wiki](https://wiki.projectdiablo2.com/wiki/Corruptions#Equipment_Corruptions) for order)

Most changes are in "CubeMain.txt". Some things are also changed in "UniqueItems.txt" to ensure uniques aren't limited to one per game and they can be rerolled multiple times. This may result in exclusive items (e.g. dclone/rathma uniques) being able to drop anywhere.