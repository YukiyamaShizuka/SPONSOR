# Signal_X86 Summer Development Environment – Sponsorship Request **(Hardware Delivery Required by July 1, 2025)**

This document outlines the full hardware configuration for the Signal_X86 low-level systems development platform. The goal is to build a transparent, deterministic execution stack for assembly-level experimentation, instruction tracing, and kernel module simulation under the Signal programming language runtime.

This is a formal sponsorship request. If accepted, please **ensure delivery is completed before July 1, 2025** to the following address:

**Delivery Address:**  
Baojing New Village‌, Lujiang County, Hefei City, Anhui Province, China  
**Phone:** 136‑9652‑5769 *(for courier use only; all other inquiries via email: shizuka@treeos.art)*  

**If the sponsored equipment has been shipped, please notify me with the tracking number via email.**

---

## The hardware version and configuration are finalized. All listed components are fixed for delivery and documentation:

## CPU & Motherboard

- **Processor**: Intel Xeon W-3595X (60Cores , 120Threads , LGA4677)
- **Motherboard**: ASUS Pro WS W790-ACE
- **Purpose**: High-performance multi-core simulation, AVX-512 parallelism, ECC memory integration for stable memory-critical workloads.

## Memory

- **Size**: 2TB (8 × 256GB SK hynix DDR5-4800 ECC RDIMM)
- **Purpose**: Enables full-memory simulation environments for deterministic vector execution and memory-mapped system calls.

## GPU

| Quantity | Model / Configuration                                                                                                                   |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------|
| 3        | NVIDIA RTX PRO 6000 Blackwell Workstation Edition (Retail Box)                                                                          |
| 2        | NVIDIA H200 NVL PCIe GPU                                                                                                                |
| 1        | **Dell PowerEdge XE9680** — **2** × Intel Xeon Platinum **8593Q** (**64** cores each, **128** cores total)  ·  System Memory: **4** TB DDR5-5600 RECC RDIMM (Registered ECC)  ·  GPU: 8 × NVIDIA H200 141GB SXM5 GPUs (700W TDP each, for compute only), fully interconnected via NVLink on HGX H200 board; **1** × NVIDIA RTX 2000 Ada (Tray/OEM Pack, Factory-Installed via Configuration Service, for 4K HDR primary display output only)  ·   System Storage: 1 × **4** TB PCIe 5.0 NVMe M.2 SSD (OS)  ·  Data Storage: 8 × 2.5-inch U.2/U.3 NVMe SSD (15.36 TB each, total 122.88 TB)  ·  LCD Bezel|
- **Purpose**: CUDA-backed runtime acceleration for instruction visualization, GPGPU compilation testing, and real-time pipeline rendering for the Signal virtual machine.

## Power Supply

- **Model**: Great Wall GW-EPS3000BL(94+)
- **Quantity**: 1 unit
- **Purpose**: Stabilized power under dual-GPU and 2TB ECC RAM conditions. Suitable for 24/7 simulation runs.

## Cooling

- **Model**: COOLSERVER **LGA4677 M99** Tower Cooler
- **Quantity**: 1 unit
- **Purpose**: Passive and active airflow regulation for Xeon socket, critical to maintaining frequency integrity under thermal stress.

## Monitor

- **Model**: ASUS ProArt PA32UCXR 32” 4K HDR Mini-LED Display (P/N PA32UCXR)
- **Quantity**: 3 units
- **Purpose**: Precise representation of assembly flow, binary trace overlays, and full-range color debugging during signal-mapped visualizations.

## Computer Case

- **Model**: ASUS ProArt PA602 Wood Edition with Tempered Glass Panel (P/N 90DC00J0-B08010）
- **Quantity**: 1 unit
- **Purpose**: High airflow support and component spacing for workstation-class builds.

## System Storage

- **Model**: Samsung 9100 PRO 4TB – PCIe 5.0 x4 NVMe, M.2 2280 (P/N MZ-VAP4T0BW)
- **Quantity**: 1 unit
- **Purpose**: High-throughput I/O tracing, page file analysis, live recompilation caching, and runtime log capture.

## Data Storage

- **Model**: SOLIDIGM D7-PS1010 PCIe5.0 U.2 NVMe 2.5" (15 mm) 15.36TB
- **Quantity**: 2 units

## Wi-Fi / Bluetooth

- **Module**: Intel Wi-Fi 7 BE200NGW (M.2 2230 E-Key, Wi-Fi 7 + BT 5.4)
- **Quantity**: 1 unit
- **Standards**: Wi-Fi 7 / Bluetooth 5.4

## Peripherals

- **Keyboard**: 2 x ROG RX98 Wireless Mechanical Keyboard (White Edition , 2.4 GHz/BT/wired, Triple‑mode)
- **Mouse**: 2 x ASUS ROG Keris II Ace Wireless Mouse (White Edition , 2.4 GHz/BT/wired, Triple‑mode)  
- **Speaker**: Edifier Halo SoundBar (Cherry Blossom Pink Edition)
- **Fan**: 3 x Lian Li UNI FAN TL140 Wireless ARGB Standard Blade Fan (Black/LCD Edition)
- **Fan Controller**: Lian Li UNI FAN TL Wireless Controller (Transmitter , required for the TL wireless fans , Black/LCD Edition)
- **Cable**: 2 x PCIe4.0 SlimSAS SFF-8654 4i to SFF-8639 U.2 NVMe Cable(50cm)
- **NVLink**: 3 x NVIDIA 2-way NVLink Bridge for H200 NVL.
- **Purpose**: 
   - Provides low-latency, ergonomic input for long development sessions, console emulation, and breakpoint debugging.
   - The wireless TL140 fans, powered by 2.4 GHz L‑Wireless sync, use standard-direction blades for strong airflow, optimizing chassis cooling without cable clutter.

## Tablet

- **Model**: Microsoft Surface Pro (11th Edition) – Intel Core Ultra 7 268V / 13-inch PixelSense Flow Display / 32 GB LPDDR5x RAM / 1 TB SSD / Platinum – with Surface Pro Keyboard (Silver) & Surface Slim Pen2.
- **Purpose**: To draw program-execution path diagrams.

## Laptop for testing

- **Model**: Dell Precision 17 7780 Mobile Workstation (i9-13950HX/128G/6T/5000Ada/4K 120Hz)
- **Purpose**: Testing Signal on a standalone device to identify problems.

---

## 📬 Delivery Reminder

If this configuration is approved for sponsorship, please arrange for shipping via **JD Express** only, ensuring arrival **no later than July 1, 2025**. Timely delivery is critical for inclusion in the summer Signal_X86 development timeline.
