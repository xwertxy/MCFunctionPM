# MCFunctionPM
This allows to make it possible for Pocketmine-MP to parse scripts that ends with `.mcfunction`.

> [!NOTE]
> 
> `.mcfunction` can only execute commands that are currently registered and contained in Pocketmine or the plugin's registered commands.
> 
> This plugin is only intended to process `.mcfunction` files in Pocketmine-MP. It does not support all Minecraft's dedicated server commands. Such as `/execute` and so on.

> [!WARNING]
> If you're unfamiliar with `.mcfunction` script syntax, you can learn more [here](https://learn.microsoft.com/en-us/minecraft/creator/documents/functionsintroduction?view=minecraft-bedrock-stable#setting-up-the-functions-folder).

# Installation
This is a plug-and-play plugin. All you need to do is the following:
1. Download [this](https://github.com/xwertxy/MCFunctionPM) plugin from github releases.
2. After that, make sure you also installed [Pocketmine-MP](https://github.com/pmmp/Pocketmine-MP) and downloaded the plugin from poggit builds or releases.
3. Put the downloaded plugin to the `plugins/` folder under your Pocketmine-MP server installation.
4. Import your .mcfunction file into `plugin_data/MCFunctionPM/mcfunctions/` and put your `.mcfunction` there.
5. Start your server, and wait until the plugin is loaded.
6. Just run `/function <file_name (without .mcfunction extension)` to run your `.mcfunction` file! It simple right?
