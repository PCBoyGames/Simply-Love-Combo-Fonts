This is a repository for custom-made combo fonts for [Stepmania 5 theme Simply Love](https://github.com/dguzek/Simply-Love-SM5). The theme is so powerful in all scripts that it had to have been lead developed by the one and only [Dan Guzek](https://github.com/dguzek).

# FAQ
Below I answer some of the important questions that you may have about this whole project.

## What are combo fonts?
On the release of [Simply Love SM5 version 4.8.5](https://github.com/dguzek/Simply-Love-SM5/releases/tag/4.8.5), some of the genius coding mastery sparked the minds of many, and one of the newest features allowed for the customization of combo fonts. This means how the combo counter looks can be changed from Wendy (what it was forced to in 4.8.4 and below) to a different font.

## What is in a combo font?
A combo font contains an image and a configuration file. The requirements for the image, excluding certain LUA features (such as [SL4.8.5's built-in font Source Code calling for hexadecimal](https://github.com/dguzek/Simply-Love-SM5/blob/1ebad20ef4399879939b5911ec3d9e933001087c/Graphics/Player%20combo.lua#L109)), are 1234567890()/, the last three characters being used in the measure counter. However, if you don't need a measure counter, all it takes is 1234567890. This came to be a basis for [my tutorial](https://www.youtube.com/watch?v=0EcDscIRPzM) (which now that I think about it I need to redo) for players who don't use the measure counter. For the measure counter, the main map would be used, and the append would be 15x15 instead of 4x4. This is because the numbers map does not include ()/ while main does.

## Which fonts are currently here, and who made implementation possible?

This list will update as more combo fonts are created.

The names in parentheses state the alias of the user who implemented it as a Simply Love combo font. If you send a pull without changing this part of the README, I will add it here with your GitHub alias, and if it is not the same as your Stepmania/ITG player/themer/modder/memer/whatever you do with the game alias, I will replace this after you ask me to. If you troll this README, I will revert it, but add the fonts to the list as needed if they are fit to add.

*Note to self: put this list somewhere else later.*
*Other note to self: if the list becomes too big, which I feel could happen soon, sort into folders by letter/number.*

I currently have these:
* 5Muta Sans (PCBoyGames)
* A Friend In Deed (PCBoyGames)
* Aero Matics (PCBoyGames)
* Arvin (PCBoyGames)
* Blank (PCBoyGames)
* Burbank (PCBoyGames)
* Circles And Sticks (PCBoyGames)
* Comic Sans (PCBoyGames)
* Emoji (PCBoyGames) 💯🔥
* Eurostile (PCBoyGames)
* Evensong Hollow (PCBoyGames)
* Expansiva (PCBoyGames)
* FixedSys (PCBoyGames)
* Gill Sans (PCBoyGames)
* Gill Sans Ultra Bold (PCBoyGames)
* Halfvetica (PCBoyGames)
* Heartisan (PCBoyGames)
* Helvetica (PCBoyGames)
* Impact (PCBoyGames)
* Kozuka Gothic (PCBoyGames)
* Kozuka Mincho (PCBoyGames)
* La Oriental (PCBoyGames)
* LD Elementary (PCBoyGames)
* LD Trainer (PCBoyGames)
* Misuse (PCBoyGames)
* Mobile Sans (PCBoyGames)
* NK57 Monospace (PCBoyGames)
* Notype (PCBoyGames)
* Papyrus (PCBoyGames)
* Phatboy Slim (PCBoyGames)
* Polentical Neon (PCBoyGames)
* Pusab (PCBoyGames)
* Recharge (PCBoyGames)
* Rockwell (PCBoyGames)
* TW Cen MT (PCBoyGames)
* Times New Roman (PCBoyGames)
* Waltograph (PCBoyGames)
* Wingdings (PCBoyGames)
* ZB Manuscript (PCBoyGames)

## How do I install a combo font?
In the fonts folder of Simply Love, there is a folder called "_Combo Fonts" which contains folders with names of fonts. In these folders, two files are seen. One of them is the map image, and the other is the map configuration. Likewise in this repository, folders contain these two files.

To install a combo font, download both files into a new folder in "*themefolder*/Fonts/_Combo Fonts" with the same name as the folder you downloaded them from here. For example, if you downloaded Comic Sans, the folder cascade should look like "*themefolder*/Fonts/_Combo Fonts/Comic Sans" and this folder should have two files named "Comic Sans 15x15.png" and "Comic Sans.ini" for the image and configuration respectively.

## Can I request a font?
Have at it! I'll see if it has what it needs to be here (see **What is in a combo font?** for more details) and if so, I'll definitely make it for you. Contact me at simplylovecombofonts(at)gmail.com with a link to the font or a font name. If I have multiple fonts that fit or may fit a name, I will reply with links to the font possibilities, but when you find a font link before I do, I'd be glad to see it.

## Can I send in my own?
Please do! If you want to make a combo font for this repository, ensure that additional scripting (such as LUA in a seperate file) is not required, and let me know through a pull request. ***You must fill out the form for your combo font to be accepted in this repository.*** Please make sure that your font uses the main map and contains no watermarks (such as a developer logo in place of a slash), blank spaces (such as all numbers but no sign of the slash, which is left empty), [tofu](https://curiosity.com/topics/a-missing-letters-blank-box-is-called-tofu-curiosity/) (such as a blank box in place of a slash) or replacements (such as a letter A in place of a slash (yes, I've seen this sort of thing happen)) for needed characters. I will make changes if needed according to the contributing rules to ensure everything works out. As mentioned earlier, I would ideal adding the font name to the list (I might change where this is) with your Stepmania/ITG alias appended in parentheses. Again, please remember, I will revert the README if you troll it in your fork.


## I am a font owner and I do not want my font in this list. What should I do?
If you have a GitHub account, leave this as an issue using the Font Removal template. However, in such case you do not have and do not want to make an account, send an email to me at simplylovecombofonts(at)gmail.com and let me know which font to remove and I will. In a case where it is a contribution not by me, I will notify the contributor before I remove the font. These will be necessary actions so that neither any contributor nor I would face any large fees or fines over being sued. After all, I'm still in high school and jobless, as well as not an intern at any workplace, paid or unpaid.
