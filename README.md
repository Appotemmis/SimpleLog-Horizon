# SimpleLog
Battlemod created by Byrth  
Ported to Ashita by Spiken  
Combat and Message log parser for Ashita v4
Update for HorizonXI

# Features
- Custom chat messages
- Condensation of targets and damage into one single line
- Filters for different messages
- Color definition for different messages
- Crafting result preview
- **(New)** In-game configuration menu

# Commands
- **/simplelog** or **/slog** - Calls the configuration menu.

# Changes
- Removed duplicate suppression at the packet level for incoming 0x28 action packets.
- Added duplicate suppression at the message output level.
- Fixes missing:
    Weapon Skill damage
    Spell messages
    Job Ability messages
    Combat animations

# Credits
- Original Battlemod is a creation of Byrth
- Action Message parsing bit by Farmboy0
- Resource files created using ResourceExtractor from the Windower Team
- And a huge thanks to the Ashita development community, you're all awesome


