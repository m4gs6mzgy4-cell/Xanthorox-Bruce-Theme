# Xanthorox Theme for Bruce Firmware

**Dark cyberpunk-horror neon theme** for LilyGO T-Embed CC1101 (and standard T-Embed) running [Bruce Firmware](https://bruce.computer).

### Features
- **10-second cinematic boot animation**:
  1. Cracked-glowing woman walks down a rainy industrial hallway
  2. Stops and turns to the camera
  3. Smiles provocatively
  4. Jagged gothic neon **XANTHOROX** logo appears with lightning & energy
- Cyan (`0x07FF`) + Magenta (`0xF81F`) cracked porcelain aesthetic
- 15 matching neon icons
- Magenta LED breathe effect
- Optimized for 320×170 T-Embed display

### Installation
1. Flash latest **Bruce** (select T-Embed CC1101) via the [official flasher](https://bruce.computer/flasher)
2. Download this repository (Code → Download ZIP) or clone it
3. Copy all the theme files (theme.json + icons + boot.gif / boot.png) to the root of a FAT32 SD card (or put them in a folder)
4. On the device: **Config → UI Theme → SD Card → select `theme.json`**
5. Reboot to enjoy the full animated boot

### Files
| File | Description |
|------|-------------|
| `theme.json` | Theme configuration |
| `boot.gif` | 10s animated boot sequence (~1.2 MB) |
| `boot.png` | Static boot fallback |
| `*.png` | Menu icons (wifi, ble, rf, rfid, etc.) |

### Colors (RGB565)
- Primary: `07ff` (Cyan)
- Secondary: `f81f` (Magenta)
- Background: `0000` (Black)
- LED: `#c000c0` (Magenta breathe)

### Credits
Created with Grok Imagine for the Bruce community.  
Stay ethereal. 🦈

---
**Repo**: https://github.com/m4gs6mzgy4-cell/Xanthorox-Bruce-Theme
