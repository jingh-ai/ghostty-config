# ghostty-config
My personal configuration and setup script for the Ghostty terminal


```
ghostty-config/
├── config          # Main Ghostty configuration file
├── .gitignore      # Git ignore rules
└── README.md       # This file
```

## Quick Install

### Option 1 — Symlink (recommended)

Keeps your config in sync with this repo automatically.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/ghostty-config.git ~/ghostty-config

# Create the config directory if it doesn't exist
mkdir -p ~/.config/ghostty

# Symlink the config file
ln -sf ~/ghostty-config/config ~/.config/ghostty/config
```

### Option 2 — Copy

```bash
git clone https://github.com/YOUR_USERNAME/ghostty-config.git
cp ghostty-config/config ~/.config/ghostty/config
```

## Keybindings

| Shortcut | Action |
|----------|--------|
| `⌘ N` | New window |
| `⌘ T` | New tab |
| `⌘ W` | Close tab/split |
| `⌘ D` | Split right |
| `⌘ ⇧ D` | Split down |
| `⌘ ⌥ ←/→/↑/↓` | Navigate splits |
| `⌘ ⇧ ] / [` | Next / previous tab |
| `⌘ ⌃ F` | Toggle fullscreen |
| `⌘ = / -` | Increase / decrease font size |
| `⌘ 0` | Reset font size |
| `⌘ ⇧ ,` | Reload config |


## Useful Commands

```bash
# List all built-in themes
ghostty +list-themes

# Show all config options with default values and docs
ghostty +show-config --default --docs | less

# Validate your current config
ghostty +show-config

# View man page
man ghostty
```

## Resources

- 📖 [Official Docs](https://ghostty.org/docs)
- ⚙️ [Config Reference](https://ghostty.org/docs/config/reference)
- 🎨 [Built-in Themes](https://ghostty.org/docs/config/reference#theme)
- 💬 [GitHub Discussions](https://github.com/ghostty-org/ghostty/discussions)

## License

MIT — feel free to fork and adapt.