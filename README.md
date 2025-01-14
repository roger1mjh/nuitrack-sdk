<p align="center"><a href="https://nuitrack.com/"><img src="doc/img/nuitrack-logo.png" width="70%" /></a></p>

## What's New ?
- :soon: *Holistic skeletal tracking with multiple sensors*
- :soon: *Major update on tracking accuracy*
- :soon: *Native UE5 support* 
- :new: **TouchDesigner** :fireworks: package is in beta, please follow [this post](https://forum.derivative.ca/t/nuitrack-skeleton-tracking-plugin-for-touchdesigner/352108) to try it out !
- :white_check_mark: Jul'23 - 0.36.13 - **Orbbec Persee+ and Femto (W)** are finally supported !
---
- :white_check_mark: Oct'22 - 0.36.7 - :movie_camera: [**Multisensor tracking**](/doc/Multiple_Depth_Sensors.md)  
This opens up a huge opportunities like room-scale tracking with increased accuracy. Please stay tuned to get a firsthand experience of the coming **Nuitrack Holistic**.
- :white_check_mark: Sep'22 - 0.36.4 - :gear: [Failure cases recorder](/doc/Failure_Case_Recorder.md)
- :white_check_mark: Sep'22 - 0.36.2 - [Nuitrack Daemon [Beta]](/doc/Nuitrack_Daemon.md)  
- :white_check_mark: Aug'22 - 0.36.1 - :memo: [Person re-identification](/doc/Person_Reidentification.md)


## What is Nuitrack™ SDK?

<p align="center"><a href="https://nuitrack.com/"><img src="doc/img/nuitrack-teaser.gif" width="70%" /></a></p>

**Nuitrack™** is an ultimate 3D body tracking solution developed by **[3DiVi Inc](https://www.3divi.com/)**.

It enables body motion analytics applications for virtually any widespread:
- depth sensors - Orbbec Astra/Persee/Femto, Kinect v1/v2, [Kinect Azure](https://youtu.be/K7O-361UlfI), [Intel Realsense](https://youtu.be/gMPtV4NXtUo), Asus Xtion, LIPS, Structure Sensor, etc.
- hardware platforms - x64, x86, ARMv7, ARMv8
- OSes - Windows, Linux, Android, iOS
- and development environments - C++, C#, [Python](/PythonNuitrack-beta), [Unity](/Unity3D), Unreal

Inspired initially by Microsoft Kinect, **Nuitrack™**'s mission is to provide strong skeletal tracking baseline for the next generation of immersive and analytical applications beyond any specific platform or hardware. Think of it as a *"Kinect for anything"*.

With its performance and flexibility resulting from 10 years of development **Nuitrack™** is capable to support the wide range of applications:
- from a real-time gesture recognition on embedded platforms like [Raspberry Pi4](https://youtu.be/qyt4U7ZBj90)
- to a large-scale multisensor analytical systems

Now it's all yours - try it, use it, challenge it!

## Key Features
After being launched with [any supported depth sensor](https://nuitrack.com/#sensors) **Nuitrack** is able to :


Interpret a depth map as 3D Point Cloud | Perform scene analysis, detect key elements like floor plane | Detect/track persons in the scene and provide pixel-perfect masks for each of them |
:------------: |  :----------: | :-------------:  |
[![Depth Map](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/5aab9268-6170-4d1e-9c47-c4ed8b03e00a)](https://youtu.be/nX7kLXv65kU)  | [![Floor plane](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/37eac24c-0f88-45e0-b134-c1930a80fbd0)](https://youtu.be/5ehEcfCIBAU)  | [![Segmentation](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/4b944bf7-7df3-4110-a12f-0706b0f5ffcc)](/doc/Unity_Segment.md)  |


Perform a highly-sophisticated full body _Skeletal Tracking_ for each person | Perform a basic _Facial Analysis_ like age and emotion detection | Provide a _Hand Tracker_ and _Gesture Recognition_ higher-level APIs for the development of gesture-based user interfaces |
:------------: |  :----------: | :-------------:  |
[![Skeleton tracking](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/d9c92f22-638c-4b55-b0a9-6e787848add0)](https://youtu.be/-PSN1AWc5Ro) | [![Face Tracking](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/3cbbda69-d68c-4f49-b267-1c5e199975dd)](https://youtu.be/HOm0-7qL5hk) | [![Hand Tracking and Gesture Recognition](https://github.com/3DiVi/nuitrack-sdk/assets/50783230/8f2b289b-7d06-4718-a377-e40dd77db713)](/doc/Unity_Gallery.md) |

Nuitrack has two **Skeletal Tracking** engines:
   - "classical" - fast, stable and lightweight, highly-optimized for embedded hardware and limited CPU usage
   - [AI](https://youtu.be/S8dkf2MEZeM) - new deep-learning based engine, which provides greater coverage for complex poses


Essentially Nuitrack provides a **human-centric spatial understanding tool** for your applications to engage with a user in a natural and intelligent way.

## Application Areas
- Games and Training (Fitness, Dance Lessons)
- Medical Rehabilitation
- Smart Home
- Natural/Gesture-based User Interface (NUI)
- [Full Body Tracking for AR / VR](https://youtu.be/7JqtB6Dt_9c)
- Audience Analytics
- Robot Vision

## Try out Nuitrack with your sensor

It's as quick and simple as 1-2-3:
1. Download the **Nuitrack Runtime** package for your [Platform of choice](/Platforms)
2. Install it, in case of any issues please follow the [Installation Instructions](/doc/Install.md)
3. Just plug-in your sensor and launch Nuitrack executable from start menu
You will need [Trial or Commercial license](https://nuitrack.com/#pricing) that can be obtained from nuitrack.com

## Start development with Nuitrack

1. If you use Unity for development please download `Unity Package` and import it according to [this link](/Unity3D)

2. If you are C++/C#/Python developer - clone this repository to get a hands-on experience with a libraries and Nuitrack examples

If you have any questions, issues or feature ideas - feel free to engage with Nuitrack Team at our [Community Forum](https://community.nuitrack.com/).

## What’s included in the SDK:
| What | Description |
| --------- | ----------- | 
| **[Documentation](doc/readme.md)** | **Nuitrack** documentation ||
| **[Runtime Components](/Platforms)** | **Nuitrack Runtime** packages for all supported platforms ||
| **[C#/.NET and C++ API](https://download.3divi.com/Nuitrack/doc/annotated.html)** | It allows you to integrate **Nuitrack** with your **C#/C++** applications ||
| **[Python Wrapper [beta]](/PythonNuitrack-beta)** | **Nuitrack** supports **Python API** that allows you to integrate **Nuitrack** with your Python applications ||
| **[iOS [beta]](/iOS-beta)** | Get started developing for **iOS** with **Nuitrack** ||
| **[Code Samples](/Examples)** | These basic examples demonstrate how to use **Nuitrack SDK** |
| **[Unity Package](/doc/readme.md#unity-tutorials)** | This package allows you to easily integrate **Nuitrack SDK** into your Unity project |
| **[Unreal Engine Plugin](/doc/readme.md#unreal-engine-tutorials)** | This plugin allows you to develop applications with **UE 4.20** |

## Nuitrack in Academia 
Nuitrack is widely used in serious research, here are just a few selected references:
- [Detecting Short Distance Throwing Motions Using RGB-D Camera](https://www.jstage.jst.go.jp/article/pscjspe/2021A/0/2021A_45/_article/-char/ja/)
- [Planning Collision-Free Robot Motions in a Human–Robot Shared Workspace via Mixed Reality and Sensor-Fusion Skeleton Tracking](https://www.mdpi.com/2079-9292/11/15/2407)
- [Skeleton Driven Action Recognition Using an Image-Based Spatial-Temporal Representation and Convolution Neural Network](https://www.mdpi.com/1424-8220/21/13/4342)
- [Towards a Live Feedback Training System: Interchangeability of Orbbec Persee and Microsoft Kinect for Exercise Monitoring](https://www.mdpi.com/2411-9660/5/2/30)
- [ROBOGait: A Mobile Robotic Platform for Human Gait Analysis in Clinical Environments](https://www.mdpi.com/1424-8220/21/20/6786)
- [Robot-Assisted Gait Self-Training: Assessing the Level Achieved](https://www.mdpi.com/1424-8220/21/18/6213)
