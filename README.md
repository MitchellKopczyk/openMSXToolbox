# openMSX Toolbox

> Easy installer and launcher for openMSX — built for noobs!

Getting openMSX up and running with the right machine config, ROMs, and DOS image is surprisingly odd to setup. openMSX Toolbox takes care of all of it in a few clicks.

---
## Screenshot

![openMSX Toolbox UI](screenshot.png)

---

## What it does

- Downloads and installs the latest openMSX release for Windows (x64)
- Grabs the Panasonic FS-A1GT ROMs automatically Check Legality!!! Not liable for you mistakes ¯\_(ツ)_/¯
- Sets up the SunriseIDE extension with a Nextor ROM
- Downloads an MSX-DOS 2.3 boot disk and wires everything up
- Launches openMSX fully configured — just press Run
- Use the GUI to mount ROMS, Disks, or whatever you want

---

## Requirements

- Windows 10 or 11 (x64)
- Python 3.8+
- `requests` library (`pip install requests`)

---

## Getting started

1. Download the openMSXToolbox.exe
2. Drop the `floppy.dsk` next to the launcher. I pefer the Documents folder because openMSX dumps other files in there this way it's all in one place 
3. Run the launcher:

```bash
python openMSX_Toolbox.py
```

4. Hit **INSTALL** and wait for everything to download and set up
5. Once complete, hit **RUN** — that's it!

---

## FAQ

**Where does everything get installed?**
openMSX is installed into an `openMSX/` folder next to the launcher. The boot disk lands in your `Documents/openMSX/` folder as openMSX expects.

---

## License

MIT — do whatever you want with it.

---
