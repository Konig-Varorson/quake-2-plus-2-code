# Quake 2 + 2
 Code for a mod for Quake II remaster for a Quake 4 themed jam.

## CHANGES MADE
- g_local.cpp:<br>
	- Expanded end of unit splash to display 16 levels instead of default 8.
- g_monster.cpp:<br>
  - Added code for summoning grenades (see parasite beta). Unfinished and not referenced.
  - Added Black Widow's powerup copying code for wider use; two versions (one for JOrg, Makron, and Black Widows; the other for Supertank, Hornet, Guardian, and Carrier). Finished but not referenced.
- g_spawn.cpp:<br>
  - Added ability to spawn finished beta strogg (unfinished betas commented out).
- g_target.cpp:<br>
	- Change muting of music on final goal of map to use N64 level victory music.
- m_arachnid.cpp:<br>
	- Added code for pain skin if present.
  - Added beta version under monster_protector.
    - Inspired by the Stream Protectors of Quake 4.
    - Protectors fire homing rockets instead of railguns. Wanted to include a blaster variant but requires reanimating.
    - Has code for new skin if files provided.
- m_berserker.cpp:<br>
  - Added beta version under monster_berserk2. Unfinished. Commented out in current version.
    - Added lightning attacks to swipe and jump. Unfinished.
    - Increased damage of jump from 8 to 16 (halfway to pre-nerf, which was 32).
- m_boss2.cpp:<br>
  - Replaced blasters with flechettes for N64 spawnflag.
- m_guardian.cpp:<br>
  - Added code for pain skin if present.
- m_insane.cpp:<br>
  - Added alternate version for non-insane marines. Unfinished. Commented out in current version. Might split into its own .cpp file at later date.
- m_parasite.cpp:<br>
  - Added beta variant inspired by Quake 4's Portal Dropper. Unfinished. Commented out in current version.
  	- Drops special grenades that spawn monster_soldier variants instead of life siphon tether. Unfinished.
- m_shambler.cpp:<br>
  - Added code for pain skin if present.
- m_soldier.cpp:<br>
  - Added a 7th variant that uses railgun, inspired by Quake 4's Tacticals.
    - Has code for new skin if files provided.
- m_tank.cpp:<br>
  - Tank Commander has reduced health but added combat armor. Added to make flechettes useful somewhere.
  - Tank Commander Guardian (N64 spawnflag) has reduced health but added body armor. Added to make flechettes useful somewhere.
- m_xatrix_fixbot.cpp:<br>
  - Added code for beta variant inspired by Quake 4's Repair Bot. Unfinished. Commented out in current version.
  	- Uses lasers instead of blaster shots. Unfinished.
  	- Heals living strogg instead of reviving corpses. Unfinished.
- p_weapon.cpp:<br>
  - Blaster and Hyperblaster fires blue lasers to match Quake 4 blaster and hyperblaster.

## ADDITIONAL INFO
Original code can be found [here](https://github.com/id-Software/quake2-rerelease-dll).
