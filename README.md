# Breeze Remove Mask

we offer 24/7 support in our discord server: https://discord.gg/vJ6wjuztZj

A QBCore-based FiveM resource that allows police officers to remove masks from players.

## Features
- Police officers can interact with players to remove their masks.
- Notifications for both the officer and the player when a mask is removed.
- Configurable job restrictions.

## Requirements
- [QBCore Framework](https://github.com/qbcore-framework/qb-core)
- [ox_target](https://github.com/overextended/ox_target) (for interaction)

## Installation
1. Download or clone this repository into your `[qb]` resources folder.
2. Ensure the resource is named `breeze-removemask`.
3. Add the following line to your `server.cfg`:
4. Restart your server.

## Configuration
You can modify the `config.lua` file to adjust settings such as the job allowed to remove masks.

## Usage
1. As a police officer, approach a player wearing a mask.
2. Use the interaction menu (via `ox_target`) to select the "Remove Mask" option.
3. The player's mask will be removed, and both parties will receive a notification.

## Known Issues
- Ensure all required files (`client/mask.lua`, `locales/en.lua`, `config.lua`) are present in the resource folder.
- If you encounter any issues, check the server console for warnings or errors.

## Credits
- Developed by Breeze Developments.
- Built on the QBCore Framework.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
