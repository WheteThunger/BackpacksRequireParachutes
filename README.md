## Features

- Requires players to have a parachute equipped in order to access their backpack ([Backpacks](https://umod.org/plugins/backpacks) plugin on uMod)

## Permissions

- `backpacksrequireparachutes.bypass` -- Allows users to access their backpack without having a parachute equipped.

## How it works

When a player tries to access their backpack without a parachute equipped, this plugin will prevent that access and print a chat message to the player. If the player unequips their parachute, items in their backpack will be inaccessible until they equip a parachute again. The player's backpack contents may still drop on death if configured to do so, regardless of whether the player was wearing a parachute at the time. 

## Limitations

- When using the [Item Retriever](https://umod.org/plugins/item-retriever) plugin, it will appear that the player has access to the resources in their backpack (e.g., in the craft menu) even though that access is blocked.
- When using the [Backpack Button](https://umod.org/plugins/backpack-button) plugin, there is no indication of whether the backpack is accessible.

## Localization

```json
{
  "NoParachute": "You must equip a parachute equipped to access your backpack."
}
```
