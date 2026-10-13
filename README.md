# Hi, I'm Maryam Imran 👋

I’m a 4th-year Electrical Engineering student focused on digital IC design, computer architecture, and hardware verification. I enjoy learning about how processors work and turning code into real, working hardware.


### What I'm Working On: CVA6 MMU Optimization

My main focus right now is my Final Year Project: **Efficient MMU Architecture: RTL to GDSII Implementation**.

Address translation can easily become a major performance bottleneck in modern processors. When you add the **RISC-V Hypervisor extension** into the mix, the translation path gets even messier with two-stage address mapping (guest-virtual to physical) and nested page-table walks. Every TLB miss adds noticeable latency to memory access.

**What I'm doing about it:**
* Analyzing address translation overhead, TLB miss rates, and page-table walk latency in the open-source **CVA6** core.
* Architecting and implementing a more efficient Memory Management Unit in **SystemVerilog** to streamline memory translation under heavy workloads.
* Running the optimized MMU through a complete **RTL-to-GDSII** physical design flow.
* Contributing my findings and design back to the open-source CVA6 project.


### Core Technical Interests

* **Processor Architecture & RISC-V:** Pipeline design, memory hierarchies, virtual memory systems, and microarchitectural optimizations.
* **RTL Design & Verification:** Writing clean, synthesizable SystemVerilog and building thorough verification environments (UVM, constrained-random testing, coverage-driven verification).
* **VLSI & Physical Implementation:** PPA (Power, Performance, Area) trade-offs, synthesis, floorplanning, and timing closure.
* **Open-Source Hardware:** Building on and contributing to real-world open-source silicon projects.

---

### Projects

* **SPI Protocol Verification:** Built a coverage-driven UVM testbench environment to verify SPI master/slave transaction integrity.
* **MAC Unit Design:** Implemented a high-throughput Multiply-Accumulate unit in RTL, focusing on pipeline stage placement and latency trade-offs.

*(Currently organizing and documenting more of my hardware design and verification projects. More repos coming soon!)*



### Tools & Technologies

* **Languages:** SystemVerilog, Verilog, C/C++, RISC-V Assembly
* **Verification & Simulation:** Verilator, GTKWave, ModelSim/Questa
* **EDA / Implementation:** Quartus, Virtuoso
* **Architecture & Tools:** RISC-V GNU Toolchain, Spike, CVA6 Core
* **Environment:** Linux, Git, Bash

---

### Connect

I'm always open to discussing digital design, computer architecture, or open-source silicon projects.

* **Email:** [maaryaamimraan@gmail.com](mailto:maaryaamimraan@gmail.com)
