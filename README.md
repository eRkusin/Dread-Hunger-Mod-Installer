Here's the **README** for the program based on the provided requirements:

---

# Dread Hunger MOD Installer

## Overview
This `.bat` script is an installer for mods designed for the game **Dread Hunger**. It enables you to install, uninstall, or manage two primary mods: **Totem Mod** and **Old Expanse**. These mods cannot coexist, and the installer ensures that only one mod is active at a time.

### Transparency
The script is written in `.bat` format, allowing users to inspect the process for transparency. If you don't trust the script, you can manually extract the mod files to the appropriate directories.

---

## Features
### Mod Details:
- **Totem Mod**:
  - Adds support for hosting lobbies with more than 8 players.
  - Includes a UI update for 11 players.
  - Extracts to:
    ```
    C:\Program Files (x86)\Steam\steamapps\common\Dread Hunger\DreadHunger\Content\Paks
    ```
  
- **Old Expanse**:
  - A separate map mod that is **not compatible with Totem Mod**.
  - The installer ensures Totem Mod is uninstalled before installing this mod and vice versa.

---

## Installation Options
Upon running the script, you will be prompted with the following choices:
1. **Install Totem Mod**:
   - If Old Expanse is detected, it will be automatically uninstalled before installing Totem Mod.
2. **Uninstall Totem Mod**:
   - Removes Totem Mod from your game directory.
3. **Install Old Expanse**:
   - If Totem Mod is detected, it will be automatically uninstalled before installing Old Expanse.
4. **Uninstall Old Expanse**:
   - Removes Old Expanse from your game directory.
5. **Cancel**:
   - Exits the installer.

---

## How to Use
1. **Run the Installer**:
   - Double-click the `.bat` file to start the process.
2. **Provide Game Directory**:
   - Enter the path to your Dread Hunger installation (default is provided).
3. **Choose an Option**:
   - Follow the on-screen prompts to install, uninstall, or manage mods.

---

## Manual Installation
If you prefer not to use the installer, you can manually extract the mod files:
1. **Totem Mod**:
   - Extract the contents of `totemmod_client.zip` to:
     ```
     C:\Program Files (x86)\Steam\steamapps\common\Dread Hunger\DreadHunger\Content\Paks
     ```
2. **Old Expanse**:
   - Extract the contents of `oldexpanse.zip` to the same directory as above.

Ensure you only install **one mod** at a time to avoid conflicts.

---

## Important Notes
- **Incompatibility**:
  - Totem Mod and Old Expanse cannot be installed simultaneously. The installer handles uninstallation automatically when switching between mods.
- **Transparency**:
  - The installer is written in `.bat` format to allow you to inspect its actions. You can replicate its steps manually if preferred.
