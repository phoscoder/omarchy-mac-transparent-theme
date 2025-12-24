# Transparent Theme

---
## Screenshots
![term](https://github.com/zamanlof/Omarchy-Mercury-theme/blob/main/screenshots/s1.png)
![term](https://github.com/zamanlof/Omarchy-Mercury-theme/blob/main/screenshots/s2.png)
![term](https://github.com/zamanlof/Omarchy-Mercury-theme/blob/main/screenshots/s3.png)


## Install

### Method 1: Via Command Line
To install this theme, simply use the omarchy-theme-install command:

```bash
omarchy-theme-install https://github.com/phoscoder/omarchy-mac-transparent-theme.git
```

### Method 2: Via Omarchy Menu
Copy REPO URL and install via `SUPER + ALT + SPACE` → Install → Style → Theme  then enter URL

### Method 3: Manual Installation
Clone the theme files to 

```bash
git clone https://github.com/phoscoder/omarchy-mac-transparent-theme.git
```

Move to `~/.config/omarchy/current/theme`
```bash
mv omarchy-mac-transparent-theme/* ~/.config/omarchy/current/theme
```

## Waybar Installation

This theme comes with Cava Waybar Visualizer, to install it, follow these steps:

1. Move cava files to ~/.config/:
```bash
cp -r cava ~/.config/
```

2. Move waybar files to ~/.config/:
```bash
mv waybar ~/.config/
```

3. Make cava script executable
```bash
chmod 755 ~/.config/waybar/scripts/cava.sh
```

4. Restart waybar OR reboot PC:
```bash
pkill waybar && waybar &
```

5. Enjoy 😉



