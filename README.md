# flytwerx-bridge

Release channel for the FlytWERX desktop bridge installers.

## `latest.json`

Consumed by packaged bridge builds for auto-update.

| Field | Purpose |
|-------|---------|
| `version` | Newest release (semver-ish) |
| `url` / `sha256` | Legacy Windows download (older clients) |
| `windows` | `{ url, sha256 }` for Windows `.exe` |
| `macos` | `{ url, sha256 }` for macOS `.dmg` / zip |

Source code lives in `flight-maneuver/bridge`. Build instructions are in that folder’s `README.md`.
