# GODDESS OF VICTORY: NIKKE (PC Client)

**Status:** 🟡 Playable, but updates sometimes break the setup, forcing a reinstall.

### 📋 Overview
* **Developer/Publisher:** SHIFT UP / Level Infinite  
* **Store Link:** https://nikke-en.com/  
* **Anti-Cheat:** Anti-Cheat Expert (ACE)

---

### 🛠️ Installation Steps
This guide covers installation using **Faugus Launcher + DW-Proton**

1. **Install Faugus Launcher:**  
   * Install via Flatpak or your package manager (`pacman`, `dnf`, etc.)

2. **Install DW-Proton:**  
   * Install ProtonPlus → https://protonplus.vysp3r.com/#download  
   * Open ProtonPlus and install **DW-Proton Latest**  
   * Close ProtonPlus  
   * *Faugus will automatically detect the runner*

3. **Create Prefix:**  
   * Open Faugus → click `+`  
   * Type: **Windows Game** (default)  
   * Name: `Goddess of Victory NIKKE`  
   * Prefix:  
     * Click 🔍 and choose location (recommended: game drive)  
     * *Auto-filled after naming, leave PATH blank for now*  
   * Proton: **DW-Proton Latest**

4. **Install Dependencies (Winetricks):**  
   * Go to **Tools → Winetricks**  
   * Select: *default wineprefix*  

   **Fonts (Required):**  
   * `arial` or `allfonts`  

   **DLLs (Optional but recommended):**  
   * `mfc42`  
   * `vcredist2012` or `vcrun2012`  
   * `vcredist2022` or `vcrun2022`  

5. **Install the Game:**  
   * Tools tab → **RUN**  
   * Select the NIKKE installer `.exe`  
   * Wait for full download/install  

6. **Configure Launcher Path:**  
   * Go back to Game/App tab  
   * PATH → 🔍 → set to:  

```
<prefix-path>/drive_c/NIKKE/Launcher/nikke_launcher.exe
```


   * Enable shortcuts if needed → OK  

7. **Run:**  
   * Launch via Faugus  
   * Use the launcher to start/update the game  

---

### ⚙️ Required Tweaks / Launch Options
* **Proton Version:** DW-Proton Latest  
* **Recommended Setup:**  
  * Works on most modern distros (Arch-based, Fedora-based, etc.)  
* **Storage Tip:**  
  * Place prefix on a secondary/game drive to save space  

---

### ⚠️ Known Issues & Fixes
* **Launcher Required:** Game must be launched via the official launcher (no direct `.exe` first-run)  
* **Paths:** If using custom prefix location, ensure PATH matches your setup  
* **Winetricks:** Missing fonts may cause UI issues  

---

### 📸 Proof of Gameplay

<img width="1492" height="819" alt="Screenshot_20260502_024705" src="https://github.com/user-attachments/assets/f557ef31-6938-40ef-89cc-cdd2890f11d4" />

<img width="1915" height="1077" alt="Screenshot_20260502_025006" src="https://github.com/user-attachments/assets/67f7d3f7-3e1e-4023-92cb-773e975b1804" />

---

*Guide contributed by: @Brian2po*
