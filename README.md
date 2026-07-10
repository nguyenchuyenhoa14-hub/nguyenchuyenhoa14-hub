# Vo Hoang Nguyen (Nguyen) 🇻🇳

### Undergraduate Researcher in Digital IC Design & Computer Architecture

I am a final-year Computer Engineering student at **Ho Chi Minh City University of Technology (HCMUT)**, currently ranking in the **top 5%** of my class. My focus is on **Digital IC Design**, **Computer Architecture**, and **Hardware Acceleration (FPGA/ASIC)**.

Currently, I am a Research Intern at **National Taiwan University (NTU) Nano Lab**, working on 3D-IC Through-Silicon Via (TSV) dimension reconstruction.

---

## Technical Projects & Publications

### CRYPTO_SOC (Collaborative Project)
*Full-stack Cryptographic System-on-Chip featuring custom bus interconnects and hardware-accelerated security IPs.*
- Integrated **TRNG**, **SHAKE128/256**, **AES-CBC**, **Ed25519**, and **BIKE Key Encapsulation Mechanism (KEM)** for Post-Quantum Cryptography.
- Designed custom bus interconnect adapters and DMA controllers in Verilog for low-latency hardware IP streaming.
- Developed and validated as part of the **Urban Integrated Circuit Design Competition**.
- **Repository:** [BAT-LAB69/CRYPTO_SOC](https://github.com/BAT-LAB69/CRYPTO_SOC)

### YOLOv8-FPGA-Accelerator
*Custom FPGA Accelerator for real-time YOLOv8 object detection on resource-constrained platforms.*
- Designed custom detection head in Verilog to bypass edge CPU bottlenecks.
- Implemented division-free bounding-box suppression and memory-based focal loss lookup tables.
- Achieved **32.1 FPS @ 105 MHz** on a Zynq-7020 with only **0.302 W** dynamic power.
- **Publication:** Accepted for presentation at **IAAA 2026**.
- **Repository:** [YOLOv8-FPGA-Accelerator](https://github.com/nguyenchuyenhoa14-hub/YOLOv8-FPGA-Accelerator)

### Zynq-True-Random-Number-Generator
*High-speed physical entropy source implementing Jitter-Sampling TRNG on FPGA.*
- Replaced standard ring oscillators with Latch-XOR cells to optimize layout area and entropy.
- Integrated the core with a Zynq ARM processor using the AXI bus interface.
- Certified via **NIST SP 800-22** statistical randomness tests.
- **Repository:** [Zynq-True-Random-Number-Generator](https://github.com/nguyenchuyenhoa14-hub/Zynq-True-Random-Number-Generator)

### RISCV-RV32I-Pipelined-Processor
*A complete 5-stage pipelined RV32I processor designed from scratch in Verilog.*
- Synthesized cleanly at **125 MHz** on an Artix-7 FPGA.
- Features data forwarding units, hazard detection, and stall/flush control logic.
- Verified using Python testbenches comparing RTL output against an ISA reference model.
- **Repository:** [RISCV-RV32I-Pipelined-Processor](https://github.com/nguyenchuyenhoa14-hub/RISCV-RV32I-Pipelined-Processor)

### UAV Volumetric Triangulation System (Research Project)
*Terrain-independent volumetric multi-view triangulation for UAV 3D geolocation.*
- Uses multi-ray frustum intersections and skew-line triangulation across viewpoints.
- Reduced geolocation estimation errors by **22.6%** over single-ray baselines.
- **Publication:** Accepted for presentation at **IAAA 2026**.

---

## Technical Skills

- **Hardware Design & HDLs:** Verilog, SystemVerilog, MIPS Assembly
- **Software Programming:** Python, C, C++
- **FPGA & MCU Platforms:** Xilinx Zynq-7000, Artix-7, STM32 MCU
- **EDA & CAD Tools:** Vivado, Vitis, ModelSim, Altium Designer, Lumerical FDTD/RCWA

---

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nguyenchuyenhoa14-hub&show_icons=true&theme=radical&hide_border=false&border_radius=10" height="185" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nguyenchuyenhoa14-hub&layout=compact&theme=radical&hide_border=false&border_radius=10" height="185" alt="Top Languages" />
</div>

---

## Contact
- **Email:** nguyenchuyenhoa14@gmail.com
- **LinkedIn:** [Vo Hoang Nguyen](https://linkedin.com/in/nguyenchuyenhoa14)
