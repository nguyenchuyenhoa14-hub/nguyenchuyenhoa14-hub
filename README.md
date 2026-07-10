# Vo Hoang Nguyen (Nguyen) 🇻🇳

[![GitHub Profile Views](https://komarev.com/ghpvc/?username=nguyenchuyenhoa14-hub&color=a31d24&style=flat-square&label=Profile+Views)](https://github.com/nguyenchuyenhoa14-hub)
[![EECS Fellowship Status](https://img.shields.io/badge/Fellowship-2027%2F2028%20EECS%20Global%20Elite-maroon?style=flat-square)](https://github.com/nguyenchuyenhoa14-hub)

I am an undergraduate student in **Computer Engineering** at **Ho Chi Minh City University of Technology (HCMUT)**, currently ranked in the top 5% of my cohort. My main academic and research interests lie at the intersection of **Digital IC Design, Computer Architecture, and Hardware Accelerators (FPGA/ASIC)**. 

Currently, I am working as a Research Intern at **National Taiwan University (NTU) Nano Lab** under Prof. Jia-Han Li, applying physics-guided deep learning to 3D-IC Through-Silicon Via (TSV) dimension reconstruction.

---

### 🔬 Research Interests
- **Hardware Accelerators:** Custom computing engines for Deep Neural Networks (Quantization, dataflow architectures, custom decoders).
- **Computer Architecture:** Custom RISC-V extensions, multi-stage pipelines, and memory-efficient data buses.
- **Hardware Security:** Physical entropy extraction, True Random Number Generators (TRNG), and cryptographic accelerator design (AES).
- **Physical-Layer Co-Design:** 3D-IC packaging, Through-Silicon Via (TSV) metrology, and physical parasitics optimization.

---

### 💻 Featured Research & Hardware Projects

#### 🚀 [YOLO_Tank](https://github.com/nguyenchuyenhoa14-hub/YOLO_Tank)
*Custom FPGA Accelerator for real-time YOLOv8 object detection on resource-constrained platforms.*
- Designed a custom detection head in Verilog bypassing the CPU post-processing bottleneck.
- Implemented division-free bounding-box suppression and memory-based focal loss lookup tables.
- Achieved **32.1 FPS at 105 MHz** on a Zynq-7020 with only **0.302 W** dynamic power.
- **Publication:** Accepted for presentation at **IAAA 2026**.

#### 🔒 [Zynq-True-Random-Number-Generator](https://github.com/nguyenchuyenhoa14-hub/Zynq-True-Random-Number-Generator)
*High-speed physical entropy source implementing Jitter-Sampling TRNG on FPGA.*
- Replaced standard ring oscillators with Latch-XOR cells to optimize layout area and entropy.
- Integrated the core with a Zynq ARM processor using the AXI bus interface.
- Passed all **NIST SP 800-22** statistical randomness tests.

#### ⚙️ [PipelineDatapath](https://github.com/nguyenchuyenhoa14-hub/PipelineDatapath)
*A complete 5-stage pipelined RV32I processor designed from scratch in Verilog.*
- Synthesized cleanly at **125 MHz** on an Artix-7 FPGA.
- Features data forwarding units, hazard detection, and stall/flush control logic.
- Verified using Python testbenches comparing RTL output against a gold ISA reference model.

#### 🛰️ [UAV_detection_and_Tracking](https://github.com/nguyenchuyenhoa14-hub/UAV_detection_and_Tracking)
*Volumetric multi-view triangulation software for drone-based target localization.*
- Uses multi-ray frustum intersections and skew-line triangulation across viewpoints.
- Reduced geolocation estimation errors by **22.6%** over single-ray baselines.
- **Publication:** Accepted for presentation at **IAAA 2026**.

---

### 🛠️ Technical Stack & Tools

- **Languages:** Verilog, SystemVerilog, C, C++, Python, MIPS Assembly
- **Hardware Platforms:** Xilinx Zynq-7000 (Zynq-7020), Artix-7, Arty Z7-20, STM32 MCU
- **EDA & CAD Tools:** Vivado, Vitis, ModelSim, Ansys Lumerical (FDTD/MODE/RCWA), Altium Designer, PSpice
- **Frameworks & Libs:** PyTorch, NumPy, SciPy, OpenCV, Git

---

### 📫 Let's Connect!
- **Email:** [nguyenchuyenhoa14@gmail.com](mailto:nguyenchuyenhoa14@gmail.com)
- **LinkedIn:** [Vo Hoang Nguyen](https://linkedin.com/in/nguyenchuyenhoa14)
- **Phone:** (+886) 0975 871 426
