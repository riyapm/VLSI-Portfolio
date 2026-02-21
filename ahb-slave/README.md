# AHB-to-APB Bridge
Maven Silicon Internship Project (July-Aug 2025)

**What I did:**
- Trained at Maven Silicon, Bangalore (45 days)
- Built AHB-to-APB bridge in Verilog
- Used ModelSim for simulation, Quartus for synthesis

**Project blocks:**

AHB Side → Bridge → APB Side (UART/Timer/GPIO)

    AHB Slave: Gets address/data from master

    APB Controller: Makes PSEL, PENABLE, PWRITE

    APB Interface: Talks to peripherals

text

**Key parts:**
- HADDR[31:0], HWDATA[31:0] → PADDR, PWDATA
- Pipeline registers: HADDR1→HADDR2  
- FSM: IDLE → SETUP → ACCESS
- Address decode: 0x60000000 = Peripheral 1

**Tools used:**
- ModelSim (waveform debugging)
- Quartus Prime (FPGA synthesis)

**Status:** RTL + testbench complete

---
**Goa College of Engineering** | PRN: 202211392
