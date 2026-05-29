# AI-Based Sketch Completion and Physical Rendering using XY Plotter

## Overview
This project presents an end-to-end AI-powered system that completes incomplete hand-drawn sketches and physically renders the completed output using an XY plotter.

The system integrates computer vision, deep learning (SDXL), and hardware control to bridge the gap between digital sketch processing and real-world drawing.

---

## Key Features
- AI-based sketch completion using Stable Diffusion XL (SDXL)
- Image preprocessing and sketch extraction using OpenCV
- ArUco marker-based calibration and perspective correction
- Vectorization and path planning for drawing
- Coordinate transformation from image space to real-world plotting space
- Physical rendering using AxiDraw XY plotter

---

## System Workflow
1. Capture incomplete sketch using a webcam  
2. Detect paper boundaries using ArUco markers  
3. Apply perspective transformation for top-down alignment  
4. Extract sketch using image processing techniques  
5. Perform AI-based sketch completion using SDXL  
6. Extract generated lines and convert to vector paths  
7. Transform coordinates to match plotter space  
8. Render the completed sketch using XY plotter  

---

## Technologies Used
- **Programming:** Python  
- **AI Model:** Stable Diffusion XL (SDXL)  
- **Libraries:** OpenCV, NumPy, PyTorch, Hugging Face Diffusers, PIL  
- **Hardware:** AxiDraw XY Plotter, Webcam  
- **Acceleration:** CUDA, xFormers  

---

## What Makes This Unique
- Combines AI image generation with physical drawing output  
- Fully automated pipeline from sketch capture to plotting  
- Real-world coordinate mapping using homography  
- Human-AI collaborative drawing system  

---

## Applications
- Art restoration and enhancement  
- Educational drawing assistance  
- Interactive art systems  
- Rapid prototyping for design  

---

## Future Scope
- Mobile app integration for remote control  
- Real-time preview before plotting  
- Multi-user collaborative drawing  
- Support for larger paper formats  

---

## Status
Work in progress – project files and demo will be uploaded soon.
