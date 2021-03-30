# Onnx_Runtime_Mobile_ODSC_Tutorial

## Overview
Tutorial for ODSC East 2021, "ML Inference on Mobile Device With Onnx Runtime"

- [Slides for this tutorial](files/ODSC_ML_inference_on_Mobile_with_ONNX_Runtime.pdf)

This demo Android image classification app is loosely based on [Google CodeLabs - Getting Started with CameraX](https://codelabs.developers.google.com/codelabs/camerax-getting-started), with all the UI components, image analysis class, pre/post processing functionalities ready to use.

In this workshop, we will integrate [Onnx Runtime Mobile](https://github.com/microsoft/onnxruntime) and [MobileNet V2](https://pytorch.org/hub/pytorch_vision_mobilenet_v2/) into this demo app to perform image classification.

## Prerequisites

- [Android Studio 4.1+](https://developer.android.com/studio)

- A modern Android device with a camera

- The prebuilt onnxruntime arm64 AAR package, model and label files [available here](https://1drv.ms/u/s!Auaxv_56eyubgQX-S_kTP0AP66Km?e=e8YMX1)

- [optional] If you prefer to build your custom Onnx Runtime Mobile Package

    - [Onnx Runtime](https://github.com/microsoft/onnxruntime) and its prerequisites

## Getting Started
1. Clone this repository
2. Open using Android Studio
3. Click Build -> Make Project
4. Run the App on your Android device
5. Let's start adding image classification capability to this app using Onnx Runtime Mobile
