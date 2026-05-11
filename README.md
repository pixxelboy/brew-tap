# pixxelboy/brew-tap

Homebrew tap for Pixxelboy tools.

## Install

Because this repository is named `brew-tap`, tap it with the explicit repository URL:

```sh
brew tap pixxelboy/brew-tap https://github.com/pixxelboy/brew-tap.git
brew install pixxelboy/brew-tap/codex-git-branch-hook
```

Then install the Codex config into a target repository:

```sh
codex-git-branch-hook install /path/to/your/repo
```

## Formulae

- `codex-git-branch-hook`: Codex CLI Git branch status-line configuration and SessionStart hook.

## Note

The shorter command `brew tap pixxelboy/tap` requires a repository named `pixxelboy/homebrew-tap`. If you want that exact command, rename this repository to `homebrew-tap` or create a separate public `homebrew-tap` repository.
