# 2-Input NOR Gate - Cadence Virtuoso

**Cadence lab**: CMOS NOR + Layout + Pre/Post-layout simulation

## NOR Logic:

A=0,B=0 → OUT=1 (both PMOS ON)
A=1 OR B=1 → OUT=0 (parallel NMOS)

text

## Cadence Flow:

    Schematic: 2 PMOS parallel + 2 NMOS series

    Symbol creation

    Testbench: 200ns transient (va,vb inputs)

    Layout: Poly connect + Metal1 + Via + HRail

    DRC → LVS → Extraction (Assura Quantus)

    Pre-layout vs Post-layout simulation

text

## Key Results:

✅ DRC clean
✅ LVS passed
✅ Post-layout: Slower edges (parasitics added)

text

## Screenshots:

schematic.png (Fig 7.2)
symbol.png (Fig 7.3)
layout.png (Fig 7.5) ← IMPRESSIVE!
pre_post_wave.png (Fig 7.8) ← SHOWS PARASITICS

text

**Status**: Full flow complete (schematic→layout→extraction→timing) ✅

---
**Goa College of Engineering VLSI Lab*
