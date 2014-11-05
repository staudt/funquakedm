funquakedm
==========

A fun deathmatch mod for the classic Quake that requires no client-side modifications, only the server needs to load it.
It includes several changes to the game logic using only the default game resources.

Please note this is in very early development phase.

The compiler used to build this source is FTEQCC, which can be found here: http://www.fteqw.com/ftedownloads/30-downloads/75-maintrunk

Current Features
================
 * Secondary trigger for weapons. Every gun has a secondary attack (IMPULSE 21)
    * To assign it to the right click, run on the console: */BIND MOUSE2 "IMPULSE 21"*
 * One-key instant melee attack with the axe (CoD-like) - The Axe is finally useful!
    * To assign it to the Q key, run on the console: */BIND Q "IMPULSE 20"*
 * You can now shoot grenades/missiles thru teleports
 * You kick away items you won't take, as well as heads
 * Items will fly away when caught on explosions (you can blow items away from enemies)
 * Players now drop all their weapons when they die (instead of a backpack)
 * Players bleeds when near death (< 20 health)
 * Weapons
   * Axe is much stronger (2 hits will kill a non-armored player)
   * Super Shotgun:
      * 1st trigger: 1 shell shot (like the regular shotgun, slightly slower and stronger)
      * 2nd trigger: Double shell shot (stronger than the old super shotgun)
   * Rocket Launcher
     * 1st trigger: Good ol' Missile at short/mid range. Goes drunk at long range (like actual rockets)
     * 2nd trigger: Drops a Rocket like a grenade that explodes on contact
   * Lightning gun is now a single super strong bolt that takes a long time to charge
