<div align="center">
  
# 👋 Kamsani Yashwanth Chowdhary

### ⚡ **ECE × CSE** — Bridging Silicon and Intelligence ⚡

[![Email](https://img.shields.io/badge/-yashwanthchowdhary83@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:yashwanthchowdhary83@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-kamsani--yashwanth--chowdhary-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kamsani-yashwanth-chowdhary)
[![GitHub](https://img.shields.io/badge/-@Yash1026--hash-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yash1026-hash)
[![IEEE](https://img.shields.io/badge/-IEEE%20ComSoc-00629B?style=flat-square&logo=IEEE&logoColor=white)]()

📍 Hyderabad, Telangana · 📞 +91 72073 30433

---

</div>

<!-- Dual Domain Architecture Banner -->

```verilog
module Yashwanth #(parameter DOMAIN = "ECE + CSE") (
    input  wire        clk_silicon,      // 50 MHz ECE clock
    input  wire        clk_software,     // async software domain
    output reg  [31:0] innovation,       // novel solutions out
    input  wire        resetn            // active-low resilience
);

  // Dual-domain synchronization fabric
  always @(posedge clk_silicon or negedge resetn) begin
    if (!resetn)
      innovation <= 32'h0000_0000;
    else
      innovation <= innovation + 1;  // perpetual growth mindset
  end

endmodule
```

---

## 🧬 Dual-Domain Expertise

<table>
<tr>
<td width="50%" valign="top">

### 🔬 **Electronics & VLSI Engineering**

| Category | Stack |
|----------|-------|
| **HDL & Design** | Verilog HDL, SystemVerilog, RTL Design, FSM Design |
| **Verification** | UVM, ATPG, D-Algorithm, SCOAP |
| **EDA Tools** | Vivado ML, ModelSim, Cadence Virtuoso, LTSpice |
| **Physical Design** | Floorplanning, P&R, HPWL, RC-Grid, Thermal Modeling |
| **DSP** | FIR/IIR Filters, FFT, DDS, CORDIC |
| **Protocols** | AXI4-Stream, SPI, I2C, UART |

</td>
<td width="50%" valign="top">

### 🤖 **Computer Science & AI Engineering**

| Category | Stack |
|----------|-------|
| **Languages** | Python, C, C++, SQL, Bash |
| **ML/DL** | PyTorch, TensorFlow, YOLOv8, Scikit-learn |
| **Computer Vision** | OpenCV, Object Detection, Image Segmentation |
| **DevOps & Tools** | Docker, FastAPI, Git, Linux, REST APIs |
| **Embedded AI** | Raspberry Pi 4, ESP32, Edge AI Inference |
| **Concepts** | RL, CNN, Transfer Learning, PID Control |

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<div align="center">

### **VLSI & Hardware Design**

</div>

<table>
<tr>
<td width="33%" valign="top">

### 🎛️ FPGA DSP Processing Chain
`SystemVerilog` `AXI4-Stream` `Vivado ML`

Designed a 5-IP AXI4-Stream DSP pipeline on Artix-7 FPGA with DDS, FIR, CIC, FFT & CORDIC blocks. Implemented 31-tap Hamming-window FIR filter with ILA-based hardware debugging.

</td>
<td width="33%" valign="top">

### 🔥 Thermal-Aware VLSI Floorplanning
`Python` `MATLAB`

Hybrid PSO + Simulated Annealing optimizer for HPWL, routing congestion & thermal hotspot minimization using RC-grid modeling. Benchmarked on MCNC circuits.

</td>
<td width="33%" valign="top">

### ✅ RTL & UVM Verification
`SystemVerilog` `UVM` `Vivado`

True Dual-Port RAM with BRAM inference on Zynq. Built complete UVM env (sequencer → driver → monitor → scoreboard → coverage) with ATPG & SCOAP analysis.

</td>
</tr>
</table>

<div align="center">

### **AI & Software Engineering**

</div>

<table>
<tr>
<td width="33%" valign="top">

### 🚦 Smart Urban Traffic Density Analyzer
`YOLOv8l` `Python` `Docker` `OpenCV`

Real-time vehicle detection & traffic density pipeline with multi-threaded OpenCV. 🏆 **Top 3 at IISc Bangalore Urban Vision Hackathon 2024** (200+ teams).

</td>
<td width="33%" valign="top">

### 🥭 Mango Disease Detection System
`YOLOv8` `Python` `OpenCV`

Multi-class crop disease detector trained on custom annotated mango leaf dataset. Designed for low-resource edge deployment in agricultural IoT.

</td>
<td width="33%" valign="top">

### 🔄 Chip Cycle — ASIC RL Environment
`Python` `FastAPI` `Docker` `Open Env`

OpenEnv-compliant RL environment where AI agents review ASIC design reports — synthesis QoR, STA debug, MCMM sign-off. Deployed on Hugging Face Spaces.

</td>
</tr>
</table>

---

## 📊 System-On-Chip: Yashwanth

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                    YASHWANTH SoC ARCHITECTURE                │
├─────────────────────────────────────────────────────────────┤
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │  VLSI    │  │   DSP    │  │   ML     │  │   SW     │   │
│  │  RTL     │←→│  Engine  │←→│  Core    │←→│  Stack   │   │
│  │  Design  │  │  (FPGA)  │  │ (YOLOv8) │  │ (Docker) │   │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘   │
│        └─────────────┬──────────────────────┘              │
│                      ▼                                     │
│           ┌─────────────────────┐                          │
│           │  AXI4-Stream Bus    │                          │
│           │  (Interconnect)     │                          │
│           └─────────────────────┘                          │
│                      │                                     │
│           ┌──────────▼──────────┐                          │
│           │   Problem Solver    │                          │
│           │  Innovation Engine  │                          │
│           └─────────────────────┘                          │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## 🏛️ Leadership & Community

| Role | Organization | Period |
|------|-------------|--------|
| **Vice President** | Aparmaya Club (AI & Autonomous Systems), KL University | Jan 2024 – Present |
| **Treasurer** | IEEE ComSoc Student Chapter, KL University | Jan 2025 – Present |

> *Leading 30+ engineers across AI, robotics, VLSI & embedded systems. Organized "Samyak" national-level tech fest (200+ attendees). Reduced integration defects by 40% through structured code reviews.*

---

## 🎓 Education

| Degree | Institution | Year | CGPA |
|--------|------------|------|------|
| **B.Tech ECE (VLSI Specialization)** | KL Deemed University, Hyderabad | May 2027 | 8.29/10 |
| **Diploma ECE** | Anurag Engineering College, Telangana | 2024 | 9.18/10 |
| **SSC** | ZPHS Konijerla, Telangana | 2021 | 10/10 |

---

## 🏆 Achievements

```
═══════════════════════════════════════════════════════════════
  🥉  TOP 3 — IISc Bangalore Urban Vision Hackathon 2024
      (200+ teams — AI-based traffic analytics)
  
  🥉  TOP 3 — VR Siddhartha Engineering College Hackathon 2023
      (150+ teams — autonomous robotics)
  
  📝  AUTHORED technical content & IEEE outreach reaching 
      1,000+ students across university community
  
  🎤  ORGANIZED 5+ workshops on ML, signal processing & 
      communications as IEEE ComSoc Treasurer
═══════════════════════════════════════════════════════════════
```

---

## 📈 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Yash1026-hash&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=ff6f61&icon_color=ff6f61&text_color=c9d1d9)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Yash1026-hash&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=ff6f61&text_color=c9d1d9)

</div>

---

<div align="center">

### 🔄 *"Bridging the gap between Silicon and Software — one RTL block and one model at a time."*

---

![Profile Views](https://komarev.com/ghpvc/?username=Yash1026-hash&color=ff6f61&style=flat-square&label=Profile+Views)
[![Repos](https://img.shields.io/badge/dynamic/json?style=flat-square&label=Repositories&query=%24.public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2FYash1026-hash&color=ff6f61)]()
[![Open Source Love](https://img.shields.io/badge/-Open%20Source%20Enthusiast-ff6f61?style=flat-square)]()

**Let's connect and build something extraordinary!** 🚀

</div>
