# Reword Manager

[![Endpoint Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fapi.runelite.net%2Fpluginhub%2Fshields%2Finstalls%2Fplugin%2Freword-manager&style=for-the-badge&label=Active%20installs)](https://runelite.net/plugin-hub/ejaz-karim)

A plugin for [RuneLite](https://runelite.net/plugin-hub/ejaz-karim)

This project uses Adoptium Eclipse Temurin 11 as its JDK.

## Introduction

Reword Manager will allow for Chat messages, Items, NPCs, Objects, Options, Player and Clan names to be reworded.

## Examples

NPC List

	Wise Old Man,Example
	Vannaka,Example1
 	Bob,Example2
 	Zaff,<col=ff0000>Zaff</col>

Entering data in the lists must be in the CSV format ***x,y*** and is case-sensitive. You **MUST** use a new line for new entries. It is possible to recolour the names of NPCs, Items, etc. with HTML Hexadecimal colour codes.

## Exceptions and Limitations

Known bug: Rewording player & clan names may not work if the name contains a space. Rewording player names may not work if the player is an ironman.

Messages containing `</col>` or `<br>` will not be modified. E.g. Checking Serpentine helm scales, Casting a line in Barbarian fishing.

Some special characters in the Chat list may not be reworded.

If you are trying to modify a message in the Chat list containing `<`,`>` it will appear as `<lt>`,`<gt>` and may not be reworded.

You can't use Swap left click teleport with the Menu Entry Swapper plugin if you have reworded the option text for the teleport that is selected as the left click option. This is because RuneLite associates the name with the action.

Rewording the teleport submenu text option will break the submenu with the Menu Entry Swapper plugin. The teleports in the submenu dropdown can't be reworded.
