# Better Kitty Terminal

A personal fork of [Kitty](https://github.com/kovidgoyal/kitty) by Kovid Goyal.

I liked the original terminal but wanted to make improvements for my own use. This fork reflects my own way of using the terminal — the way I like it.

As I build new features or change things, this project evolves with me.

## Changes so far

- **Mouse tab reordering** — click, hold and drag tabs to reorder them.

## Installation

### Build from source

**Dependencies (Ubuntu/Debian):**

```bash
sudo apt install \
  libharfbuzz-dev liblcms2-dev libxxhash-dev libsimde-dev \
  libdbus-1-dev libxcursor-dev libxrandr-dev libxi-dev \
  libxinerama-dev libgl1-mesa-dev libxkbcommon-x11-dev \
  libx11-xcb-dev libfontconfig-dev libssl-dev libpython3-dev \
  libcairo2-dev wayland-protocols
```

**Go >= 1.24.0** is required. Install from [go.dev](https://go.dev/dl/).

**Build & run:**

```bash
make
./kitty/launcher/kitty
```

## Configuration

Reads `~/.config/kitty/kitty.conf` — fully compatible with existing Kitty configurations.

## License

GPL v3

## Credits

Based on [Kitty](https://github.com/kovidgoyal/kitty) by Kovid Goyal.
