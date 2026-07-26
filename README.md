# quickstarter

Personal checklist for setting up a new MacBook.

## 1. Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 2. Install apps

```bash
brew install --cask middleclick caffeine codex claude bentobox cleanshot fluidvoice presentify linearmouse
```

**Important:** for Claude Code, use the `@latest` cask instead of the default one:

```bash
brew uninstall claude-code && brew install claude-code@latest
```

### App list

| Cask | Link |
|---|---|
| middleclick | https://formulae.brew.sh/cask/middleclick |
| caffeine | https://formulae.brew.sh/cask/caffeine |
| codex | https://formulae.brew.sh/cask/codex |
| claude | https://formulae.brew.sh/cask/claude |
| bentobox | https://formulae.brew.sh/cask/bentobox |
| cleanshot | https://formulae.brew.sh/cask/cleanshot |
| fluidvoice | https://formulae.brew.sh/cask/fluidvoice |
| presentify | https://formulae.brew.sh/cask/presentify |
| linearmouse | https://formulae.brew.sh/cask/linearmouse |
