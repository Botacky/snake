# Snake

A feature-rich Snake game that runs entirely in a single HTML file — no dependencies, no build step.

**[Play it live →](https://botacky.github.io/snake)**

## Modes

| Mode | Description |
|------|-------------|
| **Classic** | Pure snake. Eat, grow, survive. Borders wrap. |
| **Maze** | Navigate shifting walls that refresh every 20–30 s. A blinking Shrink food appears during each transition. |
| **Chaos** | Random special foods spawn throughout. Once you hit 30 pts, a **Purple Chasing Snake** joins the game. |

## Special Foods

| Shape | Name | Effect |
|-------|------|--------|
| ▲ Yellow | Boost | Speed ×1.7 for 5 s · +2 pts |
| ◆ Cyan | Freeze | Permanent −20% speed (stacks) · 0 pts |
| ● Gold | Bonus | Instant +3 pts |
| ▼ Pink | Shrink | Halve your length · +2 pts |
| ✚ Orange | Challenge | +5 length, 2× pts for 5 s, then −5 length |

## Controls

| Input | Action |
|-------|--------|
| Arrow keys / WASD | Move |
| Space / P / click | Pause / Resume |
| Swipe | Move (mobile) |

## Other Features

- **Quest system** — unlocks at 30 pts in Classic & Chaos; eat 5 numbered objects in order for a bonus
- **Leaderboard** — top 10 scores per mode, stored locally
- **Speed levels** — Beginner (0.75×), Normal (1×), Pro (1.5×)
- **Extra life** — one revive per game via a mock ad

## Running locally

Just open `index.html` in any browser. No server needed.
