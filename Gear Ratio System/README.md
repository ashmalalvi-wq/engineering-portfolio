# Gear Ratio System

An educational, 3D-printed gear system built in **Fusion 360** to explore fundamental mechanical design questions rather than serve a single fixed application.

## Purpose
Designed and printed primarily as a hands-on test platform to investigate:
- **Durability of 3D-printed (PLA) gears** under repeated use and torque
- **How to achieve a high gear ratio** within a compact mechanical footprint
- **The effect on input torque** at the initial driving gear as ratio increases

## Result
Achieved a **512:1 gear ratio** — one full rotation of the initial input gear produced 512 rotations at the final output gear.

## Key Finding
The printed **PLA gears did not hold up well over extended use** — increased torque at the high-ratio stages caused visible wear and degradation of the printed teeth over time, highlighting a real limitation of PLA as a gear material at higher mechanical loads.

## Skills Demonstrated
- Parametric CAD modeling and gear train design in Fusion 360
- Compound gear ratio calculation and mechanical power transmission analysis
- Design-for-3D-printing considerations (tolerance, tooth geometry, material limits)
- Empirical testing and failure analysis of printed components

## Challenges & Solutions
- **Challenge:** Achieving a very high (512:1) ratio within a compact footprint required staging multiple gear reductions rather than a single gear pair.
- **Challenge:** PLA's mechanical limits under sustained torque caused premature tooth wear at high-ratio stages.
- **Takeaway:** Identified material choice (PLA) as the primary bottleneck for durability — a stronger filament (e.g., PETG or nylon) or metal gears would be the logical next iteration for any load-bearing use.

## Future Improvements
- Reprint high-load stages in a more durable material (PETG/nylon) or replace with metal gears
- Add torque/RPM measurement at input and output stages to quantify efficiency losses
- Complete the originally-planned integration with the Magnetic Induction Wheel Generator drivetrain

## Notes
Originally intended to eventually be adapted into the drivetrain for the [Magnetic Induction Wheel Generator](../Magnetic%20Induction%20Generator), but this integration was never fully optimized or completed — the two remain separate, standalone projects.

## Status
Functional test rig / proof of concept, not integrated into a larger system.

## Tools
Fusion 360

## Files
No CAD or mesh file is included yet — this folder currently holds only this README. An exported mesh (OBJ/STL) may be added later.
