# PT Volleyball

An offline 5-on-5 arcade volleyball game with an Air Force PT-inspired theme, desktop keyboard play, mobile touch controls, and polished original art.

Play it here:

https://vibezzzcoder.github.io/pt-volleyball/

## Status

The current open-source build is fully playable on desktop and mobile. It supports solo play against the CPU, two players on one shared keyboard, two courts, selectable match lengths, and three solo difficulty levels. Future updates may add more characters, courts, and animation, but the current core game is complete and fun to play.

## Screenshots

![Landscape Mode](landscape-demo-screenshot.jpeg)

![Landscape Mode](landscape-demo-screenshot-2.png)

![Portrait Mode](portrait-demo-screenshot.jpeg)

## Features

- Arcade 5-on-5 volleyball between Summer and Winter PT squads
- `1 Player` mode against CPU
- `2 Players` mode on a shared keyboard
- Selectable court presentation
- Selectable player character
- Polished character, ball, and court art with generated fallbacks
- Mobile touch controls for phone and tablet browsers
- A self-contained release that plays offline with no network dependencies

## Difficulty (1 Player)

- **Easy** — your CPU teammates reliably keep every ball that's hit into their zone alive. The only ball that's yours to win or lose is the one that comes to *you*; the opponent plays loose and is beatable.
- **Normal** — a balanced, side-to-side game where both teams trade long rallies.
- **Hard** — the CPU opponent digs your attacks and answers with fast, accurate, deliberate spikes. Your AI teammates are only competent, so you have to carry.

In **2 Players** mode the CPU teammates focus on *passing* — they set the ball up for the human players and leave the scoring to you, rather than putting the ball away themselves.

Across all modes the CPU follows real volleyball rules: it won't contact the ball twice in a row, and a side gets at most three touches before it must go over the net.

## Controls

Player 1:

- `W` / `A` / `S` / `D` = move
- `F` = bump (press while moving with no ball in reach = diving dig)
- `G` = spike (press near the net with no ball to attack = defensive block jump)
- `R` = swap player

Player 2:

- `Arrow keys` = move
- `,` = bump (also dives when moving)
- `.` = spike (also blocks at the net)
- `/` = swap player

System:

- `Esc` / `P` = pause

Bump and Spike are context-sensitive: the same input becomes a **dive** (bump while on the move) or a **block** (spike at the net when there's no ball to attack), so you always get a visible reaction.

Mobile:

- Touch controls appear automatically; the on-screen BUMP / SPIKE buttons do the same context-sensitive dive / block.
- Portrait and landscape are both playable.

## Local Play

Open `index.html` directly in a desktop browser to run the multi-file development build, or host the project folder with any static file server.

No build step is required for local play.

## Attribution

Created by [@VibezZzCoder](https://github.com/VibezZzCoder).

PT Volleyball is an independent fan/prototype project and is not an official U.S. Air Force product. It is not endorsed by, sponsored by, or affiliated with the U.S. Air Force, the Department of the Air Force, or the U.S. Department of Defense.

The project uses fictionalized, stylized, military-inspired athletic characters and settings. No official endorsement is implied.

## Contributing

Issues, suggestions, and pull requests are welcome. Please keep contributions respectful and consistent with the project's fictional, unofficial nature.

## License

PT Volleyball is licensed under the GNU General Public License v3.0 or later.

Copyright (C) 2026 VibezZzCoder and PT Volleyball contributors

This project is open-source free software, not proprietary software. You can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or, at your option, any later version.

This project is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

The license applies to this project's original code and assets. It does not grant rights to use any third-party trademarks, logos, seals, emblems, or official marks.

The copyright notice applies to this independent fan/prototype project's original code and original assets only, including future contributor work where applicable. It does not claim ownership of, endorsement by, or affiliation with the U.S. Air Force, the Department of the Air Force, or the U.S. Department of Defense.

See `LICENSE` for the full license text.
