# PT Volleyball

An offline 5-on-5 arcade volleyball game with an Air Force PT-inspired theme, desktop keyboard play, mobile touch controls, and polished original art.

[Play PT Volleyball](https://vibezzzcoder.github.io/pt-volleyball/)

## Status

The current open-source build is fully playable on desktop and mobile. It supports solo play against the CPU, two players on one keyboard or with game controllers, two courts, selectable match lengths, and three solo difficulty levels. Future updates may add more characters, courts, and animation, but the current core game is complete and fun to play.

## Screenshots

![Landscape Mode](landscape-demo-screenshot.jpeg)

![Landscape Mode](landscape-demo-screenshot-2.jpeg)

![Portrait Mode](portrait-demo-screenshot.jpeg)

## Features

- Arcade 5-on-5 volleyball between Summer and Winter PT squads
- `1 Player` mode against CPU
- `2 Players` mode on one keyboard, or with USB / Bluetooth game controllers
- Two courts: Base Gym and The Track
- Selectable player character
- Polished character, ball, and court art
- Mobile touch controls (floating stick and thumb pads) for phone and tablet browsers, plus gamepad support
- A self-contained release that plays offline with no network dependencies
- Point callouts that explain why the rally ended, and a short coach that teaches by doing
- Impact feel: hit-stop, camera, a bouncing dead ball, and in-world PERFECT / NICE callouts
- Procedurally generated sound and music: applause, whistle, court acoustics, menu theme and a match bed that follows the rally
- A Settings screen (volume, assists, coach tips, screen shake, broadcast camera, vibration, motion, touch size and hand) and a pause hub

## Difficulty (1 Player)

- **Easy** — your CPU teammates reliably keep every ball that's hit into their zone alive. The only ball that's yours to win or lose is the one that comes to *you*; the opponent plays loose and is beatable.
- **Medium** — a balanced, side-to-side game where both teams trade long rallies.
- **Hard** — the CPU opponent digs your attacks and answers with fast, accurate, deliberate spikes. Your AI teammates are only competent, so you have to carry.

In **2 Players** mode each human's CPU teammates pass to their setter, and the setter sets the human — the attack is yours.

Across all modes the game follows real volleyball rules: no athlete contacts the ball twice in a row, and a side gets at most three touches before it must go over the net. The on-screen cues never invite a fault: when a press could only be a fourth touch or a double contact, nothing lights up. A serve must cross untouched—if it hits the net, lands short or out, or is touched by the serving team, the receiver wins the point immediately. A block touch is not a team touch. A rally that runs past 40 seconds is replayed (no point, same server).

Choose a Short (11), Medium (21), or Long (25) match. A team must win by two.

## Controls

Player 1:

- `W` / `A` / `S` / `D` = move
- `F` = bump (while moving with no ball in reach = diving dig; in the air = tip)
- `G` = spike (at the net with no ball to attack = block; jump early and hold = Super Spike)
- `R` = swap player
- In 1 Player you can also use the arrow keys to move, `J` / `K` / `L` or `Z` / `X` / `C` for bump / spike / swap, and `Space` to spike

Player 2:

- `Arrow keys` = move
- `,` = bump (also dives when moving, tips in the air)
- `.` = spike (also blocks at the net, charges when held)
- `/` = swap player

System:

- `Esc` / `P` = pause
- `M` = mute / unmute

Game controllers (Xbox, PlayStation, Switch Pro and most USB / Bluetooth pads):

- Left stick or d-pad = move, `A` / `LT` = bump, `B` / `X` / `RT` = spike, `Y` / `LB` / `RB` = swap, `Start` = pause
  (PlayStation: `✕` bump, `○` spike, `R1` swap; the on-screen prompts use your controller's own button names)
- The menus are navigable with the stick and `A` / `B`
- In 2 Players, one controller plays Player 2 beside the keyboard; with two controllers, the first is Player 1 and the second Player 2
- Most browsers only see a controller after you press one of its buttons

Bump and Spike are context-sensitive — the same two inputs cover every verb, so
there is nothing extra to learn or reach for:

- **Dive** — bump while on the move. Buys extended reach for a moment, then you
  have to scramble back to your feet.
- **Tip** — bump while airborne at the net. Drops the ball into the gap behind
  the block instead of hammering it.
- **Block** — spike at the net with no ball to attack. Jumps and presents a real
  contact volume above the net, marked on the tape so attackers can aim around it.
  Press as their hitter leaves the floor (the BLOCK prompt turns lime then). An
  attack that gets past the block is dug with Bump; you cannot spike it straight back.
- **Super Spike** — jump early and keep Spike held. The attack fires by itself
  when the ball arrives, and only a charged attack turns the ball lime.
- **Quick attack** — hit the ball while it is still rising, before the set peaks.
- **Serve** — hold Bump or Spike to charge, steer with movement to aim, release to
  serve. A reticle shows where it is going. Release just as the meter fills
  (**RELEASE!**) for a clean serve; hold too long and an aimed line serve starts to
  wobble. A tap is a safe float, and the auto-serve still fires if you do nothing.
  Receiving a hard serve takes a well-timed pass: a mistimed one can shank.
- **Set me** — press Spike on the ground while your team's first touch is up, and the
  setter sets you.

Contacts are graded on timing: meeting the ball cleanly reads **NICE** or
**PERFECT** and hits harder, while a mistimed contact goes soft and wandering —
weak, but never a dead ball.

Assists (on the mode screen and in Settings):

- **Landing Marker** (on by default) — a single ring showing where the incoming
  ball will land.
- **Auto Switch** (off by default) — hands control to whichever teammate is about
  to play the ball. Manual swap stays the default.

Mobile:

- Touch controls appear automatically. Put your thumb anywhere on the left side to
  get a stick. The on-screen BUMP / SPIKE buttons do the same context-sensitive dive /
  tip / block and hold the same way to charge, and a small word on each button tells
  you what it will do right now.
- Portrait and landscape are both playable. Button size and left/right-handed layout
  are in Settings.
- On a touch laptop the game starts on the keyboard, and the touch pads appear the
  first time you touch the screen.

## Offline Play

Download `index.html` from this repository and open it in a browser. That single file (about 23 MB) contains the complete game and art, so it needs no installation, server, or network connection.

## Attribution

Created by [@VibezZzCoder](https://github.com/VibezZzCoder).

PT Volleyball is an independent fan/prototype project and is not an official U.S. Air Force product. It is not endorsed by, sponsored by, or affiliated with the U.S. Air Force, the Department of the Air Force, or the U.S. Department of Defense.

The project uses fictionalized, stylized, military-inspired athletic characters and settings. No official endorsement is implied.

## License

PT Volleyball is licensed under the GNU General Public License v3.0 or later.

Copyright (C) 2026 VibezZzCoder and PT Volleyball contributors

This project is open-source free software, not proprietary software. You can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or, at your option, any later version.

This project is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

The license applies to this project's original code and assets. It does not grant rights to use any third-party trademarks, logos, seals, emblems, or official marks.

The copyright notice applies to this independent fan/prototype project's original code and original assets only, including future contributor work where applicable. It does not claim ownership of, endorsement by, or affiliation with the U.S. Air Force, the Department of the Air Force, or the U.S. Department of Defense.

See `LICENSE` for the full license text.
