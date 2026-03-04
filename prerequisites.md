---
layout: page
title: Project Prerequisites
---

## Compatibility Matrix
Before starting, ensure your stack matches these versions to avoid driver conflicts.

| Component | Requirement | Notes |
| :--- | :--- | :--- |
| **JetPack** | 6.0 / 6.1 | Includes CUDA 12.x |
| **ROS 2** | Humble | Standard for Isaac ROS |
| **Isaac Sim**| 4.0+ | Required for ROS 2 Bridge |



### **Pre-Flight Command**
Run this on your Jetson to verify the environment:
```bash
# Check if the GPU is visible
lsmod | grep nvgpu