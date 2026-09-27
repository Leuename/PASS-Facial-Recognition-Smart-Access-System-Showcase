# PASS — Facial Recognition Smart Access System

> **Portfolio Showcase**  
> This repository documents the project's capabilities and architecture. Source code, biometric templates, face databases, attendance databases, trained models, and deployment configuration are intentionally not published.

## Overview

PASS is a **facial-recognition smart access and attendance system** designed to combine identity recognition, anti-spoofing, access decisions, and attendance recording in a single application.

The project explores how computer vision can be used as an interface between physical access control and digital attendance records while adding liveness-oriented defenses against simple presentation attacks.

## Core Capabilities

- Facial recognition for identity verification
- Anti-spoofing / liveness-oriented image classification
- Access-control decision workflow
- Attendance recording
- User-facing management interface
- Local biometric-processing pipeline
- Integration between computer vision and access-management logic

## High-Level Architecture

```text
Camera Input
     ↓
Face Detection
     ↓
Anti-Spoofing Check
     ↓
Face Recognition
     ↓
Identity / Access Decision
     ↓
Access Event
     ↓
Attendance Record
     ↓
Management Interface
```

## Anti-Spoofing

The system includes an anti-spoofing component based on a **MobileNetV2-oriented classification workflow**. Its purpose is to add another verification layer before a recognized face is accepted by the access-control pipeline.

This helps distinguish the engineering problem from simple face matching: an access system must also consider whether the camera is observing a live subject rather than merely receiving a recognizable facial image.

## Engineering Focus

The project combines:

- Computer vision
- Facial recognition
- Anti-spoofing
- Local data persistence
- Attendance tracking
- Backend application logic
- Web-based user interface
- Physical-access workflow design

## Privacy and Security

Biometric systems handle sensitive information. For that reason, this public showcase deliberately excludes:

- Face embeddings and biometric templates
- Face-image datasets
- Attendance databases
- User records
- Trained/model artifacts where disclosure is unnecessary
- Production configuration
- Implementation source code

No operational biometric database is included in this showcase.

## Repository Notice

This repository exists solely as a **technical portfolio showcase**. The full implementation is maintained separately and is not publicly distributed.
