adventuretime-rus
=================

WayForward's "Adventure Time: Explore the Dungeon Because I Don't Know!" language patcher

Used utilities:

* paktools (https://github.com/artlavrov/paktools)
* ltbtools (https://github.com/artlavrov/ltbtools)
* JPEXS Free Flash Decompiler (https://github.com/jindrapetrik/jpexs-decompiler)
* wfLZEx (.anb to .png converter) may be useful too (https://github.com/meh2481/wfLZEx)

You will need resources from the original game.

Files that should be updated (fonts can be replaced with with JPEXS FFD, texts with ltbtools.py):

* global.pak: *.ttf, *.swf, localization.ltb
* menus.pak: *.swf
* shop.pak: *.swf
* tutorial.pak: *.swf 

Not translated yet:

* Loading icon (loadingicons.pak/loading.anb) - can't find tools for importing images back into .anb
* Title picture (menus.pak/mainmenu.swf) - transparency issue (upd: fixed with Sothink Decompiler)
* Sounds
