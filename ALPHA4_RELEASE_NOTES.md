# NFP Editor Alpha 4

Inspect, repair and edit your **Age of Empires II: Definitive Edition** campaign progress through a visual interface. Alpha 4 adds new campaigns, localization, campaign decisions, and clearer medal controls.

## Changes since Alpha 3.1

* Added the three **Viking Sagas** chapters and their 15 scenarios: The Exiled Prince, The Hard Ruler, and The Last Viking.
* Added a language selector for all **17 game languages**, with localized campaign and scenario names from an installed game and bundled editor translations. English campaign editing remains available without game files.
* Added campaign decision editing to help players explore other recorded choices or outcomes without replaying all the earlier missions. Available choices and effects depend on the campaign and the entries already stored in the profile.
* Added a read-only **Profile Info** page with saved player name when available, profile folder account ID, progress totals, recorded runtime, and file details.
* Reworked the medal buttons with simple round designs. Inactive medals are blank and subdued; the selected tier is bright and checked. Confirmed the wooden **Easiest** medal and corrected its ordering. Easiest and Legendary controls appear where support is known, with an optional warned override elsewhere.
* Corrected scenario labels in **The Art of War**, **Victors and Vanquished**, and **Historical Battles**, and updated other English scenario titles to match the game.
* Improved profile loading and recovery of campaign progress when unrelated sections cannot be read.
* Made medal selection faster while keeping your scroll position. Improved sorting, language button layout, and text sharpness across the interface.

## Before editing

Close the game and keep an independent `Player.nfp` backup. Direct export creates a numbered `.bak` backup.

**Lowering medals or resetting progress:** the server may restore its higher completion record when the game reconnects. A local reset does not clear Relic's copy. Offline changes are not a dependable permanent fresh start.

**Unearned medals / cheating:** not recommended. Increased medals may synchronize to Relic's servers and remain there. Treat these increases as irreversible: the editor cannot undo a stored server increase, and restoring a local backup does not remove it. During a repair, select only the progress you actually earned.

Steam Cloud may replace a locally edited profile. Check the repair in-game afterward.

Unsupported difficulties may show no medal or cause unpredictable behaviour, including crashes. Use the override only if you understand the risk.

## Known limits

**Future game updates, new campaigns, or changes to the profile format may require an editor update.** Check the loaded campaign names, scenarios, and medals before exporting.

Editor translations are drafts. Localized game titles require game language files; missing titles fall back to English. Saved player names can reflect an earlier session, and recorded runtime may differ from Steam playtime.

[Download](https://github.com/cmsautter/NFP-Editor/releases/latest) · [Project](https://github.com/cmsautter/NFP-Editor) · [Report a bug](https://github.com/cmsautter/NFP-Editor/issues)

A source code release is planned so players can inspect how their profiles are read and changed.
