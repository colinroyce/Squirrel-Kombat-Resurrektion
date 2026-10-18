# Squirrel Kombat Resurrektion

> This is a mostly faithful re-creation of **Squirrel Kombat** (Monkey Farm Software, 1999), built by
> Colin Grushkin and Claude Code. If John Butler, or anyone associated with the original Monkey Farm
> Software, would like this repository and its GitHub Pages site taken down, I will do so. Just reach
> out and let me know by [opening an issue](https://github.com/colinroyce/Squirrel-Kombat-Resurrektion/issues/new)
> on this repository.

A browser recreation of **Squirrel Kombat** (Monkey Farm Software, 1999, classic Mac OS), built from
the original game's own art, sound and code.

## Play it

**▶ [Play in your browser](https://colinroyce.github.io/Squirrel-Kombat-Resurrektion/)**. Nothing to
install. Click (or press a key) to start; browsers only allow sound after a click or key press. You
need a keyboard, so play on a computer rather than a phone. Esc pauses and shows every fighter's
moves.

All original art, sound, music and game design © Monkey Farm Software, 1999. This is a free,
non-commercial fan restoration.

## What's in it

The whole original game, rebuilt from its own code:

- **All twelve fighters**, each with their four special moves and the CPU playing them as the
  original does. Military Muskrat, the secret twelfth, has to be unlocked (see below).
- **All five scenes**: Forest (log elevator, tree eyes, falling acorns, birds' nests), Field
  (butterflies), Tundra (ledges, snow and rolling snowballs), Great Wall (towers and pits) and City
  (ledges and passing flocks of birds).
- **One on One** against the CPU or a friend. With 2 Players, the screen splits in two when the
  fighters get more than a screen apart.
- **Tournament**: climb the ladder of fighters, then the win screen and the high score table (also
  on the title screen's SCORES button).
- **Practice**: hit a training dummy (nobody gets hurt) while tutorial tips cycle above.
- **Options** (sound, music, blood, difficulty, round time, keys), the **credits** (click the
  CREDITS corner of the title screen) and the original's **cheat codes**.

Not included: the original's Two on Two mode (and Practice or Tournament with 2 Players, which are
team fights), and its Mac OS alert boxes. Their buttons are shown but do nothing.

The character screen opens in Tournament mode, as the original does, so click **ONE ON ONE**
first for a single fight.

## Additions to the original

- The title screen has a second line, RESURREKTION, under SQUIRREL KOMBAT. Its letters fly in and
  wobble like the original's and are brightened copies of the original letter tiles, so the new
  line stands out. The original has no N, so that one is new art built from the original M (see
  `assets/added/`).
- Military Muskrat is unlocked by winning the Tournament, or by the original's secret key code,
  or on the Cheats page. For testing, adding `?debug` to the address unlocks him.
- A combo display under your life bar shows your key presses as you make them and flashes a
  special move's name in green when you pull it off (player 2's is on the right). Turn it off on
  the Cheats page.
- Cheats aren't hidden: Options → CHEATS switches super blood and Military Muskrat on and off, and
  shows the original's codes (type FIREMONKEY on the title screen for super blood; press left,
  jump, right, punch, uppercut, spin kick on the character screen for Military Muskrat). The
  CHEATS button is new art made from the original buttons' letters. Cheats are remembered.
- The original Tournament can't be won (its last place on the ladder is left empty), so Military
  Muskrat is the final opponent there.
- The high-score name window is a plain rebuild: in 1999 Mac OS drew its frame and button. Its
  pictures, text and layout are the original's. High scores are saved in the browser.
- Pausing (Esc) shows a move guide: the controls and every fighter's special moves in your own
  keys, one page each, with a QUIT button and the menus' squirrel cursor. In 1999 the moves were in
  a separate text file, P paused and Esc quit straight away.
- Player 2 has new default keys that fit beside player 1's on a laptop keyboard (see Controls).
- With 2 Players, fighters can also be picked by clicking: clicks take turns, player 1 first (the
  original only used the keys).
- The theme music plays on the menus but not during fights (the original played it throughout).
- The title screen has no QUIT button: there's nothing to quit in a browser.

## Controls

These are the defaults. You can change them in Options → Keys, and they're saved in the browser.
Player 1's are the original's. Player 2's are an addition: the original put player 2 on the number
pad, so the new layout mirrors player 1's to let two players share a laptop keyboard. In two-player
games player 1's uppercut becomes Left Shift (while it's still set to Space), to match player 2's.

| Action | Player 1 | Player 2 |
|---|---|---|
| Walk left / right | A / D | L / ' |
| Jump | W | P |
| Punch | S | ; |
| Kick | E | [ |
| Uppercut | Space (Left Shift with 2 players) | Right Shift |
| Spin kick | Q | O |

Other keys:

- Return or Enter starts from the title screen and confirms on every menu. Space also starts the
  scene.
- On the character screen, Esc cancels and the walk keys change fighter.
- During a fight, Esc pauses and shows the move guide. To leave the fight, click QUIT in the
  top left of the pause screen. (An addition: in the original, P paused and Esc quit straight away.)

Special moves, from the original "Special Moves" sheet (`<` back, `>` forward, `p` punch, `k` kick,
`u` uppercut, `s` spin kick, `^` jump). Tap the keys: holding one down counts once.

| Fighter | Move 1 | Move 2 | Move 3 | Move 4 |
|---|---|---|---|---|
| Ed | Machine Gun Nuts `<<<>u` | Tri Ball `>>pp` | Atomic Scatter `<p>k>` | Teleport `pkpu` |
| Speedy | Speed By `<>p` | Hit and Run `<<>k` | Scorch `<u<>k` | Fire Ball `<<>>s` |
| Ice | Ice Blast `>>pu` | Ice Fist `<<>k` | Ice Column `pku` | Sneak Attack `ps^` |
| Invisible | Toggle Visibility `<^<>p` | Boxing Glove `<<>>u` | Fire Ball `<<>>p` | Ice Ball `<<>>k` |
| Ninja | Chain Grab `<<<>u` | Random Teleport `<pkkp` | Ninja Stars `>>>k>` | Decoy `>>ppk` |
| Mech | Power Fist `<<>>u` | Electric Blast `<<<>s` | Scatter Bomb `>>p^` | Missile `<>>k` |
| Kathy | Sonic Scream `<kk>` | Tri-Heart Stasis `>>p>k` | Heart Bomb `<<upk` | Flower Power `>>sk` * |
| George | Drive By `<>pku` | Paralyzing Fart `supk>` | Cane Throw `<>kp` | False Teeth `<<p<>` |
| Philbert | Pie `<<>u` | Earthquake `pp>>u` | Stomach `pk>>` | Chew 'em up and Spit 'em out `p<<>p` |
| Super Squirrel | Fly `p<>k^` | Chase `pppu>` | Laser Eye Beam `>>>k` | Phone Booth `<k>ku` |
| Corpse | Life Drain `<<>>p` | Body Explode `u<>p^` | Dark Beam `<<>k` | Summon Bats `<ps>k` |
| Military Muskrat | Proximity Mine `p<k>u` | Grenade Attack `>>us` | Air Strike `<<pk>` | Chaser Missile `s<<^>` |

\* The sheet says `>>s>`, but the game itself only accepts `>>sk`, so that is what works here too.

## Fonts

The original draws text in the Mac's Geneva bitmap font, which can't be redistributed:

- **9 pt text** (scores, the Keys screen) uses Geneva 9.1, a FontStruct remake under the OFL. Its
  documented changes from the real font are undone. See `tools/extract/fontstruct_font.py` and
  `assets/fonts/`.
- **10 pt text** (the round timer, the hint ticker, the practice tutorial, the win screen) is
  drawn with the Geneva 9 letters as a stand-in, until a freely usable 10 pt Geneva is found.

## Running it locally

The game is plain HTML and JavaScript modules with no build step, so it runs straight from the
repository. Browsers won't load modules from `file://`, so serve the repository root over HTTP:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>. The 640×480 screen is scaled to fill the window, keeping its 4:3
shape. Adding `?debug` to the address unlocks Military Muskrat for testing.

## Repository

| Path | Contents |
|---|---|
| `index.html`, `src/` | the game |
| `assets/` | sprites, pictures, sounds, text and fonts extracted from the original archive |
| `docs/SPEC.md` | game behaviour recovered from the PowerPC binary (timings, physics, damage, AI, screens) |
| `tools/extract/` | the extraction pipeline (`.sit` → `assets/`) |
| `tools/re/` | disassembly / decompilation tools used to write the spec |
