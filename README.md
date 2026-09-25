# BeardLib-Editor

BeardLib-Editor is a tool that allows you to edit and create things like maps & environments.

## Installation
1. Install [SuperBLT](https://superblt.znix.xyz)
2. Install [BeardLib](https://modworkshop.net/mod/14924)
3. After downloading the editor by clicking `Code` -> `Download ZIP`, unzip the contents of the ZIP file in the mods folder of the game.
4. Launch the game and click `Yes` on the dialog that pops up. These files are required.

If you install the dev branch, make sure you have the latest BeardLib commit https://github.com/diesel-modding/PAYDAY-2-BeardLib it's possible that branch uses unreleased features not found in the public (MWS) version.

## Guides
https://www.youtube.com/playlist?list=PLRSASA7UrjTsX1WWG6kStRTK51DKSEDPn \
https://wiki.modworkshop.net/books/beardlib-editor-tutorials \
https://www.payday2maps.net/guides/

## Report a Bug/Request a Feature
https://github.com/diesel-modding/BeardLib-Editor/issues

## Ask a Question
Payday 2 Maps Discord Server - https://discord.gg/fn62qaq \
Painday 2 (maker of the video tutorials) Discord Server - https://discord.gg/RNBUnrN7 \
ModWorkshop Discord Server - https://discord.gg/Eear4JW \
GitHub Discussion - https://github.com/diesel-modding/BeardLib-Editor/discussions

## Help Needed
We're looking for developers that will work together on the editor.

Your best friend in all of this is knowing how to look for the pieces of code that correspond to parts of the editor. Be it in the decompiled files of the game or the editor's code.

Make sure you are using a good code editor like VSCode. This will allow you to quickly search the code and the decompiled code of the game https://github.com/steam-test1/Payday-2-LuaJIT-Complete.

Make sure you have an empty file called developer.txt in the mods folder (turns on the console) and run the following command: blt.forcepcalls(true) - this let's you not crash the moment you hit a random error.

The editor is equipped with a code refresher, editing any file will refresh parts of the editor.

The real editor uses what is called in the decompiled code 'EWS' ('External Window System', based on wxWidgets). Unfortunately porting this kind of GUI is easier said than done. Instead of that we use https://github.com/diesel-modding/PAYDAY-2-BeardLib/wiki/MenuUI and have a class that simplfies the process of creation a little https://github.com/diesel-modding/BeardLib-Editor/blob/master/Classes/MenuUIExt.lua

## Plugin Source
https://github.com/diesel-modding/BeardLib-Editor-Plugin
