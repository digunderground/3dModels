# Panavise Gridfinity Base 4×4×2

A [Gridfinity](https://www.printables.com/model/274917-gridfinity-specification)-compatible base designed to hold a **Panavise** bench vise on a standard Gridfinity grid. The base occupies a 4×4 unit footprint and stands 2 stacking units tall, providing a stable, low-profile platform that integrates with any Gridfinity storage setup.

## Files

| File | Description |
|------|-------------|
| `Panavise Gridfinity base 4x4x2.stl` | Main base body — 4×4 grid footprint, 2 units tall, with Panavise mounting geometry on top |

> Source files: `gridfinity panavise base.f3d` (Fusion 360), `Panavise_Gridfinity_base_4x4x2.step`

## Usage

Mount this base onto any Gridfinity-compatible baseplate. The base accepts the Panavise vise post and locks it in place so the vise can be quickly swapped in and out of your workbench or storage grid. Ideal for electronics workbenches, hobbyist desks, and maker spaces where bench space is managed with Gridfinity.

## Compatibility

- **Gridfinity spec:** Standard 42 mm grid pitch, magnetic pockets in base (if your baseplate supports magnets)
- **Panavise model:** Designed for standard Panavise Junior / Model 201 series (verify the post diameter against your specific vise before printing)

## Print Settings

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG or ASA | Needs rigidity and moderate heat resistance near workbench tools |
| **Layer height** | 0.2 mm | Good balance of strength and surface quality |
| **Infill** | 40–50% | Higher infill improves rigidity under vise clamping forces |
| **Infill pattern** | Gyroid or cubic | Better isotopic strength for functional parts |
| **Perimeters / walls** | 4 | Critical for Gridfinity snap-fit walls and vise socket |
| **Top/bottom layers** | 5 | Ensures solid top surface for vise contact |
| **Print orientation** | Flat (bottom face down) | Gridfinity base pockets face down, no supports needed |
| **Supports** | None required | Design is self-supporting |
| **Bed adhesion** | Brim (3–5 mm) | Recommended for large flat footprint on smooth PEI |
| **Nozzle** | 0.4 mm | Standard; 0.6 mm acceptable for faster print |
| **Print speed** | 40–60 mm/s | Reduce to 30 mm/s for perimeters to improve dimensional accuracy |

## Tips

- Print with at least 4 walls to ensure the Gridfinity retention geometry is strong enough.
- If you plan to use magnets, press-fit 6×2 mm neodymium magnets into the base pockets while the print is still warm.
- PETG is preferred over PLA for workbench use — vise clamping generates vibration and minor heat that can fatigue PLA over time.
