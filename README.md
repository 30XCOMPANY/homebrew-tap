# 30xcompany/homebrew-tap

Homebrew tap for [Swall](https://swall.app).

## Install

```bash
brew install 30xcompany/tap/swall
```

(That's it. `brew` auto-taps on first install.)

## Upgrade

```bash
brew update
brew upgrade swall
```

## Uninstall

```bash
brew uninstall swall
brew untap 30xcompany/tap
```

## What's here

- `Formula/swall.rb` — the Homebrew formula for the Swall CLI.
  Written automatically by GoReleaser on each release, pointing at
  the public binary mirror at
  [`30xcompany/swall-releases`](https://github.com/30xcompany/swall-releases).

## Don't use `curl | sh`?

If Homebrew isn't your thing:

```bash
# macOS / Linux
curl -fsSL https://install.swall.app | sh

# Windows (PowerShell)
irm https://install.swall.app/ps1 | iex
```

Both install the same CLI and run the same `swall setup` afterwards.

## License

MIT (same as the Swall CLI).
