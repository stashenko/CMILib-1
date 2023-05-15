# CMILib

## Introduction

This plugin helper, or **library**, is a handy tool that allows us to easily manage common phrases, hex colours and more. Instead of each plugin having to write its own code for these features, this library allows them to share this functionality, as well as providing an API for other developers to extend their own plugin features. 

This reduces the overall size of other plugins, and makes updating and maintaining plugins much easier and more consistent.

**NOTE:** This library is required by ALL Zrips' plugins.

## Library Updates

It's heavily recommended to always keep this library up to date. You can download the latest builds from:

- [Developer's Official Website](https://www.zrips.net/cmilib/)
- [Spigot Releases](https://www.spigotmc.org/resources/87610/)

## Plugins Using This Library

- [CMI](https://www.spigotmc.org/resources/cmi-298-commands-insane-kits-portals-essentials-economy-mysql-sqlite-much-more.3742/) version 9.x and up
- [Residence](https://www.spigotmc.org/resources/residence-1-7-10-up-to-1-19.11480/) version 5.x and up
- [MobFarmManager](https://www.spigotmc.org/resources/mob-farm-manager-supports-1-7-10-up-to-1-19-hopper-support.15127/) version 2.x and up
- [SelectionVisualizer](https://www.spigotmc.org/resources/selection-visualizer.22631/) version 3.0.4.0 and up
- [TryMe](https://www.spigotmc.org/resources/tryme.3330/) version 7.x and up
- [BottledExp](https://www.spigotmc.org/resources/bottledexp.2815/) version 3.x and up
- [JobsReborn](https://www.spigotmc.org/resources/jobs-reborn.4216/) version 5.x and up
- [TradeMe](https://www.spigotmc.org/resources/trademe-with-api-to-create-custom-trades-1-7-10-1-19-x.7544/) version 6.1.0.0 and up
- [Recount](https://www.spigotmc.org/resources/recount.3962/) version 3.5.0 and up

## Installation Instructions

**As with all plugin changes, make sure to `/stop` your server and make a full backup first.**

Download the latest version of the library from a release website mentioned, and place it in your server's `plugins/` directory.

To avoid conflicts, it is recommended to load this library without the plugins that depend on it first, this will ensure that any issues that arise aren't related to the library itself but rather with the dependent plugin, you should then report it to it's developer so they update it to match the library changes.

Your Server should start with no issues. After the first startup, a new folder called `CMILib` will be created in your server's `plugins/` folder. This folder contains the library's configuration files. You can edit these files to your liking, but it's not required.
If you're working on translations, please make sure to send a pull request to this repository.

At this stage, you should run another `/stop` to add the plugins that depend on this library and proceed with their setup as required.

## Bugs and Suggestions

You're free to clone and make a pull request to offer bug fixes and/or code suggestions. If you don't know how you can report bugs and suggestions as an issue (if no existing one exists yet) under the Issues tab here on Github.

## Support

You can request support from other Community Members on the [Zrips Community Discord](https://discord.gg/dDMamN4).

Please do check [the FAQ page](https://www.zrips.net/cmilib/faq/) out first, before asking questions
