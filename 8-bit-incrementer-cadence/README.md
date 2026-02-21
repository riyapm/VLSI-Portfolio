# 8-Bit Incrementer - Cadence Virtuoso

**Cadence project**: 8-bit binary counter (+1 to input)

## How it works:
- **8 Half Adders** cascaded
- First bit: `1 + A0` 
- Each next bit: `A[i] + CarryFromPrevious`
- Output: `S0-S7` (incremented) + `CARRY`

## Cadence Flow:

    NAND gates (PMOS/NMOS) → Half Adder (NAND only)

    8 Half Adders → 8-bit incrementer schematic

    Layout → Extracted view → Simulation

    Spectre: Transient analysis (200ns)

text

## Results:
- **Power**: 33μW average
- **Delay**: 100-316ps per bit (A0→S0 fastest)
- **Tech**: gpdk090 (90nm)

## Screenshots:

nand_gate_waveform.png (Step 1)
half_adder_schematic.png (Step 2)
8bit_incrementer_layout.png (Step 3)
final_waveform.png (S0-S7 vs A0-A7)

text

**Status**: Schematic + Layout + Simulation
