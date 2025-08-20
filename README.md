# setcolors

A self-managing script that uses pywal to generate color schemes from images and applies them to Ubuntu GNOME.

## Usage
```bash
# Apply colors only
setcolors -i /path/to/image.jpg

# Apply colors and set as background
setcolors -i /path/to/image.jpg -b
```

## Features
- Auto-installs/removes pywal using pipx as needed
- Zero permanent Python packages
- Works with GNOME Wayland
- Updates fastfetch colors automatically
