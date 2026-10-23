# G-TEC Computer Education, Ottappalam

Official digital presence and course repository for **G-TEC Computer Education, Ottappalam centre**, located at JRJ Complex, Ottappalam, Kerala.

## Technical Structure

- **`new-site/`**: Next-generation, animation-driven responsive website engineered with custom typography, 3D CSS gyroscope, interactive course repository, and multi-discipline career trajectory matrix.
  - `index.html`: Main editorial document featuring all 10 storytelling sections.
  - `assets/css/`: Modular design system (`tokens.css`, `base.css`, `components.css`, `animations.css`).
  - `assets/js/`: ES Module application architecture (`app.js`, `courses-data.js`, `config.js`, `motion-engine.js`).
- **`scripts/`**: Automation tooling and background synchronization services.
  - `auto-git-sync.py`: Autonomous daemon that detects edits and pushes them to GitHub.
  - `start-sync.sh`: Starts the background auto-sync service.
  - `stop-sync.sh`: Stops the background auto-sync service.
  - `status-sync.sh`: Displays live daemon status, recent logs, and git status.
  - `sync-now.sh`: Forces an immediate manual stage, commit, and push.

## Automatic GitHub Synchronization

To automatically sync all edits made in Antigravity or saved locally to GitHub:

```bash
# Start background auto-sync
./scripts/start-sync.sh

# Check live sync status
./scripts/status-sync.sh

# Stop background auto-sync
./scripts/stop-sync.sh
```
