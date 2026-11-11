# Hello Nicky

A mod for **Hello Neighbor** (Steam) with the roles swapped: **you are the Neighbor**, and Nicky is the one sneaking into
your house. He works through each act's puzzles on his own, on his way to your basement. Catch him first.

<!-- video / screenshots here -->

## What's in it
- **Acts 1, 2 and 3**, each with Nicky's own way through the house, his hiding spots and his escapes.
- **You are the Neighbor**: first person with his arms and run, or third person (F4).
- **Nicky fights back**: he hides in wardrobes and under beds, throws things through windows to get out, and knocks your cameras down with tomatoes.
- **Your tools**: tomatoes, glue, a vacuum, bear traps, and up to 10 security cameras with a monitor.
- **Live in the house**: watch TV, nap on the sofa, sleep, take a bath, exercise.
- **Several catches**: a slap, a hush, an ear pinch, a tackle, the waist grab.
- **The story from the other side**: the game's cutscenes from the Neighbor's side, Aaron in Act 1's films, a new Act 3 ending and end credits.

## Install
1. Download `HelloNicky-1.0.0.zip` from [Releases](../../releases) and unzip it anywhere (keep the folder until you uninstall).
2. Close Hello Neighbor and double-click **`Install.bat`**. It finds the game through Steam, or asks for its folder.
3. Start Hello Neighbor from Steam as usual. New Game starts Act 1; Select Act has Acts 1 to 3 unlocked.

The installer adds [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (the mod loader) unless you already have it, and the mod.
No game file is changed. **Uninstall:** double-click `Uninstall.bat`. It removes the mod, and also UE4SS if this
installer put it there.

## Keys
| Key | What it does |
|---|---|
| Q / R / V / B | tomato / glue / vacuum (hold, or tap to toggle) / bear trap (3 at most) |
| F | check the wardrobe or bed you face (Nicky hiding there is caught) |
| X | put a security camera on the wall you look at (10 at most) |
| Z | camera monitor on / off; Left / Right arrow or X = next camera |
| G / H | use nearby furniture (TV, sofa, bed, bath, armchair, sink); G again = get up |
| T | exercise |
| F4 | third person on / off |
| F5 | next running-arms look |
| F3 | on-screen text (what Nicky is up to) on / off |
| F9 | restart the round |
| Shift+F9 | jump to the Act 3 basement finale |
| F6 | Nicky's round on / off |
| F8 | the whole mod on / off (back to the normal game) |

## Trouble?
- Mods that also change the Neighbor or the player (Hello Playtime, Tom & Jerry, ...) fight with this one: use one at a time.
- Logs: `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\nicky_lua.log` and `ue4ss\UE4SS.log` in the same folder. Please attach both to an issue.
- A game update can break UE4SS mods. Tested with the Steam version of November 2026.

## Credits
- Made by **Gaming with ACK**.
- Aaron's 3D model: ["Aaron Peterson Search Rescue"](https://sketchfab.com/3d-models/aaron-peterson-search-rescue-8ffdde502c044df2801a77a65b359747) by **werikas** (Sketchfab Standard licence), re-rigged and animated for this mod; shipped only inside the built pak.
- Everything else you see and hear is Hello Neighbor's own content, loaded from your installed game.
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT).
- Built with the help of an AI coding agent (Claude Code, Anthropic).

The mod's code is under the MIT licence. Unofficial fan mod, not affiliated with or endorsed by tinyBuild or Dynamic Pixels.
