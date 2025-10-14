

<div align="center">
  <h1>skidqs hyprland dotfiles</h1>

  ![](https://img.shields.io/github/last-commit/skidqs/hyprland?style=for-the-badge&color=1E202B&labelColor=1E202B&logo=git&logoColor=FFFFFF&label=Last%20Commit)
  ![](https://img.shields.io/github/stars/skidqs/hyprland?style=for-the-badge&logo=andela&color=1E202B&labelColor=1E202B&logoColor=FFFFFF&label=Stars)
  ![](https://img.shields.io/github/repo-size/skidqs/hyprland?style=for-the-badge&color=1E202B&labelColor=1E202B&logo=protondrive&logoColor=FFFFFF&label=Size)
  ![](https://img.shields.io/github/forks/skidqs/hyprland?style=for-the-badge&color=1E202B&labelColor=1E202B&logo=git&logoColor=FFFFFF&label=Forks)
  ![](https://img.shields.io/github/issues/skidqs/hyprland?style=for-the-badge&color=1E202B&labelColor=1E202B&logo=github&logoColor=FFFFFF&label=Open%20Issues)
</div>

Welcome to my **Hyprland dotfiles** — this repository contains my personal configuration files for a **sleek**, **modern**, and **functional** Hyprland desktop environment.  
It includes a **Wlogout power menu**, **custom Rofi app launcher**, **semi-transparent Kitty terminal**, and more — all tuned for performance and style.

---

### Screenshots
![Desktop](screenshots/desktop.png)

---

### Features
- Hyprland (dynamic tiling with Dwindle layout, smooth animations, and French keyboard support)
- Waybar (custom top bar with workspaces, clock, and status modules)
- Hyprlock (elegant lock screen showing time, date, music info, and battery status)
- Hyprpaper (wallpaper manager with Pywal integration)
- Hypridle (idle management with screen lock and DPMS control)
- Wlogout (stylish power menu for lock, logout, suspend, hibernate, reboot, and shutdown)
- Rofi (minimalist app launcher with dark theme and rounded corners)
- Kitty (terminal with a semi-transparent background)
- Custom Keybindings (Super key-based controls for workspaces, windows, screenshots, and media)
- Fastfetch (system info fetch tool for terminal)
- Cava (audio visualizer for the terminal)
- Btop (modern system monitor with CPU, RAM, and process info)
- Swaync (notification center for Wayland)
- BigClock (simple desktop clock script)
- Wallust (Pywal-based color scheme generator)
- Vencord (Discord client customization)

---

### Cursor Theme
This configuration uses the [Bibata cursor theme](https://aur.archlinux.org/packages/bibata-cursor-theme)

To install Bibata on Arch-based operating systems run this ```yay -S bibata-cursor-theme```

---

### Dependencies
- Hyprland (dynamic tiling Wayland compositor)
- Waybar (customizable status bar for Wayland)
- Rofi (application launcher and window switcher)
- Kitty (GPU-based terminal emulator)
- Wlogout (Wayland logout dialog)
- Grim (screenshot utility for Wayland)
- Slurp (screen area selector for Wayland)
- WL-Clipboard (clipboard utilities for Wayland)
- Swaync (notification daemon for Wayland)
- Dunst (lightweight notification daemon)
- Picom (compositor for X11, effects like transparency)
- Swww (wallpaper setter for Wayland)
- Bibata Cursor Theme (modern cursor theme)
- JetBrains Mono (developer-friendly font)
- Fira Sans (sans-serif font)
- Font Awesome 6 Free (icon toolkit)
- Hyprlock (screen locker for Hyprland)
- Hyprpaper (wallpaper manager for Hyprland)
- Hypridle (idle management for Hyprland)
- Dolphin (file manager)
- Nautilus (file manager)
- NVIDIA Drivers (graphics drivers for NVIDIA GPUs)
- nvidia-vaapi-driver (VA-API driver for NVIDIA GPUs)
- libva-nvidia-driver (VA-API driver for NVIDIA GPUs)

---

### Keybindings
- Super + Return: Launch Kitty terminal
- Super + D: Open Rofi app launcher
- Super + Q: Close active window
- Super + Space: Toggle floating window
- Super + 1-0: Switch to workspace 1-10
- Super + G: Toggle groups
- Super + Shift + W: Select wallpaper
- Super + W: Set wallpaper
- Super + Alt + Right: Next wallpaper
- Super + Alt + Left: Previous wallpaper
- Super + Alt + Right Click: Resize window
- Super + Left Click: Move window
- Super + Mouse Scroll: Cycle through workspaces
- Super + Shift + Arrow Keys: Resize windows
- Super + Shift + Ctrl + Arrow Keys: Move window within workspace
- Super + Shift + [0-9]: Move window to workspace [0-9]
- Super + Alt + [0-9]: Move window to workspace [0-9] silently
- Super + Alt + S: Move window to special workspace
- Super + S: Toggle special workspace
- Super + Alt + G: Disable Hypr effects for GameMode
- Super + Alt + →: Next wallpaper
- Super + Alt + ←: Previous wallpaper
- Super + Alt + ↑: Next Waybar mode
- Super + Alt + ↓: Previous Waybar mode
- Super + Shift + D: Toggle theme/wallpaper colors
- Super + Shift + T: Theme select menu
- Super + Shift + W: Wallpaper select menu
- Super + Shift + A: Rofi style select menu


### Directory Structure
```
skidqs/
├── .config/
│   ├── hypr/
│   │   ├── Monitor_Profiles/
│   │   │   └── default.conf
│   │   │
│   │   ├── UserConfigs/
│   │   │   ├── 01-UserDefaults.conf
│   │   │   ├── ENVariables.conf
│   │   │   ├── Startup_Apps.conf
│   │   │   ├── UserAnimations.conf
│   │   │   ├── UserDecorations.conf
│   │   │   ├── UserKeybinds.conf
│   │   │   ├── UserSettings.conf
│   │   │   └── WindowRules.conf
│   │   │
│   │   ├── UserScripts/
│   │   │   ├── Tak0-Autodispatch.sh
│   │   │   ├── WallpaperEffects.sh
│   │   │   ├── WallpaperSelect.sh
│   │   │   ├── Weather.sh
│   │   │   └── weather.py
│   │   │
│   │   ├── animations/
│   │   │   ├── 00-default.conf
│   │   │   ├── 03- Disable Amation.conf
│   │   │   ├── END-4.conf
│   │   │   ├── HYDE - Vertical.conf
│   │   │   ├── HYDE - default.conf
│   │   │   ├── HYDE - minimal-1.conf
│   │   │   ├── HYDE - minimal-2.conf
│   │   │   ├── HYDE - optimized.conf
│   │   │   ├── ML4W - classic.conf
│   │   │   ├── ML4W - dynamic.conf
│   │   │   ├── ML4W - fast.conf
│   │   │   ├── ML4W - high.conf
│   │   │   ├── ML4W - moving.conf
│   │   │   ├── ML4W - standard.conf
│   │   │   ├── Mahaveer - me-1.conf
│   │   │   └── Mahaveer - me-2.conf
│   │   │
│   │   ├── configs/
│   │   │   └── keybinds.conf
│   │   │
│   │   ├── scripts/
│   │   │   ├── Animations.sh
│   │   │   ├── Brightness.sh
│   │   │   ├── BrightnessKbd.sh
│   │   │   ├── ChangeBlur.sh
│   │   │   ├── ChangeLayout.sh
│   │   │   ├── DarkLight.sh
│   │   │   ├── Distro_update.sh
│   │   │   ├── Dropterminal.sh
│   │   │   ├── GameMode.sh
│   │   │   ├── Hypridle.sh
│   │   │   ├── KeyBinds.sh
│   │   │   ├── KillActiveProcess.sh
│   │   │   ├── Kitty_themes.sh
│   │   │   ├── LockScreen.sh
│   │   │   ├── MediaCtrl.sh
│   │   │   ├── MonitorProfiles.sh
│   │   │   ├── PortalHyprland.sh
│   │   │   ├── Refresh.sh
│   │   │   ├── RefreshNoWybar.sh
│   │   │   ├── Sounds.sh
│   │   │   ├── SwitchKeyboardLayout.sh
│   │   │   ├── Tak0-Autodispatch.sh
│   │   │   ├── Tak0-Per-Window-Switch.sh
│   │   │   ├── Volume.sh
│   │   │   ├── WallustSwww.sh
│   │   │   ├── WaybarCava.sh
│   │   │   ├── WaybarLayout.sh
│   │   │   ├── WaybarSCripts.sh
│   │   │   ├── WaybarStyles.sh
│   │   │   ├── Wlogout.sh
│   │   │   └── sddm_wallpaper.sh
│   │   │
│   │   ├── wallust/
│   │   │   └── wallust-hyprland.conf
│   │   │
│   │   ├── application-style.conf
│   │   ├── hypridle.conf
│   │   ├── hyprland.conf
│   │   ├── hyprlock.conf
│   │   ├── initial-boot.sh
│   │   └── monitors.conf
│   │
│   ├── waybar/
│   │   ├── wallust/
│   │   │   └── color-waybar.css
│   │   │
│   │   ├── scripts/
│   │   │   └── volume.sh
│   │   │
│   │   ├── config.json
│   │   └── style.css
│   │
│   ├── wlogout/
│   │   ├── icons/
│   │   │   ├── hibernate.png
│   │   │   ├── lock.png
│   │   │   ├── logout.png
│   │   │   ├── reboot.png
│   │   │   ├── shutdown.png
│   │   │   └── suspend.png
│   │   │
│   │   ├── layout.json 
│   │   ├── style.css
│   │   └── theme.css
│   │
│   ├── rofi/
│   │   ├── themes
│   │   │   └── skidqs.theme.rasi
│   │   │
│   │   ├── wallpapers
│   │   │   └── currently no wallpapers
│   │   │
│   │   ├── config-wallpaper.rasi
│   │   └── config.rasi
│   │
│   ├── swaync/
│   │   ├── config.json
│   │   └── style.css
│   │
│   ├── kitty/
│   │   └── kitty.conf
│   │
│   ├── cava/
│   │   ├── shaders/
│   │   │   ├── bar_spectrum.frag
│   │   │   ├── eye_of_phi.frag
│   │   │   ├── normalized_bars.frag
│   │   │   ├── northern_lights.frag
│   │   │   ├── pass_through.vert
│   │   │   ├── spectrogram.frag
│   │   │   └── winamp_line_style_spectrum.frag
│   │   │
│   │   ├── themes/
│   │   │   ├── solarized_dark
│   │   │   └── tricolor
│   │   │
│   │   └── config
│   │
│   ├── fastfetch/
│   │   ├── config.jsonc
│   │   ├── config.toml
│   │   └── logo.txt
│   │
│   ├── btop/
│   │   └── btop.conf
│   │
│   ├── bigclock/
│   │   ├── requierments.txt
│   │   └── bigclock.sh
│   │
│   └── vencord/
│       └── settings.json
│
├── screenshots/
│   └── desktop.png
│
├── .bashrc
├── .profile
├── README.md
└── LICENSE
```
<div align="center"> <sub>maintained and customized by <b>@skidqs</b></sub> </div>
