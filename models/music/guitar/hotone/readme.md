# Hotone Pulze Mini — Strap Bracket

A mounting bracket designed for the **Hotone Pulze Mini** portable guitar amplifier. The bracket attaches to a guitar strap or bag strap, allowing the Pulze Mini to be carried hands-free or secured to a strap for easy access during practice and performance.

## Files

| File | Description |
|------|-------------|
| `Pulze-Mini-StrapBracket.stl` | Strap-mount bracket that clips onto a standard guitar or equipment strap and cradles the Hotone Pulze Mini amp body |

> Source file: `Pulze Mini Mount.f3d` (Fusion 360)

## Usage

The bracket is designed to clip or slide onto a guitar strap (typically 50–60 mm wide) and cradle the Hotone Pulze Mini securely. This lets players:

- Clip the Pulze Mini to their guitar strap for truly wire-free, amp-at-hip practice
- Attach the amp to a gig bag shoulder strap for transport without a separate bag
- Keep the amp accessible on a practice stand strap or music stand

### Installation
1. Thread the bracket onto your strap before attaching the strap to your guitar, or slide it on from the end of the strap.
2. Position the bracket at a comfortable height — typically mid-torso on the guitar strap.
3. Seat the Pulze Mini into the bracket cradle. The bracket should grip the amp body snugly; if loose, add a thin strip of foam tape to the inside contact surfaces.

## Hardware Required

- None required for basic use
- Optional: small strip of adhesive foam (1–2 mm) inside the cradle to prevent the amp from rattling

## Print Settings

| Setting | Recommended Value | Notes |
|---------|-------------------|-------|
| **Material** | PETG | Preferred — more flexible than PLA so the clip won't snap under strap tension; also better UV/sweat resistance |
| **Alternative material** | TPU (95A) | If you want a soft-grip clip that won't scratch the amp body |
| **Layer height** | 0.2 mm | |
| **Infill** | 40–50% | Clip areas need strength; don't go below 35% |
| **Infill pattern** | Gyroid | Best isotopic strength for clips under bending load |
| **Walls** | 4 | Especially important for clip and retention geometry |
| **Top/bottom layers** | 4 | |
| **Print orientation** | Flat (largest face down) | Maximizes layer adhesion in the direction of clip opening force |
| **Supports** | As needed | Clip overhang may require support depending on design angle |
| **Bed adhesion** | Brim (3 mm) | Helps with PETG bed adhesion |
| **Print speed** | 40 mm/s | Reduce to 20 mm/s for perimeters and small features |
| **Nozzle temp (PETG)** | 230–240 °C | |
| **Bed temp (PETG)** | 70–85 °C | |

## Tips

- **Test the strap fit before printing the full part.** Strap widths vary; measure your strap and compare to the model slot dimensions. If your strap is wider than the slot, scale the slot slightly or reopen the source `.f3d` file to adjust.
- Print in **black PETG** for a professional, stage-ready look that blends with most black guitar straps.
- If the amp feels like it could pop out during energetic playing, add a small hook-and-loop (Velcro) dot to the inside of the cradle and the side of the amp body.
