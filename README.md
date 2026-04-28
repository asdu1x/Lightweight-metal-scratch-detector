Lightweight Metal Scratch Detector via Cross-Layer Key Adaptive Feature Distillation
=============================================================================
This paper has been submitted to [The Visual Computer].

Repository: https://github.com/asdu1x/Lightweight-metal-scratch-detector 

This repository contains code for our lightweight metal scratch detector. It is intended to provide a demonstration of the model described in the paper.

-------
Environment
-------
The code has been tested on:
  - Windows 10
  - Python 3.7+
  - PyTorch 1.6.0+ (CUDA 10.1 or later recommended)
  - A GPU with at least 6 GB memory is recommended for smooth inference. CPU-only inference is also supported but will be slower.

-------
Quick Start
-------
1. Install dependencies:
   pip install -r requirements.txt

2. Install detectron2 [https://github.com/facebookresearch/detectron2]    

3. Place metal surface images in the "image_path" and weight in the "cfg.MODEL.WEIGHTS".

5. Run demo.py

---
Data Availability
---
The data that support the findings of this study are available from the corresponding author upon reasonable request.

---
Contact
---
Bo Zhang
bo_zh@scu.edu.cn
