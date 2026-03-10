# 3D Human Reconstruction using Gaussian Splatting
## Overview

This project implements a 3D human reconstruction pipeline using 3D Gaussian Splatting, a neural rendering technique that enables real-time photorealistic scene representation. The system reconstructs a 3D model of a person from multi-view video frames and renders novel viewpoints with high visual fidelity.

By capturing video footage of a subject and processing the frames through a Gaussian Splatting pipeline, the project demonstrates how modern neural rendering techniques can generate real-time 3D representations of real-world scenes.

## Demo
Input Video

Multi-view video of a subject captured from different perspectives.

Output

A reconstructed 3D human model rendered using Gaussian splatting with interactive viewpoint changes.

Example outputs are shown in the demo videos included in the repository.

## Methodology
# 1. Video Capture

A video of the subject is recorded from multiple viewpoints to capture sufficient visual coverage for reconstruction.

# 2. Frame Extraction

The video is converted into individual frames which serve as the dataset for reconstruction.

# 3. Camera Pose Estimation

Camera poses are estimated using Structure-from-Motion (SfM) techniques to determine the spatial relationships between frames.

# 4. Gaussian Splatting Training

The extracted frames and camera parameters are used to train a 3D Gaussian Splatting model, which represents the scene as a collection of anisotropic Gaussian primitives.

# 5. Rendering

The trained model is used to render novel viewpoints of the reconstructed subject in real time.

## Technologies Used

Python

PyTorch

3D Gaussian Splatting

COLMAP (Structure-from-Motion)

Computer Vision

Neural Rendering

## Results
The system successfully reconstructs a 3D representation of the subject from 2D video frames. The Gaussian splatting method enables:

High-quality photorealistic rendering

Real-time viewpoint changes

Efficient scene representation

This demonstrates the potential of neural rendering techniques for 3D avatar creation, AR/VR environments, and digital human reconstruction.

## Future Improvements

Improve reconstruction quality with additional viewpoints

Implement dynamic human modeling

Integrate diffusion-based neural rendering

Enable real-time capture and reconstruction

Add interactive 3D viewer

## Author 
 Xiaohan Jiang 
