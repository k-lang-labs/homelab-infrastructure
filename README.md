# Project Terralith: High-Performance Home Lab

## Overview
A custom-built enterprise server designed for localized Large Language Model (LLM) fine-tuning and high-tick-rate game server hosting.

## Hardware Specifications
* **Chassis:** Dell Precision T5810 Workstation
* **CPU:** Intel Xeon E5-1620 v3 (4 Cores @ 3.50GHz)
* **GPU:** NVIDIA Tesla P40 (24GB GDDR5) for AI Inference
* **Cooling:** Custom 3D-printed shroud with high-static pressure fan mod for passive GPU cooling
* **RAM:** 16GB DDR4 ECC

## Software Stack
* **OS:** Ubuntu Server 24.04 LTS (Headless)
* **Management:** OpenSSH, Screen, Docker
* **Optimization:** Custom Java flags (Aikar's), Tuned Kernel parameters for low-latency I/O

## Projects Hosted
1.  **Industrial Minecraft Server:**
    * Forge 1.20.1 instance with 170+ mods (Create, Immersive Engineering).
    * Optimized with ServerCore and Embeddium for multi-threaded chunk loading on legacy Xeon architecture.
    * Pre-generated 5k radius world border to minimize CPU overhead.
2.  **Local AI (In Progress):**
    * Configuring NVIDIA drivers for headless Tesla P40 compute.
