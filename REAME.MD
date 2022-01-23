
### Macのスタートアップ


iterm ダウンロード

。brew cask install iterm2



# ヒストリ (履歴) を保存、数を増やす
HISTFILE=~/.zsh_history
HISTSIZE=100000
SAVEHIST=100000

# 同じコマンドをヒストリに残さない
setopt hist_ignore_all_dups

# スペースから始まるコマンド行はヒストリに残さない
setopt hist_ignore_space

# ヒストリに保存するときに余分なスペースを削除する
setopt hist_reduce_blanks

# コマンドのスペルを訂正する
setopt correct

# git のカラー表示
git config --global color.ui auto

# 色を使用出来るようにする
autoload -Uz colors
colors




