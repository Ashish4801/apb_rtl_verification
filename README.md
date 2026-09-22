# apb_rtl_verification
AMBA APB Master and Slave interface design in [Verilog/SystemVerilog]. Includes a scalable architecture and complete verification testbench.

# AMBA APB (Advanced Peripheral Bus) IP Core

This repository contains a fully synthesizable RTL implementation of the AMBA APB protocol. Designed for low-bandwidth control accesses, this APB interface is optimized for connecting low-power peripherals to the system bus without the need for complex pipelining. 

It is ideal for interfacing with components like timers, interrupt controllers, UARTs, and custom low-speed hardware accelerators.

## Key Features
* **Protocol Compliance:** Fully conforms to the AMBA APB protocol specification (specify version, e.g., APB3 / APB4).
* **Language:** Written in [Verilog / SystemVerilog / VHDL].
* **Configurable:** Easily parameterized data and address bus widths (default is 32-bit).
* **Low Power & Area:** Minimal logic overhead designed for power-sensitive peripheral subsystems.
* **Verification:** Includes a complete [UVM / standard] testbench with basic read/write transaction examples.
