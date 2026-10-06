Forever Game Suit 3.5.0
=======================

Target client:
- World of Warcraft: Forever / Camelot
- Interface: 16001

Installation:
1. Remove or rename an older ForeverGameSuit folder first if needed.
2. Copy the folder "ForeverGameSuit" into:
   World of Warcraft\_classic_beta_\Interface\AddOns\
3. Start/restart WoW or use /reload.
4. Open the addon with /fgs, the minimap button, or the AddOn Compartment.

Included games:
- Polymorph Chicken Run
- Murloc Lotus Hunt
- Gnomeregan Block-Matrix
- Goblin Circuit Breaker / Arrow Jam

Useful commands:
- /fgs          Open/close the game hub
- /fgs status   Show campfire detection and settings
- /fgs debug    Toggle debug messages

Core features:
- Native WoW Forever-style frames, buttons, fonts and UI structure
- 60 second rounds by default, configurable in Options
- Random Game button
- Minimap button
- ESC pause / resume
- Stay-seated movement blocking while playing
- Local highscores and guild score sharing
- Confirmed highscore reset in Options > Maintenance
- Native WoW sound feedback
- SavedVariables migration/versioning support

3.5.0 Foundation Pass:
- Added data/schema migration versioning.
- Centralized round-duration access and formatting.
- Centralized score saving.
- Added reusable held-key repeat handling used by Block-Matrix A/D movement.
- Kept Options inside Forever Game Suit and grouped them into General, Round and Maintenance.
- Added runtime addon version information.

Final validation should always happen inside the current WoW Forever client because beta APIs and client behavior can change.
