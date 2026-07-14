# Hi, I'm Ali 👋

I'm a computer systems architecture engineer working at the boundary of **hardware and systems**, RTL and FPGA design, GPU/CUDA systems, and the memory behaviour that connects them. Most of what I build, I verify against a reference model.

## What I work on
- **Hardware & RTL design** , quantized inference accelerators, spiking-neural hardware, fault-tolerant logic, and power management, in Verilog/SystemVerilog, verified against golden/reference models.
- **GPU & parallel systems** , CUDA kernel optimisation, memory-aware mapping, and workload characterisation.
- **Systems & infrastructure** , multi-tenant platforms, runtime resource enforcement, and performance/bottleneck analysis.

## Featured projects

### INT8 QNN Accelerator , [qnn_cifar10](https://github.com/Ali-Yazdanpanah/qnn_cifar10)
Quantized-inference datapath (Verilog/Vivado): DSP48-mapped INT8 MAC, banked weight memory, INT8 requantisation. Verified bit-exact against a Python golden model; synthesised in DSP48 and LUT-fabric modes with full utilisation/timing/power reports.

### Spiking Neural Network on FPGA , [Leaky-Integrate-and-Fire-Neurons](https://github.com/Ali-Yazdanpanah/Leaky-Integrate-and-Fire-Neurons)
BSc thesis. Fixed-point (Q4.12) leaky integrate-and-fire neurons with on-chip STDP learning, verified cycle-by-cycle against a double-precision reference model.

### DVFS Controller , [dvfs_controller](https://github.com/Ali-Yazdanpanah/dvfs_controller)
Workload-driven power management (SystemVerilog): safe voltage/frequency transition sequencing over modelled MMCM DRP and I2C/PMBus, with a self-checking testbench that verifies transition ordering across all profiles.

### Triple Modular Redundancy , [Triple-Modular-Redundancy](https://github.com/Ali-Yazdanpanah/Triple-Modular-Redundancy)
Fault-tolerant registers and on-chip RAM with majority voting and idle-cycle scrubbing; self-checking fault-injection testbench (single- and double-bit upsets) with a golden-model scoreboard.

### GPU Hash Map , [gpu_hashmap](https://github.com/Ali-Yazdanpanah/gpu_hashmap)
Lock-free CUDA key-value store using slab-hashing and warp-aggregation to cut global atomics by ~32×; benchmarked against a CPU baseline.

## Stack
- **Hardware:** Verilog, SystemVerilog, Vivado, Cadence, HSPICE
- **Languages:** C, C++, Python, CUDA, Go
- **Systems:** Linux, Docker, Kubernetes

## Contact
📫 **yazdanpanah.aly@gmail.com** · [ali-yazdanpanah.github.io](https://ali-yazdanpanah.github.io)
