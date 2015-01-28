funquakedm
==========

A fun deathmatch mod for the classic Quake that requires no client-side modifications. It includes several changes to the game logic using *only the default game resources*.

It is still in beta, so expect a few bugs.

The compiler used to build this source is FTEQCC, which can be found here: http://www.fteqw.com/ftedownloads/30-downloads/75-maintrunk

Installation
============
  1. Create folder named **funquakedm** inside the Quake game folder
  2. Download the **progs.dat** file from this repository and place inside the funquakedm directory (so that you'll have "[quake dir]\funquakedm\progs.dat")
  2. Run **quake.exe -game funquakedm** (or replace quake.exe with your favorite Quake client)
  3. Start your server and have fun!

Current Features
================
 * One-key instant melee attack with the axe (CoD-like) - The Axe is finally useful!
    * To assign it to the Q key, run on the console: */BIND Q "IMPULSE 20"*
 * Fired grenades/rockets/lasers will teleport. You can attack people thru teleports
 * You kick away items you won't take, as well as player heads
 * Items will fly away when caught on explosions. You can blow items away from enemies
   * You can even blast away grenades and nails on explosions
 * Players now drop all their weapons when they die (instead of a backpack)
 * Players starts bleeding when near death (< 20 health)
 * Weapons Improvements:
   * **The Axe**: is much stronger
   * **Shotgun** (now a laser gun): Laser beam that tosses the target far away (good defense)
   * **Super Shotgun**: More bullets, takes longer between shots
   * **Nailgun** (now a machinegun): Shoots very fast shotgun-like bullets (much cooler!)
   * **Super Nailgun**: Nails bounce on walls!
   * **Grenade Launcher**: Grenades explode on any contact (won't bounce)
   * **Rocket Launcher**: Rocket will go drunk at long range (kinda like actual rockets)
   * **Lightning gun**: A single super strong bolt that takes a long time to charge (like the Q3 Rail Gun)

Future/Maybe
============
  * [currently disabled] Secondary trigger for weapons. Every gun has a secondary attack (IMPULSE 21)
    * Known bug: You can't hold the trigger for multiple shots, only one shot per click
