# CMOS Inverter - Transient Analysis

**Cadence Virtuoso lab**: Propagation delay, rise/fall time

## Measurements:

    tpLH: Input↑ → Output↓ (50% points)

    tpHL: Input↓ → Output↑ (50% points)

    tp = (tpLH + tpHL)/2

    tr: Output 10%→90% (0.18V→1.62V)

    tf: Output 90%→10% (1.62V→0.18V)

text

## Methods used:

    Manual: H(0.9V) + V markers on waveforms

    Calculator: delay(), risetime(), falltime()
    Input: 20ns period, 0.5ns rise/fall, Vdd=1.8V

text

## Results:

Manual: tp=____ps, tr=____ps, tf=____ps
Calculator: tp=____ps, tr=____ps, tf=____ps

text

## Screenshots:

testbench.png (Fig 4.1)
adel_setup.png (Fig 4.2)
calculator.png (Fig 4.3)
waveform.png (Fig 4.4) ← KEY RESULT

text

**Status**: tp, tr, tf calculated ✅

---
**Goa College of Engineering VLSI Lab**
