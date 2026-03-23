# Homebrew Tap

Custom [Homebrew](https://brew.sh) tap for formulae by [David Olrik](https://mandse.dk).

## Installation

```sh
brew tap davidolrik/tap
```

## Available Formulae

| Formula                                                    | Description                             |
| ---------------------------------------------------------- | --------------------------------------- |
| [ssh-inspect](https://github.com/davidolrik/ssh-inspect)   | Show SSH configuration for a hostname   |
| [subspace](https://subspace.olrik.dev/)                    | Transparent proxy with upstream routing |

### SSH Inspect

Install:

```sh
brew install davidolrik/tap/ssh-inspect
```

### Subspace

Install:

```sh
brew install davidolrik/tap/subspace
```

Run as a background service:

```sh
brew services start subspace
```

## Updating

Formulae in this tap are automatically updated via [GoReleaser](https://goreleaser.com) when new releases are published upstream.
