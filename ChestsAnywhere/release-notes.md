[← back to readme](README.md)

# Release notes
## 1.12 (upcoming)
* Updated to SMAPI 2.0.
* Added support for the shipping bin.
* Added support for Junimo huts.
* Added Russian translations by vanja-san.
* Added warning when translation files are missing.
* Unified controller + keyboard bindings in `config.json` and enabled mouse bindings.
* Switched to SMAPI update checks.
* Fixed being able to close the menu while holding an item, which makes that item disappear.
* Fixed typo in German translations.
* Improved translations thanks to Dorian/[@d0x7](https://github.com/d0x7) (German) and yuwenlan (Chinese).

## 1.11.1
* Added Portuguese and Spanish translations by Fabilows and ThomasGabrielDelavault respectively.
* Fixed double cursor when using a controller.

## 1.11
* Updated to SMAPI 1.14.
* Added translation support.
* Added Chinese and German translations by yuwenlan and Sasara respectively.

## 1.10
* Updated for Stardew Valley 1.2.

## 1.9.1
* Updated to SMAPI 1.9.
* Backported to Stardew Valley 1.11 until 1.2 is released.

## 1.9
* Updated for Stardew Valley 1.2.

## 1.8.2
See [log](https://github.com/Pathoschild/StardewMods/compare/a8624da04e0c15e14bfb5936fcc720fe96930051...chests-anywhere/1.8.2).

* Updated to SMAPI 1.8.
* Updated new-version-available check.

## 1.8.1
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.8...chests-anywhere/1.8.1).

* Updated to SMAPI 1.3.

## 1.8
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.7...chests-anywhere/1.8).

* Updated to SMAPI 1.1.

## 1.7
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.6...chests-anywhere/1.7).

* Added support for Linux and Mac.
* Added support for opening chest overlay from inventory (mostly to allow more controller bindings).
* Added hotkeys to navigate categories.
* Added hotkey to edit chest.
* Added default controller bindings for chest UI navigation.
* Added location tile on edit screen.
* Updated minimum game and SMAPI versions.
* Fixed `B` controller button not cancelling like `ESC` key.
* Fixed various controller issues in 1.6.
* Fixed list scrolling broken in 1.6.
* Fixed navigate-chest hotkeys ignoring category.
* Fixed group list being unsorted.
* Fixed update-check error on startup adding scary error text in console.

## 1.6
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.5...chests-anywhere/1.6).

* Added Chests Anywhere UI when opening a chest directly.
* Added compatibility with most inventory mods.
* Added an option to disable hover tooltips.
* Fixed controller toggle button not closing the menu.
* Fixed chest menu behaving unpredictably after closing edit form in some cases.
* Major rewrite under the hood.

## 1.5
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.4...chests-anywhere/1.5).

* Added name tooltip when your cursor is over a chest.
* Added edit button when you open a chest directly.
* Added cancel button when editing a chest.
* Fixed fridge being accessible before you obtain it.
* Fixed error when you click an unavailable inventory slot.
* Fixed error when you open the menu but don't have any chests.
* Fixed UI not being resized when game window is resized.
* Fixed Lewis' giftbox when you start a new game being usable as a chest.
* Fixed visual issues.

## 1.4
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.3...chests-anywhere/1.4).

* Updated for Stardew Valley 1.1.
* Added chest category which lets you override the location grouping.
* Added fields to edit sort order and hide chests.
* Fixed edited chest name not saving correctly.

## 1.3
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.2...chests-anywhere/1.3).

* Added feature to rename a chest from the menu.
* Added organise button for inventory.
* Added update check on load.
* Added error if game or SMAPI are out of date.
* Improved chest/location dropdowns:
  * They can now be closed by clicking away or pressing `ESC`.
  * They now show as many items as possible (instead of 10).
  * They now show up/down arrows when there are too many items to display at once.
* Improved error handling.
* Pressing `ESC` will now close the chest UI.
* The location tab is no longer enabled by default, and may be removed in a future version.

## 1.2
See [log](https://github.com/Pathoschild/StardewMods/compare/chests-anywhere/1.1...chests-anywhere/1.2).

* Chests are now sorted alphabetically.
* Chests can now be sorted manually.
* Added item tooltips.
* Added organise button.
* Added controller support.
* Added support for rebinding keyboard/controller keys in `config.json`.
* Added hotkeys to navigate between chests.
* Fixed chests in constructed buildings (like barns) not showing up.
* Fixed farmhouse fridge not showing up.
* Location tab is now hidden if all your chests are in one place.
* Simplified default chest names (like "Chest #1" instead of "Chest(77,12)").

## 1.1
_No log available._

* Reworked UI.
* Added tabs for chests and locations.
* Added scrollable list for the two tabs.
* Chests can now be ignored.

## 1.0
_No log available._

* Initial release.
