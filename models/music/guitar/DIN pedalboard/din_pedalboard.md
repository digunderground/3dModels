# DIN Rail Guitar Pedalboard

A modular guitar pedalboard system built around **DIN rail** (35 mm top-hat rail). Standard DIN rail acts as the spine, allowing guitar pedals to be mounted with off-the-shelf DIN rail clips or custom 3D-printed adapters. This system provides a low-profile, strong, and reconfigurable pedalboard that is easy to assemble with common hardware-store components.

## Files

| File | Description |
|------|-------------|
| `DIN_pedalboard_Support.stl` | Main lateral support / leg that holds the DIN rails at the correct angle and height |
| `DIN_pedalboard_Endcap-L.stl` | Left endcap — caps the end of the pedalboard frame and ties supports together |
| `DIN_pedalboard_Endcap-R.stl` | Right endcap — mirror of left endcap |
| `DIN_TESTER.stl` | Small test piece to verify DIN rail fit and printer calibration before committing to a full print |

> Source files: `Guitar Pedal DIN.f3d` (Fusion 360), `Guitar_Pedal_DIN__R2_R2.step`

## Usage

### Assembly Overview
1. **Print the tester first** — print `DIN_TESTER.stl` and verify that standard 35 mm DIN rail slides in with a snug but not binding fit. Adjust scaling ±0.5% if needed.
2. **Print supports** — print as many `DIN_pedalboard_Support.stl` pieces as needed for the length of your pedalboard (typically one every 200–250 mm along the rail).
3. **Print endcaps** — one left (`Endcap-L`) and one right (`Endcap-R`) per pedalboard.
4. **Cut DIN rail** to desired length with a hacksaw or angle grinder. Standard DIN rail is available at electrical suppliers and online.
5. **Assemble** — snap DIN rail into supports, cap the ends, and mount pedals using standard DIN rail clips or velcro over the rail.

### Mounting Pedals
Pedals can be attached to the DIN rail using:
- Standard 35 mm DIN rail mounting clips (available from electrical distributors)
- Velcro straps looped through DIN rail slots
- Custom 3D-printed pedal-specific DIN adapters

## Hardware Required

- 35 mm top-hat DIN rail (cut to length)
- M3 or M4 screws + heat-set inserts (if endcaps have mounting features)
- Optional: adhesive rubber feet for the underside of supports

## Print Settings

### DIN_TESTER.stl

| Setting | Recommended Value |
|---------|-------------------|
| **Material** | PLA or PETG |
| **Layer height** | 0.2 mm |
| **Infill** | 20% |
| **Walls** | 3 |
| **Purpose** | Fit check only — print fast, adjust scale if needed |

### DIN_pedalboard_Support.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG or ASA | Pedalboards can be exposed to temperature swings; PETG is safe, ASA for outdoor/touring use |
| **Layer height** | 0.2 mm | 0.15 mm for improved DIN rail fit accuracy |
| **Infill** | 40% | Supports pedals and stomping forces |
| **Infill pattern** | Gyroid or cubic | Isotropic strength in all directions |
| **Walls** | 4 | Thick walls for snap-fit DIN rail retention |
| **Top/bottom layers** | 5 | |
| **Print orientation** | Upright (as designed) | Maximize layer adhesion along stress axis |
| **Supports** | Minimal or none | Check orientation; DIN rail channel may need supports depending on slicer |
| **Print speed** | 40–50 mm/s | Slow perimeters to 25 mm/s for dimensional accuracy |

### DIN_pedalboard_Endcap-L.stl / Endcap-R.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG or ASA | Match material to supports |
| **Layer height** | 0.2 mm | |
| **Infill** | 30–40% | |
| **Walls** | 4 | |
| **Print orientation** | Flat face down | |
| **Supports** | As needed | May require supports for overhangs depending on geometry |

## Tips

- **Print the tester before anything else.** DIN rail tolerances vary by manufacturer; the tester saves wasting material on full parts.
- Use **PETG** rather than PLA for any pedalboard you plan to travel with — car trunks can exceed PLA's heat deflection temperature in summer.
- If endcaps feel loose after printing, a small drop of cyanoacrylate (super glue) on the joint with the support is sufficient to lock them in place without compromising disassembly.
- For a professional finish, sand the visible faces with 220-grit sandpaper and apply a matte spray paint to match commercial pedalboards.
