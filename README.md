# SITA Fingerprint Capture APK

## Overview

This repository contains an Android application developed as part of the **SITA Contactless Fingerprint Challenge**.
The application enables contactless capture of finger images using a smartphone camera and applies on-device image enhancement techniques to improve fingerprint visibility and quality under varying capture conditions.

---

## Application Name

**Fingersnap – Contactless Finger Image Capture**

---

## Key Features

* Contactless finger image acquisition using a mobile device camera
* Automatic detection and isolation of the finger region
* Image enhancement to improve ridge–valley visibility
* Contrast normalization and noise reduction
* Operates on standard Android smartphones
* Fully offline processing with no network dependency

---

## APK Details

* **APK File**: `Fingersnap.apk`
* **Version**: 1.0
* **Build Type**: Release
* **Minimum Android Version**: Android 8.0 (API 26)
* **Target Android Version**: Android 13 and above

---

## Installation Instructions

1. Download the APK from this repository
2. Enable **installation from unknown sources** on the Android device
3. Install the APK
4. Grant camera permission when prompted
5. Launch the application to begin finger image capture

---

## Technical Description

* **Camera Interface**: Android native Camera APIs
* **Image Processing Framework**: OpenCV for Android
* **Enhancement Pipeline** includes:

  * Finger region segmentation
  * Orientation-aware ridge enhancement
  * Adaptive contrast improvement
  * Noise handling for low-light and non-uniform illumination
* **Execution**: All processing is performed locally on the device

---

## Standards and Data Handling

* Developed with reference to **ISO/IEC 19794-4** fingerprint image standards
* No biometric data is transmitted or shared externally
* Captured images are retained locally on the device for evaluation and demonstration

---

## Repository Contents

* `Fingersnap.apk` – Installable Android application
* `README.md` – Project documentation

---

## Usage Guidelines

1. Open the application
2. Position the finger within the on-screen guide
3. Ensure stable lighting and minimal movement
4. Capture the image when prompted
5. View the enhanced output immediately after capture

---

## Disclaimer

This application has been developed **solely for research, evaluation, and demonstration purposes** as part of the SITA challenge. It is not intended for commercial or production deployment.


