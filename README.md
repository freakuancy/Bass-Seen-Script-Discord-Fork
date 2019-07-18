# Bass-Seen-Script-Discord-Fork
Bass' Seen Script for Eggdrop, Forked to respond to users over a discord &lt;-> IRC bridge such as reactiflux

This will respond to discord-IRC bridge users as well as normal IRC users. You will need to edit the first line
of the script to specify the name of the bot serving as the discord<->IRC bridge.

Note: It is recommended you disable loading of the bseen updater script. If you do not, a future update will 
replace this version.


Instructions:

1. Edit script, specify name of discord bridge bot
2. Place in ../eggdrop/scripts/
3. Edit eggdrop.conf, add the line:

  source scripts/bseen1.4.3-discord.tcl

4. If you are using a previous version of Bass' Seen script, remove
   or comment out the line loading the bseen updater.
5. Rehash or restart bot

