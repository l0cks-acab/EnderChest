# EnderChest Plugin

**Author**: herbs.acab  
**Version**: 1.2.0  
**Description**: Provides a personal storage space for players accessible from anywhere, similar to Ender Chests in Minecraft.

## Overview

The EnderChest plugin allows players to access a personal storage space from anywhere on the server. Each player's Ender Chest is unique and can be accessed via a simple chat command. The number of slots in the Ender Chest and the UI title can be customized through the configuration file.

## Features

- Personal storage space for each player.
- Accessible from anywhere using a chat command.
- Configurable number of slots.
- Customizable UI title.
- Permission-based access.

## Permissions

enderchest.use - Grant access to the /enderchest command

`oxide.grant <user/group> <user/group> enderchest.use`

## Installation

1. Download the `EnderChest.cs` file.
2. Place the file in your server's `oxide/plugins` directory.
3. Restart your server or load the plugin using the Oxide console command: `oxide.reload EnderChest`.

## Configuration

After the first run, a configuration file named `EnderChest.json` will be created in the `oxide/config` directory. You can modify this file to change the number of slots and the UI title.

### Default Configuration

```json
{
  "Number of Slots": 36,
  "UI Title": "Ender Chest"
}
```
