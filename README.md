# Homebrew tap for Session Analytics

[Session Analytics](https://github.com/rokas-tarasevicius/session-analytics) gives content-free analytics for local coding-agent sessions: usage value, models, tools and activity by repository across Claude Code, Codex, Cursor, Copilot CLI, OpenCode and Gemini CLI.

```bash
brew install rokas-tarasevicius/tap/session-analytics
session-analytics             # opens http://127.0.0.1:4174
```

The formula installs the compiled package attached to each [GitHub Release](https://github.com/rokas-tarasevicius/session-analytics/releases), the same tarball as npm, and runs it with Homebrew's Node.js. It is updated by the project's release workflow after Homebrew installs, tests and audits it. Do not edit `Formula/session-analytics.rb` by hand.

Upgrade with `brew upgrade session-analytics`; uninstall with `brew uninstall session-analytics`. Uninstalling leaves the private index in the data directory (`session-analytics index path`).
