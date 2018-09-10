# DBM-Profiles WotLK

This is a Wrath of the Lich King backport of [DBM-Profiles](https://wow.curseforge.com/projects/dbm-profiles) by [Lombra](https://wow.curseforge.com/members/Lombra).

AddOn description by Lombra:
> This addon implements AceDB profiles for Deadly Boss Mods, allowing you to share settings among characters. Dual spec profiling is supported.<br><br>
To manage profiles, open the Deadly Boss Mods configuration window using '/dbm', and select the Profiles category in the Options tab.<br><br>
The profile controls all DBM related settings, including core, bar and module settings.

To make this backport work on WotLK it was necessary to also change a bit of code within the `DBM-Core` module (specifically the `SetZone()` method), which is why this modified file is also included in this repository.

### Installation
1. Unzip the downloaded archive.
2. Copy the folders `DBM-Profiles` and `DBM-Core` into your `~\World of Warcraft\Interface\AddOns\` directory.
3. Confirm the file replacement dialog for the `DBM-Core.lua` file in the destination.
4. Done.

### Important Notice
Since this is a backport, there may be bugs that were not accounted for. Please make sure to backup your own config (WTF folder) beforehand if you do not want to lose anything in case something unintended happens.

If you do happen to come across any bugs or have any improvement suggestions, please create a `New Issue` within this Github repository.
