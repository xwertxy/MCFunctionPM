# MCFunctionPM
This allows Pocketmine-MP to parse scripts ending in `.mcfunction`.

> [!NOTE]
> 
> `.mcfunction` can only run commands that are currently registered and included in Pocketmine commands or the plugin registered commands.
> This plugin is solely meant to parse `.mcfunction` files in Pocketmine-MP. It is not support for minecraft dedicated server commands support.

# Installation
This is a plug-and-play plugin. All you need to do is the following:
1. Download [this](https://github.com/xwertxy/MCFunctionPM) plugin from github releases.
2. After that, make sure you also installed [Pocketmine-MP](https://github.com/pmmp/Pocketmine-MP) and downloaded the plugin from poggit builds or releases.
3. Put the downloaded plugin to the `plugins/` folder under your Pocketmine-MP server installation.
4. Import your .mcfunction file into `plugin_data/MCFunctionPM/mcfunctions/` and put your `.mcfunction` there.
5. Start your server, and wait until the plugin is loaded.
6. Just run `/function <file_name (without .mcfunction extension)` to run your `.mcfunction` file! It simple right?
