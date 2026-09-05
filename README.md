# dotfiles-i3

i3/X11 desktop configuration and supporting scripts.

## Contents

- `i3/` — i3 configuration
- `i3status-rs/` — i3status-rs configuration
- `scripts/` — i3/X11-specific utilities
- `setup` — installs the configuration via symlinks

## Setup

From the module directory:

```sh
./setup
```

The setup uses `$XDG_CONFIG_HOME`, falling back to `~/.config`, and installs executable scripts into `~/.local/bin`.

The module is intended to be used as a submodule of the main dotfiles repository, but can also be installed independently.
