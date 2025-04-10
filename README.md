# Monster names AIO name entries bundle - Installation Guide

## Description  
Adds **__name entries__** for **Tempered**, **Arch-Tempered**, and **Frenzied** variants to all **large monsters**, **small monsters**, **endemic life**, and **fishes** **__in Monster Hunter Wilds' localization file__**.
**__Useful for modded quests, avoid the blank mission objectives (like "Hunt the")__**.

---  

## Supported Languages:
✅All **vanilla languages** inclued in Monster Hunter Wilds are supported by this mod.
This includes:
- Japanese
- English
- French
- Italian
- German
- Spanish
- Russian
- Polish
- Portuguese (Brazil)
- Korean
- Traditional Chinese
- Simplified Chinese
- Arabic
- Latin American Spanish
Please write me if i made any semantic error.

---  

## Installation requirements:  

- [**REFramework**](https://github.com/praydog/REFramework-nightly/releases). (Required for first installation method)  
- A basic understanding of words. (placing files in the correct directory)  
- To not be offended by my jokes. (fully optional) *You surely have more braincells than me anyway.*  

---  

## Installation guide:  
**You can install this mod using two different methods:**

### Method 1: Loose Files (requires REFramework - clean method)
﻿- Open "**re2_fw_config.txt**" with any text editor and search for the the following line:
  `LooseFileLoader_Enabled=`
﻿  Then change it's value to "**true**". (**__LooseFileLoader_Enabled=true__**)
﻿  *Note: The config file is generated after the game is ran at least once with REFramework, if you just installed this last or if the config file is missing, please start the game ﻿then close it once you reached the main menu.*
- Extract the loose version in the game's directory (drop the "natives" folder from the zip into your game folder (where "**MonsterHunterWilds.exe**" is located))
  You can check there is a "**EnemyText.msg.23**" file at this path:
﻿  *MonsterHunterWilds\natives\STM\GameDesign\Text\Excel_Data\EnemyText.msg.23*
- You can run the game.

### Method 2: Pak File (does NOT require REFramework - also gross method)
*Note: REFramework is still required for the quest loaders so....*
- Drop the "**re_chunk_000.pak.sub_000.pak.patch_00x.pak**" from the zip to the game's directory (where "**MonsterHunterWilds.exe**" is located).
- Rename the file by replacing the "**x**" at it's end with the next available number:
﻿  For example, if the last existing file is
﻿  "**re_chunk_000.pak.sub_000.pak.__patch_002.pak__**",
﻿  rename the mod file to:
﻿  "**re_chunk_000.pak.sub_000.pak.__patch_003.pak__**"
﻿  *Note: Make sure it does not overwrite any other mod.*
﻿  **__!!! WARNING !!! If the game is updated, a new "patch_00x.pak" might be created, overwriting the mod, it's why this method is not adviced, you risk to loose the ﻿﻿﻿track.__**

---  

## Uninstallation:  
**Use the same method you used for the installation.**

### Method 1: Loose Files
- Remove the following file:
﻿  "**\natives\STM\GameDesign\Text\Excel_Data\EnemyText.msg.23**"
﻿  Or directly the "**natives**" folder *if that's the only mod you installed*.

### Method 2: Pak File
- Remove the file "**re_chunk_000.pak.sub_000.pak.patch_00x.pak**" you installed and *renamed* in the installation guide.
﻿﻿  **__!!! WARNING !!! If the game is updated, a new "patch_00x.pak" might be created, if you remove this file instead of the mod's one, you will break the game, a file ﻿﻿﻿integrity check will be needed.__**

---  

## Recommended mods:  
- [Event Quest Saver-Loader-Editor by Melodyhalftone](https://www.nexusmods.com/monsterhunterwilds/mods/1087): ✅Compatible

---  

## Compatibility:  
- ✅Compatible with any mod that doesn't overwrite "**\natives\STM\GameDesign\Text\Excel_Data\EnemyText.msg.23**"

---  

## Credits:  
- **REFramework:** [Praydog](https://github.com/praydog)
- **REMSG Converter:** [Dtlnor](https://github.com/dtlnor/REMSG_Converter)
