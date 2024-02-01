# Rivals City
- Current version: `0.4.0`

## Info / Rules
- 3v3
- The map contains 5 control points which can be captured by either team
- Capturing a point spawns a "node" (Psychic Amplifier) which fires at the enemy Nexus
  - The node does a small amount of damage over time to the nexus
  - The more nodes your team controls, the more damage you will do to the enemy Nexus
- To capture/control a point:
  - At the start of the match: destroy the enemy team's prism tower
  - When there is already a node there: destroy the enemy node
- First team to destroy the enemy Nexus wins
- Controlling the middle point (Point A) will periodically spawn reinforcements for the
  enemy team, controlled by an AI player
- The Nexus:
  - The Nexus can be attacked directly by player units but it is heavily defended
    by turrets unique to this map
  - The Nexus has 2 stages, each has 15,000 HP
  - When the first stage of the nexus is destroyed, the losing team will periodically
    receive reinforcement units for the rest of the match
- Build speed is increased globally
- Players can build on controlled points
- Tech structures will respawn after being destroyed



## Patch Notes

### 0.4.0
- Add a turret to protect each base
- Fix double spy sat bug
- Fix AI gap generators failing to respawn
- Fix turrets not shooting at air units

### 0.3.1
- Remove "Reveal all map" trigger actions at end of game
    - Give each player a spy sat (modded for no power requirement) instead
- Reduce initial delay of AI reinforcement waves from `1000` to `250`

### 0.3.0
- Change mirage tank reinforcements to unit crates
    - Mirage tank spawner creates an internal error if any player is not present
    - V3, MCVs, and Miners will not drop from crates

### 0.2.0
- Fix multiple gap generators being buildable in sidebar
- Remove naval yards for all houses
- Change armor from `steel` to `concrete` for nodes and turrets
- Changed node weapon projectile to a missile so it is always visible
- Fixed middle oil derricks not re-building
- Reduced delay for subsequent AI reinforcements from `1000` to `500`
- Increased build speed
- Reduced size of first 2 AI reinforcement waves to fix problems standing on one
  waypoint
- Added 1 additional precaptured oil derrick for all players
