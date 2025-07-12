---
title: "A High-Performance Implementation of GNN-Based Trajectory Reconstruction on FPGA"
authors:
  - Yun-Chen Yang
  - Hao-Chun Liang
  - Bo-Cheng Lai
date: "2025-01-01T00:00:00Z"
publishDate: "2025-01-01T00:00:00Z"
doi: ""
publication_types: ["symposium-paper"]
publication: "2025 VLSI Design / CAD Symposium"
publication_short: ""
abstract: >
  Field-programmable gate arrays (FPGAs) equipped with graph neural networks (GNNs) are a compelling platform for real-time charged-particle tracking at the High-Luminosity Large Hadron Collider (HL-LHC). Each event must be processed within 4 μs while sustaining more than 2.22 MHz throughput. Existing prototypes fall short of these targets and accelerate only the GNN inference stage, omitting the remainder of the reconstruction pipeline. In this paper, we propose the first FPGA accelerator that performs complete GNN-based trajectory reconstruction. Our work unifies geometry-aware graph construction, low-latency GNN inference, and sequential track building in a single AXI-Stream pipeline. Its core contributions are: (i) a geometry-guided graph constructor that prunes spurious edges, (ii) a scheduling-optimized GNN engine that reduces inference latency by 52.3 % through fine-grained pipelining and resource sharing, and (iii) a lightweight track builder that removes clustering overhead while improving resource efficiency and tracking accuracy. Design parameters allow the pipeline to be tuned for diverse HL-LHC scenarios. Implemented on a Xilinx® Virtex UltraScale VU9P, our work achieves 2.36 μs end-to-end latency and 2.35 MHz sustained throughput, exceeding the HL-LHC Level-1 trigger requirements. Comprehensive benchmarks confirm scalability and position our work as a template for next-generation AI acceleration in data-intensive science.
summary: FPGA-accelerated GNN pipeline for HL-LHC exceeding latency and throughput requirements.
tags: [FPGA, Graph Neural Networks, High-Energy Physics]
featured: true
url_pdf: uploads/gnn_trajectory_reconstruction.pdf
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
image:
  caption: "Architecture overview of HiGTR"
  focal_point: ""
  preview_only: false
projects: []
slides: ""
---

Field-programmable gate arrays (FPGAs) equipped with graph neural networks (GNNs) are a compelling platform for real-time charged-particle tracking at the High-Luminosity Large Hadron Collider (HL-LHC). Each event must be processed within 4 μs while sustaining more than 2.22 MHz throughput. Existing prototypes fall short of these targets and accelerate only the GNN inference stage, omitting the remainder of the reconstruction pipeline. In this paper, we propose the first FPGA accelerator that performs complete GNN-based trajectory reconstruction. Our work unifies geometry-aware graph construction, low-latency GNN inference, and sequential track building in a single AXI-Stream pipeline. Its core contributions are: (i) a geometry-guided graph constructor that prunes spurious edges, (ii) a scheduling-optimized GNN engine that reduces inference latency by 52.3 % through fine-grained pipelining and resource sharing, and (iii) a lightweight track builder that removes clustering overhead while improving resource efficiency and tracking accuracy. Design parameters allow the pipeline to be tuned for diverse HL-LHC scenarios. Implemented on a Xilinx® Virtex UltraScale VU9P, our work achieves 2.36 μs end-to-end latency and 2.35 MHz sustained throughput, exceeding the HL-LHC Level-1 trigger requirements. Comprehensive benchmarks confirm scalability and position our work as a template for next-generation AI acceleration in data-intensive science.