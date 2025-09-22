## (Sway + Waybar + Wofi + Alacritty) config files
These are my personal configuration files for **Sway**, **Waybar**, **Alacritty** and **Wofi**.  

I use these configs to customize my tiling window manager setup, including:  
- Sway layout and keybindings  
- Waybar status bar with custom styling  
- Wofi application launcher
- Alacritty terminal

> ⚡ **Note:** This setup is intentionally **clean, minimal, and simple**, focusing on usability and efficiency rather than flashy visuals. It's a great starting point for anyone learning Sway and its ecosystem.

## Cursor Theme
This configuration uses the **Capitaine Cursors** theme. 
1. Download the cursor theme:
    - Capitaine Cursors:[Download Capitaine Cursors](https://www.pling.com/p/1148692)
2. Extract it to `/usr/share/icons/`:

   ```bash
   sudo tar -xvf Capitaine-cursors.tar.gz -C /usr/share/icons/


## Installation
1. Clone this repository:
git clone https://github.com/notthatmojo/sway-config.git

2. Copy the configs to your `~/.config` folder:
   ```bash
   cp -r sway-config/sway ~/.config/
   cp -r sway-config/waybar ~/.config/
   cp -r sway-config/wofi ~/.config/  
   cp -r sway-config/alacritty ~/.config/

4. Reload Sway to apply changes:
Ctrl+Shift+C or in the terminal "swaymsg relaod"

