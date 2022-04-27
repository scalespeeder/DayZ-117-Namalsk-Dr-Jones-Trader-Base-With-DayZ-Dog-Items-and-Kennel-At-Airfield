DayZ 1.17  DayZ Dog Kennel At Scalespeeder Namalsk Trader & New "Pet Supplies" Category For Use With Dr Jones Trader

THESE FILES AND CODE SNIPPETS ARE ASSOCIATED WITH SCALESPEEDERS Namalsk TRADER FOR DR JONES TRADER.

Trader is at 6316.78 / 9436.10, at the Namalsk Airfield.

THESE ARE THE TEXT SNIPPETS FOR THOSE THAT WOULD LIKE TO MODIFY THEIR OWN TRADER CONFIG FILES,
PROBABLY BECAUSE YOU HAVE OTHER MODDED ITEMS ALREADY INCLUDED, OR DAYZ HAS MOVED BEYOND 1.7.

(HOWEVER, IF YOU ARE RUNNING A VANILLA 1.17 DR JONES TRADER MOD, SIMPLY UPLOAD THE TraderConfig.txt & TraderObjects.txt
FILES TO YOUR TRADER CONFIG / PROFILES FOLDER ON YOUR SERVER AND RESTART.)

MANY THANKS TO DR JONES, DayZ Dod Mod & Sumrak!

YOU MUST HAVE DR JONES TRADER, Nalmask Island / Survival AND DAYZ DOG MODS INSTALLED AND WORKING FOR THESE EDITS TO WORK!

PLEASE NOTE THAT NOT ALL SURVIVORS CAN "CALL" A DOG FROM A KENNEL. IF STILL SO AFTER A RESTART THAT SURVIVOR WILL
PROBABLY ONLY BE ABLE TO "CALL" A DOG ON THEIR NEXT LIFE.

ADD THIS TO THE SECOND HALF OF TRADEROBJECTS.TXT, BELOW // Namalsk Airfield:

<Object> dog_shed_small_static
<ObjectPosition>  6324.419921875,                20.71150016784668,                9477.5498046875
<ObjectOrientation> 179.16099548339845,                0.0,                0.0


save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)

ADD THESE TO TraderConfig.txt BELOW THE LAST ENTRY IN <Category> Hardware Supplies:

<Category> Pet Supplies
		dog_shed_small_kit,		*,		20,		-1
		dog_shed_wooden_kit,	*,		50,		-1
		dog_shed_big_kit,		*,		100,	-1
		dog_bowl,				*,		10,		-1
		dog_bone_toy,			*,		10,		-1
		
save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)

Please report any bugs to scalespeeder@gmail.com

Thanks and enjoy!