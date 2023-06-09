# Version 1.1

- Restricted trap fix to only apply on maps that it is needed on (to prevent issues with Frozen rounds on Origins)

# Version 1.2

- Permaperks
    * Fixed assignment logic for launchers using Irony compiler (Redacted & Ancient)
    * Autorestart is no longer forced on launchers using Irony and New Pluto solo
    * Added Cash Back & Teddy permaperks to assignment sequence
- Info messages are no longer affected by playernames containing color codes

# Version 1.3

- Permaperks
    * Added sniper points to award sequence
    * Added pistol points to award sequence
    * Added instakill to award sequence
    * Added double points to award sequence

# Version 1.4

- Watermarks refactor - watermarks now align horizontally. Introduced temporal watermarks that dissapear after X amount of time (to address users complaining about First Box watermark being permanent, it will now dissapear at the end of round 19)
- Fixed moving box locations with DVAR method

# Version 1.5

- Players can no longer move after safety from using conflicting patches triggered end game
- Patch now actively removes minijug after round 15 instead of only on connect
- Restored restart enforcement (at least for now) after permaperk award
- Network frame evaluation no longer generates watermark on failure. Instead it checks again next round (effectively if game is on wrong network frame, at the beginning of each round there will be a print about bad network frame)
- Added handle for splits plugin + created a template

# Version 1.6

- Fixed HUD being cut off on aspect ratios 4:3 5:4 and 16:10
- Fixed HUD plugin causing timer and round timers to overlap
- Fixed patch safety functions not ending the game properly

# Version 1.7

- Fixed Buildable tracker zeroing after one of the players disconnected from the game
- Removed redundant includes
- Network frame fix - Now network frame fix will create prints about it's presents if used without B2OP

# Version 1.8

- Fixed an error that prevented the patch from being usable on Irony based launchers (Redacted)
