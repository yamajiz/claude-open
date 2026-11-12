# claude-open

Tiny https-to-`claude://` redirect page (no content).
Opens a new Claude Code session in the Claude desktop app with a fixed prompt.
Accepts exactly one of:

- `?id=<32 hex>` — start a Notion TODO row (opens in `~/Documents/Vives/ClaudeCode`)
- `?mtg=<YYYYMMDD-HHMMSS>` — sort out TODOs from that meeting's notes (opens in `~/Documents/Vives/ClaudeCode/03_projects/todo-triage`)

Nothing else is accepted; the prompt is built inside the page.
