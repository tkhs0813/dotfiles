# dotfiles

[GNU Stow](https://www.gnu.org/software/stow/) で管理する dotfiles。

## セットアップ

```bash
sudo apt install stow
git clone git@github.com:tkhs0813/dotfiles.git ~/dotfiles
cd ~/dotfiles
stow bash ghostty nvim claude
```

## パッケージ

| パッケージ | 内容 |
|---|---|
| `bash` | `.bashrc`, `.profile` |
| `ghostty` | Ghostty ターミナル設定 |
| `nvim` | Neovim 設定 (LazyVim) |
| `claude` | Claude Code 設定 (`settings.json`, skills) |

## スキルの追加

```bash
# 1. スキルファイルを配置
cp my-skill.md ~/dotfiles/claude/.claude/skills/

# 2. シンボリックリンクを更新
cd ~/dotfiles && stow -R claude
```
