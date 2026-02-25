Туда вставь:

```markdown
# Karabiner Configuration

Config directory is symlinked to:

~/.config/karabiner → ~/git/dotfiles/karabiner/config

## Setup

Stop Karabiner first.

```bash
mv ~/.config/karabiner ~/.config/karabiner.backup
ln -s ~/git/dotfiles/karabiner/config ~/.config/karabiner