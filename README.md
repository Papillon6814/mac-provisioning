## Prerequisites

Install below before running `run.sh`
- homebrew
- XCode
- (Optional) Git

## Commands

- Just to run installation
```
HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -i hosts -K exec.yml
```

- With verbose logs
```
HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -vvvv -i hosts -K exec.yml
```

## Note
I prefer Rosetta, so you'd rather better open iTerm2 using Rosetta.
You need to change fonts to Nerd Font in iTerm2, so that devicons are displayed properly.

MacOS defaults
https://macos-defaults.com/finder/fxpreferredviewstyle.html#set-to-clmv

```
defaults read
```
