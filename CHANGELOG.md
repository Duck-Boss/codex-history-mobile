# Changelog

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
