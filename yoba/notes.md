# [YOBA] Yuri's Online Battle Arena
- Current version: `0.7`

## Rules
- Push down the lanes and destroy the enemy nexus to win
- Fully functional towers featuring the visage of Yuri! They hurt!
- Jungle camps (neutral enemies) that drop rewards and respawn on a timer
- The jungle is covered in shroud
- You get one Yuri miner to mine Ore; it has increased strength, speed, and firepower, and can mine faster. it respawns in base when destroyed, after a  modest delay
- Creep waves that spawn on a timer in each lane and attack the enemy base. They can NOT
  be controlled by players.  You can tell which units are controlled by AI because they
  are Yuri faction units only.
- Destroy the enemy inhibitors to stop your opponent's creep waves
- Inhibitors are invulnerable until all towers in the lane are destroyed
- The nexus is invulnerable until at least one inhibitor is destroyed
- Elite bosses that will give you yuge rewards
- No superweapons, No Yuri faction, No France, No Korea, No Flying Units (except Kirov), No Ore Refineries
- Allies get Snipers and Tank Destroyers
- Soviets get all special soviet units
- Soviets get the Howitzer artillery unit


## Tips
- Turrets are strong! Do not attempt to fight another army under an enemy turret, you
  will lose most of your units.
- Turrets can NOT be repaired.  Slowly chip away at them when they are undefended.
- Use your friendly creep waves as fodder when attacking turrets.
- Use your Yminer to get ore.  It also is a strong combat unit. Try to balance resource
  gathering with using it in a push
- Your Yminer can tank a lot of turret shots.  You can use it to absorb the damage while
  your other units take down the turret.
- Use scouts in the jungle to keep tabs on enemy movement
- Attack your opponent through the jungle from different angles, denying their
  resources and vision
- The radars in the "river" (middle of the map) provide a huge radius, larger than
  vanilla YR
- Use the shroud to your advantage, hide your units to deny your opponent information

## Patch Notes

### 0.9
- Units
    > Units and battles are looking a little one-dimensional so let's spice things up a
    > bit.
    - Air Units Enabled
        - Rocketeer
        - Black Eagle
        - Siege Chopper
        - Black Hawk

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
