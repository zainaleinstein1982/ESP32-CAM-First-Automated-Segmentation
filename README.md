# ESP32-CAM-First-Automated-Segmentation

This repository contains the source code and resources for an **ESP32-CAM-First-Automated-Segmentation** designed to meet specific requirements for ink detection, texture imaging, and segmentation evaluation.

## Features
- **Ink Detection:** Implements state-of-the-art ink detection methods comparable to the 2023 Grand Prize solutions.
- **Texture Imaging:** Generates texture images aligned with the ink detection outputs, showcasing the papyrus fiber structure.
- **Segmentation:** Produces UV-mapped meshes that are geometrically accurate and cover 95% of the Grand Prize banner.

## Requirements
- **Inputs:**
  - Maximum 4 hours of human input.
  - Maximum 48 hours of compute.
  - Segments from the 2023 Grand Prize or overlapping ones may only be used with memorization eliminated.

- **Outputs:**
  - **Geometric Checks:** Single continuous segmentation, manifold, and no self-intersections.
  - **Segmentation Accuracy:** Verified by segmentation and technical teams.
  - **Flattening:** Comparable to the 2023 Grand Prize results.
  - **Ink Detection:** Matches or exceeds the performance of the 2023 winning solution.

## Installation
1. Clone this repository:   
   git clone https://github.com/zainaleinstein1982/ESP32-CAM-Segmentation.git
   cd ESP32-CAM-Segmentation

2. Install required Python dependencies:
   pip install -r requirements.txt

3. Flash the ESP32-CAM firmware using the provided src/ files.
