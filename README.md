最初に入れる必要があるもの

- homebrew
- XCode
- (任意) Git

コマンド
- HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -i hosts -K exec.yml
verbose
-  HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -vvvv -i hosts -K exec.yml
