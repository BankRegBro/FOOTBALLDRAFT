[README.md](https://github.com/user-attachments/files/29648498/README.md)
# The Ledger Arcade

Single-file, no-build games for the FOOTBALLDRAFT repo. Open `index.html` to pick a game.

| File          | Game              | Sport            | Leaderboard board id |
|---------------|-------------------|------------------|----------------------|
| index.html    | The Ledger Arcade | landing page     | —                    |
| gridiron.html | Gridiron Battle   | NFL              | offense / squad      |
| bowl.html     | Bowl Game Battle  | College football | college              |
| diamond.html  | Diamond Kings     | MLB (all-era)    | baseball             |
| worldxi.html  | World XI          | 2026 World Cup   | worldxi              |
| img/          | cabinet art for the landing page                        |

Notes
- Each game is a standalone page; the landing page just links to them.
- Hall of Fame scores post to one shared Cloudflare Worker (deployed separately from this repo). Each game uses its own board id above, so boards never mix.
- No tracking; no data leaves the page except a high-score post.
