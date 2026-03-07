# homebrew-tap

Custom Homebrew tap for tools by [Christopher Klint](https://github.com/christopherklint97).

## Usage

```sh
brew tap christopherklint97/tap
```

### Available Formulae

| Formula | Description |
|---------|-------------|
| [clockr](https://github.com/christopherklint97/clockr) | AI-powered time-tracking CLI for Clockify |

### Install a formula

```sh
brew install christopherklint97/tap/clockr
```

Or, if you have already tapped the repo:

```sh
brew install clockr
```

## How It Works

This repository follows the [Homebrew third-party tap](https://docs.brew.sh/Taps) convention. Formula files (`.rb`) in the root directory are automatically discovered by Homebrew after tapping. Formulae are generated and updated by [GoReleaser](https://goreleaser.com/) as part of each project's release pipeline.
