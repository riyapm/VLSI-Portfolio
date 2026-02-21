# CMOS Noise Margin Analysis

**Cadence Virtuoso lab**: Noise immunity (NMH, NML) calculation

## How noise margin works:

NMH = VOH - VIH (High noise tolerance)
NML = VIL - VOL (Low noise tolerance)
Find where derivative = -1 on VTC curve

text

## What I did:

    CMOS inverter: Standard PMOS/NMOS

    Pseudo NMOS: PMOS gate → GND (always ON)

    Calculator: deriv() function → Find slope=-1 points

    Markers → Extract VIL,VIH,VOL,VOH

text

## Key Results:

CMOS Inverter:

    NMH = ____ mV

    NML = ____ mV

Pseudo NMOS:

    VOL ≠ 0V (PMOS always ON)

    Lower noise margin than CMOS

text

## Screenshots:

cmos_schematic.png (Fig 3.1-3.2)
pseudo_nmos.png (Fig 3.3-3.5)
vtc_derivative.png (Fig 3.8-3.9) ← MAIN RESULT

text

**Status**: Noise margins calculated ✅

---
**Goa College of Engineering VLSI Lab**
