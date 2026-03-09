# Session Breakdown Extension

Interactive TUI that analyzes `~/.pi/agent/sessions` and shows usage over last 7/30/90 days: sessions, messages, tokens, cost by model.
Includes a GitHub-contributions-style calendar graph.

## Install

```bash
pi install npm:@fnnm/pi-session-breakdown
```

```bash
pi install git:github.com/fnnm/pi-session-breakdown
```

## Usage

- Command: `/session-breakdown`
- No default keybinding

Run the command to open the interactive TUI. Use arrow keys to navigate ranges and measurement modes.

## Credits

Forked from: [mitsuhiko/agent-stuff](https://github.com/mitsuhiko/agent-stuff/blob/main/pi-extensions/session-breakdown.ts)
Original author: Armin Ronacher (mitsuhiko)

## License

MIT
