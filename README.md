# dotfiles

[GNU Stow](https://www.gnu.org/software/stow/) で管理する dotfiles。

## セットアップ

```bash
sudo apt install stow
git clone git@github.com:tkhs0813/dotfiles.git ~/dotfiles
cd ~/dotfiles
stow bash ghostty nvim
```

## パッケージ

| パッケージ | 内容 |
|---|---|
| `bash` | `.bashrc`, `.profile` |
| `ghostty` | Ghostty ターミナル設定 |
| `nvim` | Neovim 設定 |
