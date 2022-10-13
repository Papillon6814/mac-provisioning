最初に入れる必要があるもの

- homebrew
- XCode
- (任意) Git

コマンド
- HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -i hosts -K exec.yml
verbose
-  HOMEBREW_CASK_OPTS="--appdir=~/Applications" ansible-playbook -vvvv -i hosts -K exec.yml

注意
M1Macの場合ははじめからiTerm2をRosettaで起動する。
iTerm2のフォントはNerd Fontに変更する。 -> deviconsが表示されるようになる。
