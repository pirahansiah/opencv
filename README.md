# OpenCV 3 — Computer Vision with C++ & Visual Studio 2015

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![OpenCV](https://img.shields.io/badge/OpenCV-3.x-blue.svg)](https://opencv.org)
[![Platform](https://img.shields.io/badge/Platform-Windows%2064--bit-lightgrey.svg)](https://www.microsoft.com/windows)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorials-red.svg)](https://www.youtube.com/tiziran)

OpenCV 3 prebuilt libraries and example projects for Visual C++ 2015 on Windows 64-bit. Includes ready-to-use binaries for rapid prototyping of computer vision applications.

> **Project by Dr. Farshid Pirahansiah** — [www.tiziran.com](https://www.tiziran.com) | [YouTube](https://www.youtube.com/tiziran)

## What's Included

- **OpenCV 3.x prebuilt static/dynamic libraries** for Visual C++ 2015 (Win64)
- Sample C++ project configurations for Visual Studio 2015
- Ready-to-run binaries for immediate experimentation

## Quick Start

1. Download `OpenCV3.xVC++2015win64x.zip` from this repository
2. Extract to a local directory (e.g., `C:\opencv3\`)
3. Open Visual Studio 2015, create a new C++ project
4. Configure include/library paths to the extracted directory
5. Build and run

## Topics & Capabilities

This repository supports a wide range of computer vision tasks:

| Domain | Techniques |
|--------|-----------|
| **Image Processing** | Filtering, thresholding, morphological operations, color space conversion |
| **Feature Detection** | SIFT, SURF, ORB, FAST, corner detection |
| **Object Detection** | Haar cascades, HOG descriptors, DNN module |
| **Face Recognition** | Face detection, landmark detection, recognition pipelines |
| **Video Analysis** | Optical flow, motion tracking, background subtraction |
| **Camera Calibration** | Intrinsic/extrinsic calibration, stereo vision, rectification |
| **Augmented Reality** | Pose estimation, marker tracking, overlay rendering |
| **Machine Learning** | SVM, k-NN, decision trees, random forests, boosting |
| **Deep Learning** | Caffe, TensorFlow model loading via DNN module |
| **3D Vision** | Stereo matching, depth maps, point cloud processing |

## Deep Learning Integration (2025-2026 State of the Art)

OpenCV 3's DNN module supports inference with pre-trained models. For modern deployments:

- **ONNX Runtime** — Preferred backend for cross-platform DNN inference ([onnxruntime.ai](https://onnxruntime.ai))
- **OpenCV 4.10+ DNN** — Improved ONNX, TensorFlow Lite, and CUDA DNN backends
- **NVIDIA TensorRT** — 2-5x inference speedup on NVIDIA GPUs for production edge AI
- **OpenVINO** — Intel-optimized inference for Intel CPUs, iGPUs, and VPUs
- **NVIDIA Jetson** — Edge deployment with TensorRT + OpenCV CUDA module
- **Quantization (QDQ INT8)** — Post-training quantization for 4x model compression with <1% accuracy loss

## Modern Alternatives (2025-2026)

For new projects, consider upgrading to:

| Tool | Use Case |
|------|----------|
| [OpenCV 4.10+](https://github.com/opencv/opencv) | Latest stable with improved DNN, G-API, CUDA |
| [OpenCV 5.x](https://github.com/pirahansiah/opencv5vs2022) | Next-gen with improved performance and API |
| [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) | Real-time object detection (YOLOv8/v11) |
| [MediaPipe](https://github.com/google/mediapipe) | Cross-platform ML solutions for vision |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) | High-performance DNN inference |

## Resources

- [OpenCV Official Documentation](https://docs.opencv.org/3.x/)
- [OpenCV Tutorials](https://docs.opencv.org/3.x/d6/d00/tutorial_py_root.html)
- [OpenCV GitHub](https://github.com/opencv/opencv)
- [YouTube Channel](https://www.youtube.com/tiziran)
- [Dr. Farshid Pirahansiah — LinkedIn](https://linkedin.com/in/pirahansiah)

## License

See repository for license details.
