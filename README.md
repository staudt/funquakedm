funquakedm
==========

A fun deathmatch mod for the classic Quake that requires no client-side modifications, only the server needs to load it.

It includes several changes to the game logic using *only the default game resources*.

It is still in beta, so expect a few bugs.

The compiler used to build this source is FTEQCC, which can be found here: http://www.fteqw.com/ftedownloads/30-downloads/75-maintrunk

Current Features
================
 * Secondary trigger for weapons. Every gun has a secondary attack (IMPULSE 21)
    * To assign it to the right click, run on the console: */BIND MOUSE2 "IMPULSE 21"*
    * Known bug: You can't hold the trigger for multiple shots, only one shot per click
 * One-key instant melee attack with the axe (CoD-like) - The Axe is finally useful!
    * To assign it to the Q key, run on the console: */BIND Q "IMPULSE 20"*
 * Grenades/rockets/lasers teleports. You can attack people thru teleports
 * You kick away items you won't take, as well as heads
 * Items will fly away when caught on explosions. You can blow items away from enemies
   * You can even blast away grenades and nails from enemies
 * Players now drop all their weapons when they die (instead of a backpack)
 * Players starts bleeding when near death (< 20 health)
 * Weapons
   * The Axe is stronger
   * Shotgun (now a laser gun):
      * 1st trigger: Laser beam (like the enforcer's)
      * 2nd trigger: Triple drunk Laser beams (will spread in random directions)
   * Super Shotgun:
      * 1st trigger: single shell shot (like the regular shotgun, slightly slower and stronger)
      * 2nd trigger: Double shell shot (stronger than the old super shotgun)
   * Nailgun (now a machinegun):
      * 1st trigger: Shoots very fast shotgun-like bullets (much cooler!)
   * Super Nailgun (no changes yet)
   * Grenade Launcher (no changes yet)
   * Rocket Launcher
     * 1st trigger: Good ol' Rocket at short and mid range. Rocket will go drunk at long range (kinda like actual rockets)
     * 2nd trigger: Drops a Rocket (like a grenade) that explodes on contact
   * Lightning gun:
     * 1st trigger: A single super strong bolt that takes a long time to charge (like the Q3 Rail Gun)
