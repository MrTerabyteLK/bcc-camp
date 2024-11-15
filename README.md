# bcc-camp

> Create your own camp in RedM!

## Features
- Creates a command in your RedM Server to Set a tent with a bedroll!
- Creates a menu which you can use to decorate your camp with multiple different props!
- Creates a storage system for your camp to store your items in!
- Optional fast travel system in camps!
- Easy translations via a language locale files!
- Everything is easy to configure to your liking via the config.lua file!
- Versioner to keep upto date on updates!
- Discord Notifications
- Option to select ox_target to enteract with camp and items.
- Option to select notification system between vorp defaults and ox_lib notifications
- Config option to modify ox_lib notification design. Current design has small RedM vibe.
- Option to enable or disable discord webhook.
- Option to enable or disable ox_lib logger feature for use with  Loki, Datadog, FiveManage, Gray Log.

## How it works
- To set your tent up initally just type in chat the command you set in the config.lua file.
- After that you can walk up to your tent and press G on your keyboard to open the camp menu!
- To open storage walk up to your chest and press G!

## Dependencies
- [vorp_core](https://github.com/VORPCORE/vorp-core-lua)
- [vorp_inventory](https://github.com/VORPCORE/vorp_inventory-lua)
- [vorp_character](https://github.com/VORPCORE/vorp_character-lua)
- [bcc-utils](https://github.com/BryceCanyonCounty/bcc-utils)
- [feather-menu](https://github.com/FeatherFramework/feather-menu/releases)

## Optional Dependencies if you use ox_target feature or ox_lib notification.
- [ox_lib](https://github.com/overextended/ox_lib)
- [ox_target](https://github.com/MrTerabyteLK/ox_target) This is an modified version of ox_target to work with RedM. Use the RexShack's [ox_target](https://github.com/Rexshack-RedM/ox_target) if you use RSG-Core.

## Installation
- Make sure dependencies are installed/updated and ensured before this script
- Add `bcc-camp` folder to your resources folder
- Add `ensure bcc-camp` to your `resources.cfg`
- Restart server

## Credits
- This script is inspired by this script https://github.com/bcortezf/bc_camping
