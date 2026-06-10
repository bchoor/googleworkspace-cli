---
"@googleworkspace/cli": patch
---

Add Claude Code plugin marketplace manifests (`.claude-plugin/marketplace.json` and `.claude-plugin/plugin.json`) with versions synced to the package version, so the repository can be added as a plugin marketplace in Claude Code (including Claude Code on the web). The `version-sync.sh` release script now keeps the manifest versions in sync.
