# CMOS Inverter - DC Characteristics

**Cadence Virtuoso lab**: DC Transfer Curve (Vout vs Vin)

## What I did:

    PMOS + NMOS schematic (Vdd=1.8V)

    Symbol creation

    Testbench: Vin sweep 0→1.8V (0.001V steps)

    ADE L → DC analysis (linear sweep)

text

## Results:

    Vin=0V → Vout=1.8V (PMOS ON)

    Vin=0.9V → Vout=0.9V (switching point)

    Vin=1.8V → Vout=0V (NMOS ON)

    Perfect inverter transfer curve!

text

## Screenshots needed:

inverter_schematic.png (Fig 1.2)
symbol.png (Fig 1.3)
testbench.png (Fig 1.4)
dc_transfer_curve.png (Fig 1.6) ← KEY RESULT

text

**Status**: Simulation complete ✅

---
**Goa College of Engineering VLSI Lab**
