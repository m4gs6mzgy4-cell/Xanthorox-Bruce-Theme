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

### Installation
1. Flash latest **Bruce** (select **T-Embed CC1101**) → https://bruce.computer/flasher
2. **Download the full theme package** (contains boot.gif + all icons):
   - From the Grok conversation **Artifacts** panel:  
     `Xanthorox_Bruce_Theme_T-Embed_CC1101_v1.2.zip` (1.9 MB)
3. Unzip it
4. Copy **all files** inside `Xanthorox_T-Embed/` (theme.json + boot.gif + boot.png + all icons) to the root of a FAT32 SD card
5. On the device: **Config → UI Theme → SD Card → select `theme.json`**
6. Reboot and enjoy the full animation

### Current files in this repo
- `README.md`
- `theme.json` (ready to use)

**Note about binaries**: The large files (`boot.gif` ~1.2 MB and the 15 PNG icons) are provided in the conversation artifacts zip because of current upload limits on binary content through the GitHub connector.  
After downloading the zip, just drag-and-drop the missing files into this repository on GitHub.com to complete it.

### theme.json
```json
{
  "wifi": "wifi.png",
  "ble": "ble.png",
  "rf": "rf.png",
  "rfid": "rfid.png",
  "fm": "fm.png",
  "ir": "ir.png",
  "files": "files.png",
  "gps": "gps.png",
  "nrf": "nrf.png",
  "interpreter": "interpreter.png",
  "clock": "clock.png",
  "lora": "lora.png",
  "others": "others.png",
  "connect": "connect.png",
  "config": "config.png",
  "priColor": "07ff",
  "secColor": "f81f",
  "bgColor": "0000",
  "border": 1,
  "label": 0,
  "boot_img": "boot.gif",
  "ledBright": 80,
  "ledColor": "c000c0",
  "ledEffect": 1,
  "ledEffectSpeed": 4,
  "ledEffectDirection": 1
}
```

Stay ethereal. 🦈

**Live repo**: https://github.com/m4gs6mzgy4-cell/Xanthorox-Bruce-Theme
