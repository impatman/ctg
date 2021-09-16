# Combat Tracker Groups

![Version](https://img.shields.io/github/v/tag/arcanistzed/ctg?label=Version&style=flat-square&color=2577a1) ![Latest Release Download Count](https://img.shields.io/github/downloads/arcanistzed/ctg/latest/module.zip?label=Downloads&style=flat-square&color=9b43a8) ![Supported Foundry Versions](https://img.shields.io/endpoint?url=https://foundryshields.com/version?url=https://raw.githubusercontent.com/arcanistzed/ctg/main/module.json&style=flat-square&color=ff6400) [![Discord Server](https://img.shields.io/badge/-Discord-%232c2f33?style=flat-square&logo=discord)](https://discord.gg/AAkZWWqVav) [![Patreon](https://img.shields.io/badge/-Patreon-%23141518?style=flat-square&logo=patreon)](https://www.patreon.com/bePatron?u=15896855)

Group combatants in the combat tracker and roll for group initiative.

![ctg](https://i.imgur.com/25E5mBu.png)

## Installation

In the setup screen, use the URL `https://github.com/arcanistzed/ctg/releases/latest/download/module.json` to install the module.

## Usage

After creating a new combat, the combatants in the Combat Tracker will be instantly grouped and put into toggles. The toggles will open when they contain the current combatant.

This module also allows for an easy way to roll group initiative. If you hold the `Control` or `Shift` key while rolling the initiative of any of the combatants from the tracker, it will automatically give all of the combatants in the same group the initiative value rolled. *Please note that this doesn't work in "None" or "Initiative" mode and you **must** roll from the tracker for this to work.*

The way that the groups are created depends on the selected mode which you can change near the top of the Combat Tracker by clicking on one of the boxes. Here's how each mode works:

### None

This doesn't apply any groupings.

### Initiative

The default mode where combatants are grouped by their initiative value.

### Name

Combatants are alphabetically grouped by their name.

### Selection

Combatants are grouped by a custom selection. You can decide this by using the tool in the Token Scene controls toolbar:

![controls](https://i.imgur.com/3jtS1UI.png)

Once toggled on, whenever you select any tokens in the scene, they'll be added to the same group. It's recommended to toggle this control off after you are satisfied with the groups you've created.

### Players

Combatants are grouped by the players that have `Owner` permission for the associated Actor. If multiple players have ownership over an Actor, the associated combatant(s) will be grouped together with any other combatant which the same exact players have ownership over.

## License

Copyright © 2021 arcanist

This package is under an [MIT license](LICENSE) and the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

See the [Notice](./NOTICE.md) for attribution details.

## Bugs

You can submit bugs via [Github Issues](https://github.com/arcanistzed/ctg/issues/new/choose) or on [my Discord server](https://discord.gg/AAkZWWqVav).

## Contact me

Come hang out on my [my Discord server](https://discord.gg/AAkZWWqVav) or [click here to send me an email](mailto:arcanistzed@gmail.com?subject=Initiative%20Toggles%20module).
