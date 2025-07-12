---
title: "A High-Performance Implementation of GNN-Based Trajectory Reconstruction on FPGA"
authors:
  - Yun-Chen Yang
  - Hao-Chun Liang
  - Bo-Cheng Lai
date: "2025-01-01T00:00:00Z"
publishDate: "2025-01-01T00:00:00Z"
doi: ""
publication_types: ["paper-conference"]
publication: "Proceedings of the 33rd International Conference on Field-Programmable Logic and Applications (FPL)"
abstract: >
  We present **HiGTR**, the first end-to-end FPGA accelerator that performs
  complete GNN-based trajectory reconstruction within 4 μs for HL-LHC trigger systems.
tags: [FPGA, Graph Neural Networks, High-Energy Physics]
featured: true
url_pdf: gnn_trajectory_reconstruction.pdf
image:
  caption: "Architecture overview of HiGTR"
  focal_point: ""
  preview_only: false
---

HiGTR unifies geometry-aware graph construction, low-latency GNN inference, and sequential track building
in a single streaming pipeline on a Xilinx® Virtex UltraScale™ VU9P, achieving **2.36 µs** end-to-end latency
and **2.35 MHz** sustained throughput — comfortably meeting High-Luminosity LHC Level-1 trigger requirements.
