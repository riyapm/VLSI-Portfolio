# CMOS Inverter - Wn/Wp Ratio Effect

**Cadence Virtuoso lab**: How transistor size changes VTC curve

## Theory:

Wn/Wp > 1 → NMOS stronger → Curve shifts LEFT
Wn/Wp < 1 → PMOS stronger → Curve shifts RIGHT

text

## What I did:

    NMOS: Wn=120n (fixed)

    PMOS: Wp=120n→360n (parametric sweep)

    DC analysis: Vin 0→1.8V

    3 curves plotted (Wp variation)

text

## Results:

Wp=120n (Wn/Wp=1) → Symmetric switching
Wp=240n (Wn/Wp=0.5) → Curve RIGHT (PMOS strong)
Wp=360n (Wn/Wp=0.33)→ Even more RIGHT

text

## Screenshots:

schematic.png (Fig 2.1)
testbench.png (Fig 2.2)
parametric_setup.png (Fig 2.3)
vtc_curves.png (Fig 2.4) ← MAIN RESULT

text

**Status**: Parametric analysis complete ✅

---
**Goa College of Engineering VLSI Lab**

