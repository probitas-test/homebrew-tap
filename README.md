# Homebrew Tap for Probitas

This is the official Homebrew tap for [Probitas](https://github.com/probitas-test/probitas).

## Installation

```bash
# Add the tap
brew tap probitas-test/tap

# Install probitas
brew install probitas
```

Or install directly:

```bash
brew install probitas-test/tap/probitas
```

## Upgrade

```bash
brew upgrade probitas
```

## Uninstall

```bash
brew uninstall probitas
brew untap probitas-test/tap
```

## Requirements

- Probitas 2 and later: none. The formula installs the prebuilt binary from the
  [GitHub Release](https://github.com/probitas-test/probitas/releases) for
  macOS or Linux (arm64 or x64).
- Probitas 1.x: [Deno](https://deno.land/), installed automatically as a
  dependency.

## Updating the formula

`Update Formula` (dispatched by a Probitas release, or run manually) reads the
latest GitHub Release. For 2.x and later it regenerates `Formula/probitas.rb`
from the release's `SHA256SUMS` with `scripts/render-formula.sh`; for 1.x it
only bumps the version.

## License

MIT
