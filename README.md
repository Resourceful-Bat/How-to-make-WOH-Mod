# Introduction
World of Horror Modding allows users to add extra events, characters, etc. to their World of Horror gaming experience. While there are several different things you can add, we will stick with a custom event for now. Furthermore, we will assume that you are using Windows 10 and have World of Horror on your PC.  
Also note that "string" just means to input your changes in the "" within your mod

# Steps

## Create a Text Document

* Right click on your screen and create a new text document. Name it however you wish, but be sure to keep it relevant to what type of event you are going for.

## Editing Your Document
Fill in the appropriate parameters  
* **name** - Input event's displayed name         (string)
* **author** - Input your name/username           (string)
* **contact** - Not visible in game. Is meant to let the creator of the game know who you are in case they would like to add your event to the game (string)
* **about** - Text that explains your event when you hover over it in-game (string, keep it short)
* **flavor** - The text that shows up when you encounter the event during a playthrough (string, it auto-wraps but add # for a new line)
* **location** - The place where you event occurs (string, use these: downtown, school, hospital, seaside, forest, mansion, village, apartment, ithotu, athyola, gozu, atorasu)
* **options** - The amount of options available to the player (string, "1", "2" or "3")

* **image** = Path to the image file (string, relative, leave "" for a generic location-based image)


* **optiona/optionb/optionc** - Your options. Keep is short because of space on screen (string)
* **testa/testb/testc** - The stat checked when an option is chosen (string, use these: strength, dexterity, perception, knowledge, charisma, luck or story for no test and auto-success. You can also use funds1 and funds2, these will check if player has at least 1/2 FUNDS and will auto-deduct them if the check passes)
* **successa/failurea/etc** - Text result of an optionz (string)
* **winprizea/failprizea/etc** - Result of an option (string, currently: stamina, reason, doom, experience, funds, injury, curse, ally, item)
* **winnumbera/failnumbera/etc** - The number by which the win/failprize is affected. (string,  leave "" for injury, curse and ally (random effect), ITEM NAME for item (for example "STEAK KNIFE")


## Saving Your File

* **It is important to save the file as a ".ito" file instead of a ".txt" file.** Your mod won't load at all if you do not change the file extension to ".ito" . Don't worry about editing the file later. You can still edit the file later if the file is a ".ito" file.

## Where to Save

*  For a windows user, follow this path to get to where you will save your mods.
*  C:\Users\ADMIN\AppData\Local\wohgame  ( In place of ADMIN should be your username.)
*  Now that you are in the "wohgame" folder, create a new folder called "custom". This will house all of the mods you are going to make.  
![Parameters](/Step.png)

# And You're Done!

Congratulations! You've now created your first mod for World of Horror! For more info on creating mods, join the World of Horror Discord by clinking this [link](https://t.co/3Hu11wPe1y?amp=1/ "Discord link") or by typing https://t.co/3Hu11wPe1y?amp=1/ into a web browser.
