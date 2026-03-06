# SPD Slide Mount System

A two-part **slide-and-lock mounting system** inspired by Shimano SPD cleat mechanics. The design uses a tapered dovetail-style slide that enforces a single insertion direction, solving common 3D-printed press-fit tolerance problems. The taper works both top-to-bottom and along the key engagement axis, creating a positive mechanical lock while allowing ±0.2 mm printer variance without affecting function or security.

## Files

| File | Description |
|------|-------------|
| `SPD-shoeMount-male.stl` | Male half of the slide mount — the moving/receiver piece that attaches to the item being mounted (e.g., a cup holder, accessory tray, bike-side bracket) |
| `SPD-cupHolderMulti.stl` | Cup holder with integrated female SPD-style mount socket — demonstrates the system with a multi-size cup/bottle holder that snaps onto any compatible male mount point |

## Design Intent

Standard press-fit and snap-fit connections in 3D prints suffer from tolerance stack-up: too tight and parts won't seat, too loose and they rattle or fall off. This system addresses that by:

- **Single-direction insertion** — the taper only allows the mount to slide in from one end, so the fit tightens as it seats rather than requiring precise force from any angle
- **Dual-axis taper** — the dovetail narrows both vertically and along the slide key, creating a wedge effect that pulls the joint tight at full engagement
- **Tolerance-tolerant geometry** — ±0.2 mm variance across prints still results in a secure, rattle-free mount because the taper compensates for dimensional differences

## Usage

### Mounting a Cup Holder (`SPD-cupHolderMulti.stl`)
1. Install `SPD-shoeMount-male.stl` onto your target surface (bike frame, handlebar bag, desk rail, etc.) using screws, glue, or the attachment method appropriate for your surface.
2. Align `SPD-cupHolderMulti.stl` with the male mount from the open end of the slide channel.
3. Slide the cup holder onto the mount in one direction — the taper guides it to a locked position.
4. To remove, slide back out in the reverse direction.

### Extending the System
The male mount piece (`SPD-shoeMount-male.stl`) can be attached to any flat or curved surface. Print multiple male mounts and install them in different locations to allow the same cup holder (or other accessories using the same female socket) to hot-swap between positions.

## Print Settings

### SPD-shoeMount-male.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG | Good balance of flexibility (for slide engagement) and strength |
| **Alternative** | Nylon (PA12) | Superior wear resistance for frequently cycled mounts |
| **Layer height** | 0.15 mm | Finer layers improve dovetail surface finish and fit accuracy |
| **Infill** | 50–60% | Slide geometry experiences shear forces; use high infill |
| **Infill pattern** | Gyroid or honeycomb | |
| **Walls** | 4–5 | Critical — walls form the load-bearing dovetail faces |
| **Top/bottom layers** | 5 | |
| **Print orientation** | Slide axis parallel to bed (flat) | Best layer adhesion along the direction of insertion force |
| **Supports** | Minimal | Taper design minimizes overhangs |
| **Print speed** | 30–40 mm/s | Slow down for accurate dovetail geometry |
| **Cooling** | Max fan | Reduces dimensional creep on fine features |

### SPD-cupHolderMulti.stl

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG | Food/drink safe-adjacent material; easy to clean |
| **Alternative** | ASA | For outdoor/bike use with UV exposure |
| **Layer height** | 0.2 mm | |
| **Infill** | 30–40% | Cup holder body doesn't need extreme infill |
| **Infill pattern** | Gyroid | |
| **Walls** | 4 | Especially at the female mount socket and cup rim |
| **Top/bottom layers** | 4 | |
| **Print orientation** | Bottom face down | Socket geometry faces up — minimal supports needed |
| **Supports** | Light supports for socket overhang | Use support blockers to keep cup interior support-free |
| **Print speed** | 40–50 mm/s | |
| **Bed adhesion** | Brim (5 mm) | Large flat footprint benefits from brim |

## Tips

- **Print the male mount first and test the slide fit** before printing many cup holders or other accessories. Once the male geometry is dialed in for your printer, all future female receivers will fit consistently.
- If the slide is too tight: try printing the male mount at 99% scale or increase the female socket clearance in the source file.
- If the slide is too loose: try printing the male mount at 101% scale, or add a thin strip of PTFE tape to the dovetail faces as a shim.
- For bike mounting, use **stainless M4 screws** to attach the male mount to avoid corrosion.
- The "Multi" in `SPD-cupHolderMulti.stl` indicates the cup holder accommodates multiple bottle/cup diameters — verify the size range fits your bottles before printing.
