== Author Info ==
Created by: LYQ(Virose) @ Feenix(wow-one.com)
Created on: Warsong @ Feenix(wow-one.com)
Thread Info: http://www.wow-one.com/forum/topic/82432-warriorhud/
BIG THANKS TO: Oejesten & Lulleh from Emerald Dream @ Feenix for testing everything :)

== How To Configure ==
 - /whud    		  				- to display all possible options
 - /whud Ragebar					- to display all possible Ragebar options
 - /whud Overpower					- to display all possible Overpower options
 - /whud Cooldowns					- to display all possible Cooldown options
 - /whud Alerts						- to display all possible misc Alert options
 - /whud reset						- to reset your WHUD Settings
 
 to change variables use it like '/whud Ragebar Y -200'
 
 Use the listed commands to check ingame all possibilities.

== Update Notes ==
 > 1.8 (30. July 2014)
		- added the event "PLAYER_DEAD" to hide the Ragebar if the player died
		- fixed the chatcommand to disable/enable fading
		- Overpower/Revenge/Shield Bash/Pummel will now only get triggered by the combatlog - therefor their names are removed from WHUD_IMPORTANTSPELLS
		- excluded the Shine until it's working 100% bug-free
		- included the Cooldown Clock animation instead of the shine
		- if Overpower is usable but it's still on CD the Overpower alert will now have: 60% Alpha and if you're using the text mode the color is darker as well
 
 > 1.7 (28. July 2014)
		- fixed chat command for CD trinkets&fadein
		- changed fadeout option to fadein
		- the overpower alert will disappear after you've used Overpower
		- added few other alerts like Battle Shout/Salvation/Weightstones
		- shorten & cleaned a lot of code esp. in frame creation, resetting and setting
		- added Racial 'Perception' (Human)
	
 > 1.6 (20. July 2014)
		- implemented Trinket CD compatibility (yay!)
		- quick hotfix for CDslot 4-6 to not display CDs twice
		- quick hotfix for Cooldowns seperation of Pummel/Shield Bash
		- (overpower alert) lowered the icon mode - icon from 75x75 to 65x65
		- (overpower alert) default timer color is now yellow, it turns red when it's 1 or less seconds
		- (overpower alert) fixed an issue at switching between both modes when the other timer didn't hide
 
 > 1.5 (20. July 2014)
		- overpower works now in PvE too, added the needed Event "CHAT_MSG_SPELL_SELF_DAMAGE"
		- overpower alert will now have a timer
		- overpower alert has now two modes "text" and "icon". icon is a new mode which just displays a big OP Icon.
		- added the Cooldown fadeout option and raised the CD Iconslots up to 6 (2rows x 3)
		- fixed a bug in the cooldown code which could mess pummel/shield bash CDs up
 
 > 1.4 (18. July 2014)
		- fixed the overpower msg change command
		- fixed the command for cooldowns flashtime
	
 > 1.3 (17. July 2014)
		- added Mortal Strike/Shield Slam (oops :D)
		- seperated the Pummel/Shield Bash CDs (stance dependent, like overpower/revenge for now)
		- updated the command infos to make it more clear
		- added racial cooldowns
		- fixed the editmode for the ragebar
 
 > 1.2 (17. July 2014)
		- fixed the Overpower alert icon
		- reworked the entire frames, seperated ragebar/overpower/cooldowns
		- reworked entire variables
		- added scale/transparency/strata customizability
		- reworked entire commands
		- made the entire code warrior-only
		- added "editmodes" for every element, will gets triggered if you change variables like X Y etc

 > 1.1 (16. July 2014)
		- fixed an Issue with the CD OnUpdate function after loading the addon
		- fixed the enabling/disabling functions
		- changed the framestrata of WHUD_Frame to HIGH
		- making the ragebar scaleable
		- added chat messages if you change the value of something