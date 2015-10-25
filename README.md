# Diablo2BH.cfg
Custom MapHackConfig for SlashDiablo


**Because this .cfg aims to be complete it has a huge impact on the game performace so it should only be used if hardware is sufficient to counter the hit or areas farmed don't have 20+ items on at the same time on screen.**

**Otherwise feel free to grab item codes and lines from either BH-soft.cfg and mod the standard .cfg.**

**I suspect the cause of fps drop is that the .cfg is loaded once for each of the following: game, map, item name display(holding alt). The other possible causes would be that for each item the whole .cfg has to be run through once or that even junk items are displayed with their name shortened(hitting the game engine directly).**

**Versions:**

- BH.cfg - default with items grouped and comments (BH-hard.cfg with the unused lines removed)

- BH-soft.cfg - items with individual lines sorted by the slot they can be equiped in, each item has a comment

- BH-hard.cfg - items grouped loosely by type and the slot they can be equiped in, each group of items has a comment

- BH-bare.cfg - items grouped loosely, soon to be reduced in size to improve performance(aiming for <13KB), lacks comments/documentation

- BH-bare-junk-gone.cfg - junk also removed, LLD items can still be removed to reach 14KB

**Things left to fix:** 

- good magical item(while shopping), LLD items.    
- frame drop that amps with each item visible on screen

Thanks to Underbent and Rob for the BH and the base config.

Stuff used for the modifications:  
https://github.com/underbent/slashdiablo-maphack  
https://github.com/underbent/slashdiablo-maphack/wiki   
https://github.com/underbent/slashdiablo-maphack/wiki/Skills  
https://github.com/slippittydo/slashdiablo-maphack  

Install Rob's 0.1.5S and replace the config or use one of the .zip available under releases ( https://github.com/magicvoid1/Diablo2BH.cfg/releases )

**Color usage:**

Used colors on map are Red/Orange/Gold/Yellow/Green/Blue/Purple/White/Gray/Black

Red:Um-Gul, Mid value items

Orange:Crafting Runes&Items/Spirit/Insight Runes(TIR,ITH,TAL,RAL,ORT,THUL,AMN,SOL,HEL,KO,LEM,PUL)

Gold:Lenymo,some uniques that would be better if they were etheral, Facets and Unique Jewlery

Yellow:Rares that are worth identifying

Green:IK armor,Tal armor, griswold set items, Rune names

Blue:Magical items that can roll something useful/valuable

Purple:Vex/Ohm+ and items with equivalent or higher value 

White:RuneWord bases

Gray:Low value items and runes that are still useful

Black:LLD items(lines provided by Jeebus)
