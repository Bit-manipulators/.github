<div align="center">

# ⚡ Bit Manipulators

### *Bending Bits • Unleashing Mobile Hardware • Engineering Zero-Trust Systems*

[![GitHub Organization](https://img.shields.io/badge/GitHub-Bit--manipulators-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bit-manipulators)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-Android%20%7C%20Linux%20%7C%20AI-00ACC1?style=for-the-badge)](https://github.com/Bit-manipulators)
[![License: Open Source](https://img.shields.io/badge/Licenses-GPLv3%20%26%20MIT-blue?style=for-the-badge)](https://github.com/Bit-manipulators)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](https://github.com/Bit-manipulators/.github/blob/main/CONTRIBUTING.md)

<br/>

<p align="center">
  <b>Bit Manipulators</b> is an open-source engineering collective dedicated to pushing modern hardware to its limits. We bridge mobile computing with desktop workstations, craft zero-trust developer sandboxes with on-the-go AI diagnostics, and build deterministic, privacy-first Android systems.
</p>

[🌐 Projects](#-featured-projects) •
[🏛️ Core Pillars](#️-engineering-pillars) •
[🛠️ Tech Stack](#️-technology-matrix) •
[👥 Maintainers](#-maintainers--core-team) •
[🤝 Contributing](#-get-involved)

---

</div>

## 🏛️ Engineering Pillars

<table>
  <tr>
    <td width="50%">
      <h3>🖥️ Mobile-to-Desktop Convergence</h3>
      Transforming everyday Android smartphones and tablets into high-performance, multi-window desktop workstations under Linux (Wayland & X11) with ultra-low latency and hardware-accelerated video decoding.
    </td>
    <td width="50%">
      <h3>🛡️ Zero-Trust Developer Tooling</h3>
      Empowering engineers with intelligent on-the-go code analysis, instant OCR code capture from camera/screen, and isolated ephemeral Docker sandboxes running with strict resource caps and zero network exposure.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⚡ Privacy & Deterministic Diagnostics</h3>
      Engineering system telemetry and device vitality managers where <b>100% of data stays on-device</b>. Transparent mathematical scoring formulas replace deceptive cleaner gimmicks and covert telemetry harvesting.
    </td>
    <td width="50%">
      <h3>🔓 Clean-Room Open Source</h3>
      All projects are built from first principles using clean-room engineering, transparent licensing (GPL-3.0 & MIT), standard protocols (ADB, Scrcpy, Wayland, X11), and zero proprietary lock-in.
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 1. 🖥️ [Open Android DeX](https://github.com/Bit-manipulators/open-android-dex)
> **Turn your Android device into a true multi-window Linux workstation.**

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg?style=flat-square)](https://github.com/Bit-manipulators/open-android-dex/blob/main/LICENSE)
[![Platform: Linux](https://img.shields.io/badge/Platform-Linux%20(X11%20%7C%20Wayland)-teal.svg?style=flat-square)](https://github.com/Bit-manipulators/open-android-dex)
[![Android: API 29-36](https://img.shields.io/badge/Android-API%2029--36-green.svg?style=flat-square)](https://github.com/Bit-manipulators/open-android-dex)
[![Compositor: Flutter & GTK4](https://img.shields.io/badge/Shell-Flutter%20%7C%20GTK4-blueviolet.svg?style=flat-square)](https://github.com/Bit-manipulators/open-android-dex)

* **Key Capabilities**: 8-way window resizing, dynamic Z-index layering, taskbar with 9-dot app launcher, low-latency in-process 60 FPS FFmpeg video texture decoding, and seamless keyboard/mouse input passthrough.
* **Architecture**: Dual compositor design featuring a high-performance **Flutter Desktop Compositor** and an ultra-lightweight **Python / GTK4 fallback shell**.
* **Companion Portal**: [open-android-dex-website](https://github.com/Bit-manipulators/open-android-dex-website) — Documentation and web portal *(In Development)*.

---

### 2. 🔍 [DevLens](https://github.com/Bit-manipulators/DevLense)
> **The Intelligent On-the-Go Code Debugger & Zero-Trust Sandbox.**

[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688.svg?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/Bit-manipulators/DevLense)
[![React Native](https://img.shields.io/badge/React_Native-Expo_51%2F54-61DAFB.svg?style=flat-square&logo=react&logoColor=black)](https://github.com/Bit-manipulators/DevLense)
[![Docker Sandbox](https://img.shields.io/badge/Docker-Zero--Trust_Sandbox-2496ED.svg?style=flat-square&logo=docker&logoColor=white)](https://github.com/Bit-manipulators/DevLense)
[![Python: 3.12+](https://img.shields.io/badge/Python-3.12%2B-3776AB.svg?style=flat-square&logo=python&logoColor=white)](https://github.com/Bit-manipulators/DevLense)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://github.com/Bit-manipulators/DevLense/blob/main/LICENSE)

* **Key Capabilities**: Camera and gallery OCR for instant code digitization, multi-language static heuristic diagnostics (Python, JS, C++, Java), and safe ephemeral code execution.
* **Security**: Zero-trust Docker container sandbox with read-only root filesystems, memory bounds (256MB), network isolation (`--net=none`), and dropped kernel capabilities.
* **AI Copilot**: Local LLM and heuristic fallbacks for algorithmic explanations, automated test generation, and one-tap diff repairs.

---

### 3. ⚡ [AppPulse](https://github.com/Bit-manipulators/App_pulse)
> **Intelligent, Privacy-First On-Device Android Health & Resource Impact Manager.**

[![Kotlin: 2.0](https://img.shields.io/badge/Kotlin-2.0.21-7F52FF.svg?style=flat-square&logo=kotlin&logoColor=white)](https://github.com/Bit-manipulators/App_pulse)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-Material_3-4285F4.svg?style=flat-square&logo=android&logoColor=white)](https://github.com/Bit-manipulators/App_pulse)
[![Target SDK: Android 15](https://img.shields.io/badge/Target_SDK-Android_15_(API_35)-34A853.svg?style=flat-square&logo=android&logoColor=white)](https://github.com/Bit-manipulators/App_pulse)
[![Privacy: 100% On-Device](https://img.shields.io/badge/Privacy-100%25_On--Device-00ACC1.svg?style=flat-square)](https://github.com/Bit-manipulators/App_pulse)
[![License: MIT](https://img.shields.io/badge/License-MIT-F4B400.svg?style=flat-square)](https://github.com/Bit-manipulators/App_pulse/blob/main/LICENSE)

* **Key Capabilities**: Real-time hardware telemetry (RAM, storage, CPU vitality), granular permission auditing (Camera, Location, Microphone, Contacts), and stealth / stalkerware app detection.
* **Privacy by Design**: Zero network egress. Telemetry and package heuristics stay encrypted on-device in SQLite/Room databases.
* **Deterministic Metrics**: Mathematical scoring without deceptive cleaner tactics or destructive task killing.

---

## 🛠️ Technology Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Mobile & Desktop UI** | Flutter Desktop (Linux), Jetpack Compose (Material 3), React Native, Expo |
| **Languages** | Dart, Kotlin, Python 3.12+, TypeScript, C++, Modern C, Shell / Bash |
| **Systems & Compositing** | Linux Wayland & X11, Android IPC, ADB Protocols, Scrcpy Streaming, FFmpeg Video Pipelines |
| **Backend & Sandboxing** | FastAPI, Docker Containers (Zero-Trust Ephemeral Sandboxes), Uvicorn, SQLite / Room |
| **Tooling & CI/CD** | GitHub Actions, Dev Containers, Vitest, Turbo, Detekt, Pytest, CMake |

---

## 👥 Maintainers & Core Team

<div align="center">

| Name | GitHub Profile |
| :--- | :--- |
| **Aditya R. Satapathy** | [@Myparadox-creator](https://github.com/Myparadox-creator) |
| **Anurag Patel** | [@anurag200513](https://github.com/anurag200513) |
| **Amit Padhan** | [@amitpadhan525](https://github.com/amitpadhan525) |

</div>

---

## 🤝 Get Involved

We welcome developers, reverse engineers, systems architects, and designers to collaborate with us!

* **Bug Reports & Feature Requests**: Check our [Contributing Guide](https://github.com/Bit-manipulators/.github/blob/main/CONTRIBUTING.md) and open an issue in the respective repository.
* **Security & Vulnerabilities**: Review our [Security Policy](https://github.com/Bit-manipulators/.github/blob/main/SECURITY.md) for responsible disclosure.
* **Community Conduct**: We uphold a respectful, inclusive environment following our [Code of Conduct](https://github.com/Bit-manipulators/.github/blob/main/CODE_OF_CONDUCT.md).

<div align="center">
  <sub>Built with ❤️ by the <b>Bit Manipulators</b> Open Source Collective</sub>
</div>
