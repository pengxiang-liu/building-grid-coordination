<div align="center">
<h1>Building-Grid Coordination</h1>
<p align="center">
  <a href="https://pengxiang-liu.github.io/">Pengxiang Liu<sup>1</sup></a>
  &middot;
  <a href="https://www.researchgate.net/profile/Haolin-Wang-21">Haolin Wang<sup>2</sup></a>
  &middot;
  <a href="https://ee.seu.edu.cn/wz/list.htm">Zhi Wu<sup>2</sup></a>
  &middot;
  <a href="https://ee.seu.edu.cn/gw/list.htm">Wei Gu<sup>2</sup></a>
  &middot;
  <a href="https://scholars.cityu.edu.hk/en/persons/zijzhang/">Zijun Zhang<sup>1*</sup></a>
  <br/>
  <sup>1</sup> Department of Data Science, City University of Hong Kong, Hong Kong
  <br/>
  <sup>2</sup> School of Electrical Engineering, Southeast University, China
</p>
<a href="https://pengxiang-liu.github.io/publications"><img src="https://img.shields.io/badge/Manuscript-Under%20Review-blue"></a>
<a href="data"><img src="https://img.shields.io/badge/Repository-Data%20Only-orange"></a>
<a href="https://mit-license.org/"><img src="https://img.shields.io/badge/License-MIT-green"></a>
</div>

## 🌟 Overview

Welcome to **Building-Grid Coordination**, the official repository for the paper **"Global Optimization of RNN-Embedded Building-Grid Coordinated Operation via Gating-Aware Spatial Branching"**.

In this paper, we develop a data-driven building-grid coordination framework that embeds a gated-RNN-based sequence-to-sequence building energy prediction model into power system economic dispatch problems. To obtain the global optimum of the resulting non-convex program, we design a novel gating-aware spatial branching strategy for the sigmoid, hyperbolic-tangent, and bilinear constraints introduced by the gating mechanism of RNNs.

> **Project status:** The manuscript is currently under review at *IEEE Transactions on Power Systems*. Only the research data are publicly available at this stage; the complete source code will be released after the paper is formally accepted.

## 📁 Repository Structure

```text
.
├── article/            # Article materials (to be released after paper acceptance)
├── data/
│   ├── architecture/   # Building archetypes, assemblies, and components
│   ├── building/       # Building datasets, simulation results, and model weights
│   ├── microgrid/      # IEEE 33-bus and 136-bus test systems
│   ├── scenario/       # Cooling and heating operating scenarios
│   ├── weather/        # Weather data used in the experiments
│   └── metadata.json   # Dataset metadata
├── src/                # Source code (to be released after paper acceptance)
├── environment.yaml    # Python environment specification
├── LICENSE             # License information
└── README.md           # Project documentation
```

The `article/` and `src/` directories are planned for a future release and will be uploaded after the paper is formally accepted.
