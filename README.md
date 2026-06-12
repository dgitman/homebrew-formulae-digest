# homebrew-formulae-digest

Snapshot store for the weekly "New Homebrew Formulae" Claude cloud routine.

`last_formulae.json` holds the list of all Homebrew formula names recorded on the last run. The routine diffs the current Homebrew formula list against this file to find newly added formulae, posts them to Slack, then overwrites this file and commits it.

## Configuration

| Setting | Value |
|---|---|
| Slack destination | `#homebrew-updates` (channel ID `C0BADV6RS76`) |
