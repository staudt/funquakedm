funquakedm
==========

A fun deathmatch mod for the classic Quake that requires no client-side modifications.
It includes several changes to the game logic using only the default game resources. Only the server has to load it.

Please note this is in very early development phase.

The compiler used to build this source is FTEQCC, which can be found here: http://www.fteqw.com/ftedownloads/30-downloads/75-maintrunk

Current Features
================
 * One-key CoD-like melee attack with the axe (IMPULSE 20)
    * To assign it to the Q key, type this on the console: **/BIND Q "IMPULSE 20"** (or add to the config.cfg file)
 * You can now shoot thru teleports (credit: http://www.inside3d.com/qctut/lesson-24.shtml)
 * You kick away items you won't take, as well as heads
 * Items will fly away when caught on explosions (you can blow items away from enemies)
 * Player bleeds when near death (< 20 health)
 * Weapons
   * Axe is much stronger (2 hit kill a non-armored player)
   * Lightning gun is now a single super strong bolt that takes a long time to charge
   * Shotguns take longer to shoot but are much stronger