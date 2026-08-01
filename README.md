# Xanthorox Theme for Bruce Firmware

**Dark cyberpunk-horror neon theme** for LilyGO T-Embed CC1101 running [Bruce Firmware](https://bruce.computer).

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

### Installation (Easiest)
1. Flash latest **Bruce** (select **T-Embed CC1101**) → https://bruce.computer/flasher
2. Download the complete package from the Grok conversation Artifacts:  
   **`Xanthorox_Bruce_Theme_FINAL.zip`**
3. Unzip it → you will get a folder named `Xanthorox`
4. Copy the entire `Xanthorox` folder to the root of a FAT32 microSD card
5. Insert SD into T-Embed → **Config → UI Theme → SD Card** → open `Xanthorox` → select `theme.json`
6. Reboot. The full 10s boot plays automatically.

### Files in the package
- `theme.json`
- `boot.gif` (10s animated)
- `boot.png` (static)
- 15 icons: wifi, ble, rf, rfid, ir, fm, files, gps, nrf, interpreter, clock, lora, others, connect, config

### Colors (RGB565)
- Primary: `07ff` (Cyan neon)
- Secondary: `f81f` (Magenta)
- Background: `0000` (Black)
- LED: `#c000c0` Magenta breathe

### Note
Binary assets (boot.gif + icons) cannot currently be uploaded through the GitHub connector. Download the FINAL zip from the conversation artifacts and either use it directly or drag the files into this repo via the GitHub website.

Stay ethereal. 🦈

**Repo**: https://github.com/m4gs6mzgy4-cell/Xanthorox-Bruce-Theme
