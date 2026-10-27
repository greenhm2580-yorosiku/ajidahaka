# Ajidahaka

**A simultaneous-turn, three-way tactics battle that runs right in your browser.**
Read your opponents, hide behind walls, and outscore two CPU teams in a short match.

▶ **Play now:** https://greenhm2580-yorosiku.github.io/ajidahaka/

No install, no sign-up. It's a single HTML file.

## What is it?

Three teams (you, CPU-A, CPU-B) fight on a 9×9 board with walls. Each team controls **two pieces**. Every turn, you choose an action for each of your pieces, and **all six pieces act at the same time**. Win by reading what the others will do, not by reacting to it.

## How to play

1. **Pick two weapons**, one for each of your pieces, and choose the CPU difficulty (Easy / Normal / Hard).
2. **Each turn, choose an action for each piece:** move, attack, guard, charge, or wait. When both pieces are set, press **Decide**.
3. **Everything resolves together:** all movement happens first, then attacks are checked from the new positions. If your target steps out of range or behind a wall, your attack misses.
4. **You can't see through walls.** Enemies you can't see show up as a faint "?" at their last known position. (Fog can be turned off.)

### Scoring

- **+1 point** for each enemy piece you defeat.
- The match lasts a **random 40–50 turns**. When time is up, you get **+2 points for each of your pieces still standing.**
- The team with the **most points wins**. Ties go to the higher total remaining HP.
- The match also ends early if only one team is left.

### Weapons

| Weapon | Range | Damage | Notes |
|---|---|---|---|
| Melee | adjacent | 40 | Hits hard. Strong against snipers. |
| Gun | 3 | 20 | Can't shoot through walls. Strong against melee and shields. |
| Sniper | 2–8 | 50 | Pierces guard. Needs a turn to charge; moving or getting hit breaks the charge. |
| Shield | adjacent | 30 | Blocks melee and gun fire from the direction you face, and reflects melee damage. Can't be used two turns in a row. Snipers pierce it. |

### Controls

| Key | Action |
|---|---|
| Arrow keys / WASD | Move (Shift + arrow: shield direction) |
| Q / E | Switch between piece 1 and piece 2 |
| 1 / 2 / 3 / 4 | Attack / Guard / Charge / Wait |
| Enter | Decide |

You can also click the buttons and the board.

## Notes

- Built with plain HTML, CSS, and JavaScript. No external libraries (only Google Fonts).
- The game is a work in progress. Feedback and ideas are welcome via [Issues](../../issues).
