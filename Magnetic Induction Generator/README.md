# Magnetic Induction Wheel Generator

**Collaborative project** — co-designed and built with a project partner.

## Overview
A small-scale rotational generator that converts mechanical rotation into usable electrical energy. A magnet wheel spins past stationary copper wire spools, inducing a magnetic field and generating an AC voltage, which is then rectified to DC to power a low-voltage LED.

## How It Works
- A rotating wheel embedded with magnets passes by fixed copper wire coils, inducing a changing magnetic field across them (electromagnetic induction).
- The resulting AC output is passed through a **2-diode rectifier circuit**, converting it to DC.
- The DC output is used to power a low-voltage LED, demonstrating a complete mechanical-to-electrical energy conversion loop.

## Design Constraints
- The entire assembly was constrained to fit within a **6-inch 3D printer bed**, limiting the wheel diameter, magnet size, and achievable field strength.
- Due to the small magnet size, output voltage/current is modest — sufficient only for a low-power LED, not larger loads.

## Skills Demonstrated
- Applied electromagnetic induction principles to a physical mechanical design
- Basic power electronics (AC-to-DC rectification circuit design)
- Design-for-constraint: engineering a full working system within a fixed print-volume limit
- Cross-disciplinary collaboration between mechanical and electrical design tasks

## Challenges & Solutions
- **Challenge:** The 6-inch print bed limit capped magnet size and wheel diameter, directly limiting achievable field strength and output power.
- **Challenge:** Standard (non-magnet-specific) wire gauge and insulation reduced achievable coil turns compared to purpose-built magnet wire.
- **Takeaway:** Output was intentionally modest by design — the project prioritized demonstrating the working principle over maximizing power output.

## Future Improvements
- Use thinner, enameled magnet wire to fit significantly more coil turns in the same footprint
- Scale up magnet size and wheel diameter beyond the original print-bed constraint
- Add a voltage/current measurement setup to quantify real output under load

## Notes
This was an early exploratory build focused on demonstrating the working principle of magnetic induction on a small scale, rather than optimizing for power output.

## Tools
CAD tool used for the mechanical design not yet documented here — this folder currently holds a design image only, no CAD source file.

## Files
- `Magnetic Induction Wheel Design.png` — design image. No CAD file or STL is included yet, so there's nothing here for GitHub's 3D viewer to render.
