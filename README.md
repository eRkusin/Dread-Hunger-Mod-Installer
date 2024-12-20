# README

## Table of Contents
- [English Version](#english-version)
- [Czech Version](#czech-version)

---

## English Version

### Dread Hunger MOD Installer

#### Overview
This `.bat` script is an installer for mods designed for the game **Dread Hunger**. It enables you to install, uninstall, or manage two primary mods: **Totem Mod** and **Old Expanse**. These mods cannot coexist, and the installer ensures that only one mod is active at a time.

##### Transparency
The script is written in `.bat` format, allowing users to inspect the process for transparency. If you don't trust the script, you can manually extract the mod files to the appropriate directories.

---

#### Features

##### Mod Details:
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

#### Installation Options
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

#### How to Use
1. **Run the Installer**:
   - Double-click the `.bat` file to start the process.
2. **Provide Game Directory**:
   - Enter the path to your Dread Hunger installation (default is provided).
3. **Choose an Option**:
   - Follow the on-screen prompts to install, uninstall, or manage mods.

---

#### Manual Installation
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

#### Important Notes
- **Incompatibility**:
  - Totem Mod and Old Expanse cannot be installed simultaneously. The installer handles uninstallation automatically when switching between mods.
- **Transparency**:
  - The installer is written in `.bat` format to allow you to inspect its actions. You can replicate its steps manually if preferred.

---

## Czech Version

### Instalátor MODů pro Dread Hunger

#### Přehled
Tento `.bat` skript slouží jako instalátor modů pro hru **Dread Hunger**. Umožňuje instalovat, odinstalovat nebo spravovat dva hlavní mody: **Totem Mod** a **Old Expanse**. Tyto mody nejsou kompatibilní a instalátor zajišťuje, že vždy bude aktivní pouze jeden z nich.

##### Transparentnost
Skript je napsán ve formátu `.bat`, což uživatelům umožňuje kontrolovat jeho proces pro zajištění transparentnosti. Pokud skriptu nedůvěřujete, můžete soubory modů ručně extrahovat do příslušných složek.

---

#### Funkce

##### Informace o modech:
- **Totem Mod**:
  - Přidává podporu pro hostování lobby s více než 8 hráči.
  - Obsahuje aktualizaci uživatelského rozhraní pro 11 hráčů.
  - Extrahuje se do:
    ```
    C:\Program Files (x86)\Steam\steamapps\common\Dread Hunger\DreadHunger\Content\Paks
    ```
  
- **Old Expanse**:
  - Samostatný mapový mod, který **není kompatibilní s Totem Modem**.
  - Instalátor zajišťuje odinstalování Totem Modu před instalací tohoto modu a naopak.

---

#### Možnosti instalace
Po spuštění skriptu budete vyzváni k výběru z následujících možností:
1. **Instalovat Totem Mod**:
   - Pokud je detekován Old Expanse, bude automaticky odinstalován před instalací Totem Modu.
2. **Odinstalovat Totem Mod**:
   - Odstraní Totem Mod z adresáře hry.
3. **Instalovat Old Expanse**:
   - Pokud je detekován Totem Mod, bude automaticky odinstalován před instalací Old Expanse.
4. **Odinstalovat Old Expanse**:
   - Odstraní Old Expanse z adresáře hry.
5. **Zrušit**:
   - Ukončí instalátor.

---

#### Jak používat
1. **Spusťte instalátor**:
   - Poklepejte na `.bat` soubor, abyste zahájili proces.
2. **Zadejte adresář hry**:
   - Zadejte cestu k instalaci Dread Hunger (výchozí hodnota je přednastavena).
3. **Vyberte možnost**:
   - Postupujte podle pokynů na obrazovce pro instalaci, odinstalaci nebo správu modů.

---

#### Ruční instalace
Pokud nechcete používat instalátor, můžete soubory modů ručně extrahovat:
1. **Totem Mod**:
   - Obsah `totemmod_client.zip` extrahujte do:
     ```
     C:\Program Files (x86)\Steam\steamapps\common\Dread Hunger\DreadHunger\Content\Paks
     ```
2. **Old Expanse**:
   - Obsah `oldexpanse.zip` extrahujte do stejného adresáře jako výše.

Ujistěte se, že máte vždy nainstalovaný **pouze jeden mod**, aby nedocházelo ke konfliktům.

---

#### Důležité poznámky
- **Nekompatibilita**:
  - Totem Mod a Old Expanse nemohou být instalovány současně. Instalátor automaticky provede odinstalování, pokud přepínáte mezi mody.
- **Transparentnost**:
  - Instalátor je napsán ve formátu `.bat`, takže si můžete prohlédnout jeho kroky. Pokud chcete, můžete jeho kroky replikovat ručně.
