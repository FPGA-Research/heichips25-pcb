# HeiChips 2025 PCB

The official PCB for HeiChips 2025

> [!NOTE]
> This repository is currently a placeholder and will be populated before the chips come back.

General ideas:

- Create a daughterboard that houses the chip similar to the [Tiny Tapeout Demo Board](https://github.com/TinyTapeout/tt-demo-pcb)
- 5V to 3.3V and 1.5V
- Add RP2350 to the PCB
    * Clock generation
    * Can upload the bitstream via USB
    * Needs dedicated QSPI flash
    * Oscillator
    * USB socket
- Reset signal
    * Jumper selects between a button, the FPGA busy signal from the chip, or a pin from the RP2350.
- USB connector on dedicated pins of the chip
- HDMI connector on dedicated pins of the chip
- Ethernet connector (additional chips needed?)
- Pmod connectors (Tiny VGA, Audio Pmod, could plugin the QSPI Pmod from Tiny Tapeout for FazyRV?)
- ...

We are quite flexible with the pinout, as the eFPGA can be reconfigured.