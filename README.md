# pixxelboy/brew-tap

Homebrew tap for Pixxelboy tools.

## Install

Because this repository is named `brew-tap`, tap it with the explicit repository URL:

```sh
brew tap pixxelboy/brew-tap https://github.com/pixxelboy/brew-tap.git
brew install pixxelboy/brew-tap/codex-gitbranch-hook
```

Then register the global Codex hook:

```sh
codex-gitbranch-hook install --global
codex-gitbranch-hook doctor
codex-gitbranch-hook preview
```

## Formulae

- `codex-gitbranch-hook`: Codex CLI Git branch SessionStart hook.
- `codex-git-branch-hook`: compatibility formula for the previous formula name.

## Note

The shorter command `brew tap pixxelboy/tap` requires a repository named `pixxelboy/homebrew-tap`. If you want that exact command, rename this repository to `homebrew-tap` or create a separate public `homebrew-tap` repository.
