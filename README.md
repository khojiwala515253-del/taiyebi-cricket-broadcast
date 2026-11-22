# Taiyebi Cricket Broadcast - Public Scoreboard Default

The website homepage (`/`) and `/broadcast` show the spectator scoreboard. The controller is at `/control`.

## Render deployment
- Build command: `echo ready`
- Start command: `python taiyebi_broadcast_logo_embedded.py`
- Runtime: Python

Deploy the project on Render as a Web Service using the included `render.yaml` or these commands. Share the homepage URL (or `/broadcast`) with spectators. Do not share `/control`.

**Important:** `/control` is not password-protected in this version. Anyone who knows or guesses the path can access it. Keep it private; for a public match, add authentication before publishing.
