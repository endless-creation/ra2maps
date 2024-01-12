# [YOBA] Yuri's Online Battle Arena
- Current version: `1.4`

## Rules
- Push down the lanes and destroy the enemy nexus to win
- Fully functional towers featuring the visage of Yuri! They hurt!
- Jungle camps (neutral enemies) that drop rewards and respawn on a timer
- The jungle is covered in shroud
- Ore Refineries disabled, build and capture Oil Derricks to generate more cash
- Creep waves that spawn on a timer in each lane and attack the enemy base. They can NOT
  be controlled by players.  You can tell which units are controlled by AI because they
  are Yuri faction units only.
- Destroy the enemy inhibitors to stop your opponent's creep waves
- Inhibitors are invulnerable until all towers in the lane are destroyed
- The nexus is invulnerable until at least one inhibitor is destroyed
- Elite bosses that will give you yuge rewards
- No superweapons, No Yuri faction, No France


## Tips
- Turrets are strong! Do not attempt to fight another army under an enemy turret, you
  will lose most of your units.
- Turrets can NOT be repaired.  Slowly chip away at them when they are undefended.
- Use your friendly creep waves as fodder when attacking turrets.
- Use scouts in the jungle to keep tabs on enemy movement
- Attack your opponent through the jungle from different angles, denying their
  resources and vision
- Use the shroud to your advantage, hide your units to deny your opponent information

## Patch Notes

### 1.4
- "Comeback" creep waves are now veteran units
- Inhibitors will heal back to 50% health
- Prism tank damage against towers/inhibitors/nexus nerfed: `200%` -> `110%`
- Reduced veteran crate radius from `11` to `6`
- Increased HP of Nexus from `6000` to `30000`
- Increased damage of inhibitor towers slightly, slightly increased AoE radius
- Added additional spread damage to normal turrets
- Increased the range of boomer subs from `22` to `25`
- Fixed a crash at end of game when players' buildings are destroyed (credit to RAZER)
- Other
    - Changed visual explosion of nexus towers
    - Adjusted point values (for end game screen) for various structures and units


### 1.3
- Increase Nexus turret health from `12000` to `20000`
- Increase Inhibitor-Turret health from `15000` to `20000`
- Inhibitor-Turret range decreased from `17` to `16`
- Inhibitor-Turret weapon reworked to do less damage but greater AoE
- Nexus turret weapon reworked to do massive single-target damage at greater range

### 1.2
- Fix boomer sub not spawning from crate
- Fix build speed
     - Global build speed now `0.5` (default `0.7`)
     - Oil derrick build speed multiplier set to `0.4` (default `1.0`)
- Increased buildable Oil Derrick generation from `24` to `25`
- Increased buildable Oil Derrick power consumption from `50` to `75`
- Increased buildable Oil Derrick cost from `2750` to `3000`

### 1.1
- Removed Ore Refinery, replaced with buildable Oil Derricks
    - Cash generation increased from `22` per 100 ticks to `24`
- Inhibitor Action Reworked
    - Destroying an inhibitor no longer stops that team's wave from spawning in that lane
    - When an inhibitor is destroyed, the creep spawn for the team that lost the inhibitor
      now spawn a STRONGER wave in that lane
- Defensive Structures
    - Turrets health increased from `6000` to `12000`
    - Turret AoE buffed slightly
         - Spread increased from `1.0` to `1.1` cells
         - Damage at max spread increased from `0.2` to `0.3`
    - Buffed tank bunkers, health increased from `1000` to `2500`
    - Inhibitor turrets removed - inhibitor building now has enhanced turret weapon
        - More damage
            - vs light armor - `75%` => `100%`
            - vs medium armor - `50%` => `75%`
            - vs heavy armor - `50%` => `75%`
            - reload time - `90` => `70`
        - More AoE
            - Spread - `1.1` => `1.5` cells
        - More range
            - `12` => `17`
        - Also they have `15000` HP
    - All turrets now have increased rate of fire, reload time decreased from `100` to `90`
- Jungle
    - Veterancy crates have a much larger radius
        - Camps that drop vet crates have a longer cooldown: `720` => `900`
    - Cash crates now give 1.5x as much cash, on average
    - Boomer subs buffed bigly
- Smudges/craters now periodically cleared from the map

### 1.0
- Converted to a 3v3 map
    - AI now controls the towers and creep waves (must be added to the lobby in positions 7 and 8)

### 0.12
- Turrets
    > Infantry rushes, particularly tesla troopers, are looking too strong.  Adding
    > AoE damage will limit their effectiveness without making them completely useless.
    > Having a little more AoE damage should give defenders more of an advantage when
    > they have a commensurate army size.
    - Added spread damage - style similar to grand cannon
        - units in the same tile (e.g. infantry occupying the same tile) will take full
          damage
        - units in adjacent tiles take 20% damage
- Vision
    > This change is intended to make it easier for teams to recapture their own tech
    > structures and avoid falling even farther behind when being pushed in.
    - Shroud is now permanently revealed around tech structures on your team's side of
      the jungle, regardless of who owns the tech structure or if it has been destroyed
    - Shroud is now permanently revealed where elite jungle bosses spawn
- Other
    - Added missing turret to bottom lane which was deleted in 0.11 - oops :)



### 0.11
- Economy/Neutral Structures
    > Making oil derricks destroyable to give a little more counterplay. Oil derricks
    > will respawn and give $3000 on capture to give the losing team some incentive and
    > reward to retake control of oil derricks.
    - Oil derricks
        - Are now destroyable
        - Respawn on a timer (after approx 2 creep waves, 1 creep wave for river/corner oils)
        - Reduced from 5 per player to 2 per player (1 in jungle, 1 in base)
        - Increased cash per tick to to `50` (up from `20`, overall player gets same amount)
            - Oils that start out as neutral generate `25`
        - Increased initial capture reward from `1000` to `3000`
        - Health increased from `1000` to `2000`
    - Machine shops
        - Will now respawn on a timer (after approx 5 creep waves)
        - Health increased from `800` to `1600`

- Other fixes
    - Removed random ore left behind from 0.9
    - Added a label to the YOBA boss timer
    - Removed Allied Ore Purifier as it no longer serves a purpose
    - Removed Soviet Industrial Plant to balance the fact that Allies have no Ore Purifier

### 0.10
- Economy
    > Total economic makeover; remove focus on ore mining and increase focus on map
    > control
    - Ore removed
    - Yuri Miners disabled
    - Soviet and Allied Ore Refineries enabled
        - No ore miners
        - Produce cash (`110%` of an Oil Derrick)
        - Cost increased from `2000` to `2750`
    - Oil Derricks
        - Are now invulnerable (can still be captured)
        - Oil derricks in lanes moved to the jungle to avoid targeting issues with
          creeps
        - There are 12 pre-captured oil derricks for each team (3 per player) in the
          jungle, while 8 are in the base area (2 per player)
        - New, neutral oil derricks added to the map in contestable areas (8 total)

- Performance
    > FPS gains
    - Removed all invisible lamp posts
    - Removed several gap generators
    - Removed objects outside of map
    - Yuri miners probably impacted performance, those are gone now too 👋

- Machine shops can now be built off of

- Other
    - Widened the choke points in front of the elite jungle bosses to make engagement
      slightly easier
    - Faction-specific units are now faction-specific again
    - Added turrets to the pool area to prevent easy backdoors with paradrop
    - Oil derrick sight reduced from `6` to `3`

### 0.9
- Units
    > Units and battles are looking a little one-dimensional so let's spice things up a
    > bit with air units. As the Yuri refinery is easy to misplace and not really being
    > used as a combat unit, the special changes around this unit/structure are being
    > removed in favor of the standard usage.
    - Air Units Enabled
        - Rocketeer
        - Black Eagle
        - Siege Chopper
        - Black Hawk
    - Howitzers removed
    - Yuri Ore Refinery now buildable and all combat buffs have been removed. An initial
      Yuri miner no longer spawns at the start of the game. The Yuri Ore Refinery is now
      part of the required build path, replacing the Allied/Soviet ore refineries.
    - Chrono Miner and War Miner disabled

- Map
    > The bigger map protects the players' main base from being destroyed, but puts
    > them much farther from the front lines and makes it harder to defend the final
    > nexus push of the opponent.  Also the opponent misses out on the joy of base
    > destruction.  Also-also the map preview radar and preview thumbnail in general
    > were not A E S T H E T I C A L L Y pleasing.
    - Map size has been reverted to the smaller (original) size in version 0.7
    - Player positions changed back to the same positions as before
    - Fix projectiles colliding with invisible lamp posts in some locations

- Jungle
    > Fix some undesirable issues with jungle
    - Dragon changed to custom Mastermind with explosive projectile weapon
      (no mind control)
    - All jungle units have anti-air
    - Tank-like jungle units can no longer be crushed by Battle Fortresses

- Force Shield
    > Force shield on turrets is a little too strong, will keep looking at this to see
    > how it plays.
    - Recharge time increased from `5` to `12`

- Turrets
    > You better heed this warning.
    - All turrets can now attack air units. They hit like a truck and will obliterate
      units that are stacked together.

- Creep Waves
    > The creep waves that patrol down lanes are a source of framerate lag. In order
    > to improve performance, the number of patrolling units in each wave is being
    > reduced from 6 to 4.  The stats of the individual units are buffed to keep the
    > overall strength of the wave about the same.
    - Reduced number of Lashers Tanks from `4` to `3`
    - Reduced number of Gatling Tanks from `2` to `1`
    - Gatling Tank buffed:
        - Reload delay decreased from `75` to `60`
        - Damange increased from `135` to `216`
        - Strength increased from `300` to `600`
    - Lasher Tank buffed:
        - Damange increased from `20` to `26`
        - Strength increased from `600` to `800`
    - Prevent players from building on creep wave patrol waypoints

- Performance
    > YOBA needs more FPS
    - Removed several buildings that can cause framerate lag
    - Removed initial movement scripts for jungle camps

- Neutral Buildings
    > Giving the jungle a stronger strategic value
    - Machine shops added for all players, pre-captured
    - Oil derricks adjusted
        - Each player gets 5
            - 2 in base
            - 1 in lane
            - 2 in jungle
        - Death explosion removed (I won't allow you to destroy my precious trees)

- Game options
    - Added several forced options, including the YR Rebalance 2.0 patch being enabled

### 0.8
- Turrets
    > Turrets are definitely too strong right now.  Eliminating AOE should allow for
    > fair engagement near a turret and being able to punish the opponent after defeating
    > their army without getting severely punished in return.
    - Turrets HP decreased from `7000` => `6000`
    - AoE removed

- Creeps
    - Fixed pathing issues

- Battle Labs
    > This change is intended to delay the end game units a bit and make teching up a
    > more nuanced tradeoff decision.
    - Battle Labs cost increased to 5000

- Shroud
    > Games have been looking pretty campy lately. These changes are intended to allow
    > scouting of lanes to give players a little more information on whether they can
    > safely attack the enemy turrets.
    - Removed off-map spy satellites for all players
    - Removed gap generators from all lanes

- Jungle
    > The buff crates are frustrating to play against because you don't know when
    > your opponents units are buffed or not.
    - Removed attack/armor/speed crates as drops and replaced with cash
    - Fixed random projectile collisions at various camps on invis lamps

- Units
    > These changes should give soviets a good option against battle forts and shore up
    > a seriously lacking ranged response.
    - Howitzer buffed:
        - Increased speed from `5` to `6`
        - Increased rotation speed from `6` to `7`
        - Increased HP from `200` to `300`
        - Now has a modified Siege Chopper cannon as primary weapon
            - Only difference is it does less damage to buildings
        - Now costs 1600

- Economy/Neutral buildings
    > It wasn't clear to players where their income was coming from.  These changes are
    > meant to make it explicit.
    - Removed income from towers
    - Removed machine shops from map
    - Removed pyschic radars
    - Each player now gets 6 oils with varying amounts of safety

- Map
    > Expanding the map to put bases behind the main nexus area.  Players losing the 
    > inhibitor and inhibitor turret shouldn't be double-punished by getting their
    > base destroyed.  Also making it harder and riskier to build outside
    > of spawn by removing the ability to build off oil derricks. Players will now need
    > to move their MCV or build a new one to expand their reach.
    - Map expanded, player spawns moved behind nexus area
    - You can no longer build off of Oil Derricks

### 0.7
- Creep Waves
    - Fixed creep waves suiciding into the enemy fountain.  They will now properly
      attack the enemy nexus towers and nexus
    - Increased speed of Gattling Tesla from `5` to `6`

### 0.6
- Turrets
    - Weapon reload time increased from `90` => `100` ticks
    - Range reduced from `13` to `12`
    - Spread increased from up to `15` units to `21` units
    - Spread damage against infantry doubled
    - Spread damage against light armor reduced from `75%` to `45%`
    - Spread damage against medium/heavy armor reduced from `50%` to `30%`

- Jungle
    - YuriBaron now drops 2 cash crates and 2 boomers instead of 4 boomers

- Creep Waves
    - Added 2 additional Lasher Tanks and 1 Gattling Tesla to each wave
    - Reduced spawn delay from `300` to `200`
    - Increased speed of lasher tank from `7` to `8`
    - Decreased speed of Gattling Tesla from `6` to `5`

- Other
    - Reduced delay of initial Yminer spawn


### 0.5
- Turrets
    - Weapon reload time increased from `80` => `90` ticks

- Units
    - Howitzer
        - Soviets can now build the howitzer to aid in long distance poking, in lieu
          of siege choppers
        - Light armor, 200 HP
        - 75 damage, 12 range (2 more than a prism tank, 1 less than a turret)
    - All allies can now build Sniper and Tank Destroyers
    - All soviets can now build Desolator, Tesla Tank, Terrorist, Demo Truck
    - American Paradrop disabled
    - Spy disabled

- Jungle (GT = Game Time, RT = Real Time)
    - Yaron spawn timer decreased from `2880` (48min GT, ~12 min RT) to `1800`
      (30min GT, ~7min RT)
    - Disk spawn timer decreased from `1440` (24min GT, ~6 min RT) to `900`
      (15min GT, ~3.5mins RT)

- Fixes
    - Removed ability to make Barracks at start of game

- Minor adjustments
    - Relocated ore and oil in middle lane
    - Moved campfire locations in jungle spawns to make crate pickups easier
    - Moved some invisible lamps for easier building (more of this to come)
    - Added rocks to some areas where invisible gap generators exist so its obvious
      where building isn't allowed

### 0.4
- Turrets
    - Weapon changed to powerful laser! wowee - Number of shots to destroy:
        - Infantry: 1
        - Light Tanks: 1
        - Heavy Tanks: 2
        - Creep Wave Tanks: 3
        - Apocalypse Tanks: 4
        - Battle Fortress: 3
        - Chrono/War Miner: 6
        - Yminers: 11

- Other
    - Added mission timer for Yuri/Baron (YARON) spawn
    - Fixed ore in bottom lane
    - Added a message when player Yminer respawns

### 0.3
- Economy
    - Added several ore mines to the map, added gems to the river area
    - Towers now generate .75 Oil Derricks worth of cash `15 cash per 100 ticks`
    - Removed oil derricks nearest the center of each lane
    - Each player gets 1.5 Oil Derricks worth of cash as a baseline `30 cash per 100 ticks`
    - Yuri Miner Slave harvest reload time increased from `75` to `125` (vanilla is `150`)
    - Yuri Miner Slave storage decreased from `8` to `4` (vanilla is `4`)


- Turrets
    - Strength increased from `5000` => `7000` HP
    - Reload time decreased from `100` => `80` ticks
- Jungle
    - Disk strength increased from `2000` => `3000` HP
    - Yuri Head strength increased from `6000` => `7000` HP

- Bugfixes
    - Fixed a bug where players aren't able to build war factory
    - Fixed creep pathing in lanes; will no longer bypass towers
    - Removed several scripts to improve performance
