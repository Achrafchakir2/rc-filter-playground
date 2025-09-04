# RC Filter Playground (KiCad + SPICE + Audio Demo)

> A compact, two-channel **RC low-pass / high-pass** board with switchable cutoffs. Includes **KiCad** design, **ngspice** simulations, **Bode plots**, and a reproducible **build & test** workflow.

![Hero](media/hero.jpg)

## ✨ Features
- Two channels (A/B), each selectable as LPF or HPF via jumpers.
- Two cutoff presets per channel (audio + sensor).
- Complete KiCad project with Gerbers/BOM/PnP.
- Reproducible simulations (ngspice) + Python plots.
- Clear test checklist and measured CSVs.

## 🔧 Design Summary
Cutoff frequency: \\( f_c = \\frac{1}{2\\pi RC} \\)

**Presets**
- LPF ≈ **1 kHz**: R = **1.6 kΩ**, C = **100 nF**  
- HPF ≈ **100 Hz**: R = **16 kΩ**, C = **100 nF**  
(Additional presets documented on silkscreen and in `hardware/docs/assembly-notes.md`.)

Schematic PDF: [`hardware/docs/schematic.pdf`](hardware/docs/schematic.pdf)  
Board renders: `hardware/kicad-project/3d-renders/`

## 📁 Repo Layout
