# AnimalHusbandry Eco

An updated version of the popular Animal Husbandry mod for the game Eco.

## Installation notes

The Client folder is only required if you're planning on rebuilding the Unity asset bundle. It does not need to be installed on your client or servers, and can be removed if you aren't working on the mod.

## Latest fixes

### Version 1.3 (Feb 20, 2023)

- Tested on Eco v0.9.7.8
- Fix incorrect gameobject active flags in unity asset bundle- this was causing players to log in at 0,0. 
- Fixed incorrect occupancy information on small pen. Negative occupancy blocks are ignored, so the mesh was moved and the occupancy updated. This is expected to shift existing pens, so please use on a new world only, or be aware your pens may move slightly.
- New icons for Small Pen and Animal Feeder more consistent with other icons in game and mod.

- Rebuilt the mod's unity package in the included Client folder, fixing issues with the meshes of the smallPen and animalFeeder that resulted in inside-out meshes, as well as removing an unused sample mesh (Polyhymnia statue).
- Created 3 world objects and 14 item prefabs from scratch and assigned icons to them, with the new meshes in separate FBX files for easier future development.
- Added instructions for future developers to work on the client side part of the mod, by bringing the Client folder into a unity installation with ModKit installed, then into a unity project and building asset bundle via the AnimalHusbandryClient scene under the "ModKit" menu.

### Version 1.2 
- Fixed lvl 6 talent selection (Icons for talents are still missing but talents have tooltips and do work)
- Added 250W Electric Power requirement to the currently Not-So-Electric Butchery Table
- Fixed lack of collision between Electric Butchery Table and other objects
- Adjusted Advanced Scrap Meat recipe to 15cal (down from 120cal)

## Why upgrade?

The Electric Butchery Table offers better yield and takes fewer calories compared to its early game counterpart, making it a more efficient option for players.

## Latest Changes

Changes as of Feb 20, 2023 have been made by [AndyKorth](https://github.com/andykorth) and are merged into the github project.
The changes as of January 3 have been made by [padmanek](https://github.com/padmanek) and can be found on [mod.io](https://mod.io/g/eco/m/animal-husbandry-97).

## Credits

This project is a collective update of the original Animal Husbandry mod created by Mysta.
