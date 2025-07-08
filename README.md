# My-HyprLand-Setup

This repository contains my personal configuration and customization files for the [Hyprland](https://github.com/hyprwm/Hyprland) Wayland compositor. It includes scripts, user configs, monitor profiles, animation presets, and more to create a highly personalized and modular desktop experience.

## Repository Structure

- **hypr/**
  - **hyprland.conf, hypridle.conf, hyprlock.conf, etc.**: Main Hyprland, idle, and lock screen configuration files.
  - **initial-boot.sh**: Script for initial setup or bootstrapping.
  - **workspaces.conf, monitors.conf, application-style.conf**: Workspace, monitor, and style settings.
  - **animations/**: Presets for window and workspace animations.
  - **configs/**: Additional configuration files (e.g., keybinds).
  - **Monitor_Profiles/**: Profiles for different monitor setups.
  - **scripts/**: Utility scripts for system control, theming, and automation (e.g., brightness, volume, screenshots, layout switching, etc.).
  - **UserConfigs/**: User-specific overrides and customizations (keybinds, rules, startup apps, etc.).
  - **UserScripts/**: User-contributed or personal scripts (e.g., wallpaper changers, weather, calculator, etc.).
  - **wallust/**: Wallust integration for dynamic theming.
  - **wallpaper_effects/**: Wallpaper state and effects.

## Getting Started

1. **Clone the repository:**
   ```fish
   git clone https://github.com/yourusername/My-HyprLand-Setup.git
   ```
2. **Copy or symlink the `hypr/` directory to your Hyprland config location:**
   ```fish
   ln -s /path/to/My-HyprLand-Setup/hypr ~/.config/hypr
   ```
3. **Review and edit user configs in `UserConfigs/` and scripts in `UserScripts/` to match your preferences.**
4. **Restart Hyprland or reload the config:**
   ```
   hyprctl reload
   ```

## Customization

- **Animations:** Switch between different animation presets in `animations/`.
- **Keybinds & Rules:** Edit `UserKeybinds.conf` and `WindowRules.conf` in `UserConfigs/`.
- **Scripts:** Use or modify scripts in `scripts/` and `UserScripts/` for automation and system tweaks.
- **Monitor Profiles:** Quickly switch monitor layouts using profiles in `Monitor_Profiles/`.

## Contributions

Feel free to fork and adapt for your own setup! Pull requests for improvements or new scripts/configs are welcome.