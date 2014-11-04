funquakedm
==========

A fun deathmatch mod for the classic Quake that requires no client-side modifications, only the server needs to load it.
It includes several changes to the game logic using only the default game resources.

Please note this is in very early development phase.

The compiler used to build this source is FTEQCC, which can be found here: http://www.fteqw.com/ftedownloads/30-downloads/75-maintrunk

Current Features
================
 * Alternate fire for weapons. Every gun will have a secondary attack (IMPULSE 21)
    * To assign it to the right click, run on the console: */BIND MOUSE2 "IMPULSE 21"*
 * One-key CoD-like melee attack with the axe (IMPULSE 20)
    * To assign it to the Q key, run on the console: */BIND Q "IMPULSE 20"*
 * You can now shoot grenades/missiles thru teleports
 * You kick away items you won't take, as well as heads
 * Items will fly away when caught on explosions (you can blow items away from enemies)
 * Player bleeds when near death (< 20 health)
 * Weapons
   * Axe is much stronger (2 hit kill a non-armored player)
   * Lightning gun is now a single super strong bolt that takes a long time to charge
   * Shotguns take longer to shoot but are much stronger