# homebrew-tap

Homebrew tap for [pradyb](https://github.com/pradyb)'s command-line tools.

## Usage

```bash
brew tap pradyb/tap        # optional; `brew install` taps automatically
brew install pradyb/tap/<formula>
```

## Formulae

| Formula | Description | Source |
|---|---|---|
| `sgh` | Command-line tool for GitHub across repositories and organizations | [pradyb/sgh-cli](https://github.com/pradyb/sgh-cli) |

```bash
brew install pradyb/tap/sgh
```

## Upgrading

```bash
brew update && brew upgrade <formula>
```

## Notes

Formulae are generated and pushed automatically by each project's release workflow (GoReleaser) when a version tag is published, so changes made here by hand are overwritten by the next release. Fix formulae in the source project's `.goreleaser.yaml` instead.
