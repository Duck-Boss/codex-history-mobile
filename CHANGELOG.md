# Changelog

## 0.1.1-cli-vscode-compatible

Documentation and version-label update.

- Clarifies that this edition is compatible with both Codex CLI and VS Code/Codex session history.
- States explicitly that execution still uses `codex exec resume`.
- States explicitly that VS Code compatibility means current-session detection and shared-history visibility, not a packaged VS Code extension.

## 0.1.0-cli

Initial CLI shared-history edition.

- Mobile web UI for browsing Codex sessions.
- Sends phone input through `codex exec resume`.
- Reads session metadata from `~/.codex/state_5.sqlite`.
- Reads transcript messages from Codex rollout JSONL files.
- Optional current-session detection through Codex app-server remote-control.
- Optional Cloudflare quick tunnel.
- Optional user-level systemd services.
- Full-permission CLI execution mode documented in `SECURITY.md`.
