# GODDESS OF VICTORY: NIKKE (Linux Guide)

This guide covers how to run **GODDESS OF VICTORY: NIKKE** on Linux using Wine/Proton-based methods.

---

## Requirements

- A Linux distribution
- NIKKE Windows installer (official): https://nikke-en.com/

---

## Path: using Faugus Launcher + DW Proton

> Recommended method (simple + no Windows required)

---

### 1. Install Faugus Launcher

Install via:
- Flatpak  
- or your package manager (`pacman`, `dnf`, `yum`, etc.)

---

### 2. Install DW-Proton Runner

**Easiest method (recommended):**

1. Install ProtonPlus  
   https://protonplus.vysp3r.com/#download  
2. Open ProtonPlus  
3. Install **DW-Proton Latest**  
4. Close ProtonPlus  

> Faugus automatically detects installed runners

---

### 3. Create Prefix (Wineprefix)

1. Open **Faugus Launcher**
2. Click **"+" (Add)**

**Game/App Tab**
- Type: **Windows Game** (default)

**Title Tab**
- Name: `Goddess of Victory NIKKE`

**Prefix Tab**
- Click 🔍 and choose location (e.g., game drive)

> Auto-filled after setting name  
> Leave **PATH blank for now**

**Proton Tab**
- Select: **DW-Proton Latest**

**Shortcut Tab**
- Optional

---

### 4. Install Dependencies (Winetricks)

1. Go to **Tools → Winetricks**
2. Select: **default wineprefix**

#### Fonts (Required)
- `arial`  
- or `allfonts`

#### DLLs (Optional but Recommended)
- `mfc42`
- `vcredist2012` or `vcrun2012`
- `vcredist2022` or `vcrun2022`

Close Winetricks when done

---

### 5. Install the Game

1. Go to **Tools tab**
2. Click **RUN**
3. Select the NIKKE installer `.exe`
4. Wait for full download/install

---

### 6. Add Launcher

1. Return to **Game/App tab**
2. PATH → 🔍 → navigate to:


```
<prefix-path>/drive_c/NIKKE/Launcher/nikke_launcher.exe
```

3. Select executable  
4. Enable shortcuts if desired  
5. Click **OK**

---

## Done ✅

Launch the game through **Faugus + DW-Proton**

---

## Notes

- Updates are handled through the official launcher  
- No Windows installation required for this method  
- Works similarly to other Proton-based launchers (Lutris, Bottles, etc.) 

---

## Future Paths (Planned)

- Path 2: Miniloader  
- Path 3: Lutris  
- Path 4: DW Launcher  
- Path 5: Steam (DW-Proton)

---
