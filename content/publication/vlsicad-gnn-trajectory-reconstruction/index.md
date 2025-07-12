---
authors:
+title: "A High-Performance Implementation of GNN-Based Trajectory Reconstruction on FPGA"
  - Hao-Chun Liang
+  - Yun-Chen Yang
date: "2025-01-01T00:00:00Z"
+  - Bo-Cheng Lai
doi: ""
+publishDate: "2025-01-01T00:00:00Z"
publication: "Proceedings of the 33rd International Conference on Field-Programmable Logic and Applications (FPL)"
+publication_types: ["paper-conference"]
  We present **HiGTR**, the first end-to-end FPGA accelerator that performs
+abstract: >
tags: [FPGA, Graph Neural Networks, High-Energy Physics]
+  complete GNN-based trajectory reconstruction within 4 μs for HL-LHC trigger systems.
url_pdf: gnn_trajectory_reconstruction.pdf
+featured: true
  caption: "Architecture overview of HiGTR"
+image:
  preview_only: false
+  focal_point: ""

+---
in a single streaming pipeline on a Xilinx® Virtex UltraScale™ VU9P, achieving **2.36 µs** end-to-end latency
+HiGTR unifies geometry-aware graph construction, low-latency GNN inference, and sequential track building

+and **2.35 MHz** sustained throughput — comfortably meeting High-Luminosity LHC Level-1 trigger requirements.