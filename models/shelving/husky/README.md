# Husky Shelving Magnetic Brackets

Magnetic mounting brackets designed for **Husky** garage shelving systems. These brackets use embedded neodymium magnets to attach accessories, DIN rails, and organizers to Husky steel shelving uprights and surfaces without drilling or permanent hardware.

## Files

| File | Description |
|------|-------------|
| `husky 4020 mag bracket.stl` | Magnetic bracket sized for Husky 40×20 mm slot/upright profile — mounts accessories to the vertical frame of Husky shelving |
| `husky DIN mag bracket.stl` | Magnetic bracket that holds a 35 mm DIN rail section against Husky shelving steel, enabling DIN-based tool and accessory mounting on the shelving unit |

## Usage

### husky 4020 mag bracket

This bracket grips the 40×20 mm rectangular tube uprights found on Husky heavy-duty garage shelving. Magnets embedded in the back face hold the bracket firmly to the steel upright. Use it to:

- Mount small organizer bins or cups to shelf uprights
- Attach hooks, clamps, or holders to vertical steel members
- Create quick-release accessory points anywhere along the upright

### husky DIN mag bracket

Combines a magnetic mounting face with a 35 mm DIN rail cradle. The magnet holds the entire assembly to any flat steel surface on Husky shelving (the shelf deck, upright faces, or cross-members). Once attached, standard DIN rail accessories (terminal blocks, cable clips, small enclosures, tool holders) snap onto the rail. Use it to:

- Add DIN-mounted cable management to the underside of a shelf
- Mount a row of labeled terminal blocks as cable organizers
- Attach DIN-compatible tool holders or small accessory racks to shelving
- Quickly relocate the entire DIN strip by simply lifting and repositioning

## Hardware Required

- **Neodymium magnets** — 10×3 mm or 8×3 mm round disc magnets (quantity depends on pocket count in each bracket; typically 2–4 per bracket)
- Optional: cyanoacrylate glue to secure magnets in pockets after press-fitting

## Print Settings

### husky 4020 mag bracket.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG | Garage environments have temperature swings; PETG handles them better than PLA |
| **Layer height** | 0.2 mm | |
| **Infill** | 40% | Bracket needs to resist peel-off forces from the shelf upright |
| **Infill pattern** | Gyroid | |
| **Walls** | 4 | Important for the profile-gripping channel geometry |
| **Top/bottom layers** | 4 | |
| **Print orientation** | Gripping channel facing up | Avoids supports inside the channel |
| **Supports** | Minimal | Only if channel overhangs exceed 45° |
| **Print speed** | 40–50 mm/s | |

### husky DIN mag bracket.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG or ASA | ASA preferred for unheated garages in cold climates |
| **Layer height** | 0.2 mm | 0.15 mm if DIN rail snap-fit feels loose |
| **Infill** | 40–50% | DIN rail retention clips require strength |
| **Infill pattern** | Gyroid | |
| **Walls** | 4 | |
| **Top/bottom layers** | 5 | |
| **Print orientation** | Magnetic face down (flat on bed) | Best layer orientation for peel resistance |
| **Supports** | As needed for DIN channel | |
| **Print speed** | 40 mm/s | Slow to 20 mm/s for DIN clip features |

## Magnet Installation

1. Press-fit magnets into the pockets while the print is still slightly warm from the bed — this eases insertion.
2. Verify polarity before gluing; all magnets on a bracket should attract the shelf steel (not repel).
3. Apply a small drop of cyanoacrylate glue and let cure fully before use.
4. Stack magnets if pockets are deeper than one magnet to increase holding force.

## Tips

- **Test holding force** with a loaded bracket before mounting anything critical. Add more magnet pockets or use larger magnets if the bracket slides under load.
- PETG has slightly lower rigidity than PLA but much better impact resistance — important in a garage where brackets may be knocked.
- For the DIN bracket: print the DIN_TESTER piece from the pedalboard project (if available) to calibrate your DIN rail fit before printing the full bracket.
- Label each bracket position with a paint marker or printed label insert to quickly identify reorganized shelving sections.
