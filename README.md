# Trident R2 Odinite ⚙️

Trident LDO 300 cube mod build.

---

## What This Is

* **The Origin**: Years ago I bought an LDO Voron Trident 300 cube kit from Fabreeko.
* **The Delay**: Life happened and it sat in storage for a bit (3 and a half years is a bit, right?).
* **The Goal**: Figured it was time to build it, and mod it before I build—"do it nice, not twice." I want a stable printer for ABS, ASA, and multi-material printing.
* **The Solution**: Decided to go all-in on a Bondtech INDX system.
* **This Repo**: Born as a place for me to virtually build it before I really build it, and to serve as a permanent record of the build process.

---

## Submodules

* **[Official Voron Trident R2](https://github.com/VoronDesign/Voron-Trident)** (from 2026-06-26)  
  Commit: `f04f747d4dea06315806f352abf57f767cedf2b4`
* **[Clicky Clack Door](https://github.com/tanaes/whopping_Voron_mods.git)** (from 2024-08-26)  
  Commit: `62268ed817878e54d6a1186882060aa8368d4f0f`  
  *Hardware Kit:* [West3D Clicky Clack Fridge Door Kit](https://west3d.com/products/clicky-clack-fridge-door-kit-for-voron-trident-by-ldo-motors)

---

## Other Folders

**ldo_kit_info**: original build information regarding my base kit
**stealthpress_1s**: I'm going to do a lot of brass inserts... so I'm investing in this 

---

## Planned Mods & Hardware Changes

These changes were driven by what I had available and what I was able to source to support my stable ABS/ASA design goals:

| Category | Component / Mod Details |
| :--- | :--- |
| **Motion & Motors** | Change AB motors to longer shafts (`OMC 17HS19-2504S-H-V6`) |
| **Toolhead** | Bondtech INDX with 7 tools |
| **Enclosure & Frame** | ACM panels, titanium rail backers, and PEEK Z-axis lead screw nuts |
| **Cooling & Filtration** | Stealthmax V2 (top intake, bottom recirculation), dual 120mm underbed chamber circulators, and active AB stepper coolers |
| **Electronics & Power** | BTT Manta M8P V2 MCU, Raspberry Pi CM5 (with copper heatspreader, a 4011 heatsink, and custom fan cooling), Mean Well RSP-320-24 PSU, and BTT TMC5160 Pro stepper drivers (cooled with 5015 Delta fans) |
| **User Interface & Misc** | BTT HDMI5 touchscreen, chamber LEDs, and "Rock and Roller" mod for easy bottom access |

---

## Mods Considered (and Passed On)

* **Inverted Electronics Bay**: Passed on this because I didn't want loose parts or debris falling down directly into the electronics bay during maintenance.

---

## TODO

- [ ] Double-check endstops (prefer mechanical, normally closed `NC` fail-safe wiring, Omron, no lever)
- [ ] Install Chamber LEDs and status light bar
- [ ] Design/print a custom Tophat to clear the PTFE tubes
- [ ] Design/mount a camera mount
- [ ] Configure ethernet over Wi-Fi
