<div align="center">

  <a name="readme-top"></a>
  # Android Studio Calculator

  [![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)
  ![Status](https://img.shields.io/badge/Status-Completed-success)
  [![Technology](https://img.shields.io/badge/Technology-Java%20%7C%20Android-orange)](https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR)
  [![Developed by Amey Thakur and Mega Satish](https://img.shields.io/badge/Developed%20by-Amey%20Thakur%20%26%20Mega%20Satish-blue.svg)](https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR)

  A simple and efficient Calculator application built for Android using Java, featuring basic arithmetic operations and a clean user interface.

  **[Source Code](Source%20Code/)** &nbsp;·&nbsp; **[Download APK](https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR/blob/main/Calculator.apk?raw=true)** &nbsp;·&nbsp; **[Video Demo](https://youtu.be/g0uc8xAfdFk)**

  <br>

  <a href="https://youtu.be/g0uc8xAfdFk">
    <img src="https://img.youtube.com/vi/g0uc8xAfdFk/maxresdefault.jpg" alt="Video Demo" width="70%">
  </a>

</div>

---

<div align="center">

  [Authors](#authors) &nbsp;·&nbsp; [Overview](#overview) &nbsp;·&nbsp; [Structure](#project-structure) &nbsp;·&nbsp; [Quick Start](#quick-start) &nbsp;·&nbsp; [License](#license) &nbsp;·&nbsp; [About](#about-this-repository)

</div>

---

<!-- AUTHORS -->
<div align="center">

  <a name="authors"></a>
  ## Authors

| <a href="https://github.com/Amey-Thakur"><img src="https://github.com/Amey-Thakur.png" width="150" height="150" alt="Amey Thakur"></a><br>[**Amey Thakur**](https://github.com/Amey-Thakur)<br><br>[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5644--1575-green.svg)](https://orcid.org/0000-0001-5644-1575) | <a href="https://github.com/msatmod"><img src="Mega/Mega.png" width="150" height="150" alt="Mega Satish"></a><br>[**Mega Satish**](https://github.com/msatmod)<br><br>[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1844--9557-green.svg)](https://orcid.org/0000-0002-1844-9557) |
| :---: | :---: |

</div>

> [!IMPORTANT]
> ### 🤝🏻 Special Acknowledgement
> *Special thanks to **[Mega Satish](https://github.com/msatmod)** for her meaningful contributions, guidance, and support that helped shape this work.*

---

<!-- OVERVIEW -->
<a name="overview"></a>
## Overview

**Android Studio Calculator** is a precision-engineered mobile utility developed using **Java** and **Android Studio**, focusing on logical state management and UI symmetry. By leveraging the **Android Activity Lifecycle**, this project offers a stable, responsive, and mathematically accurate platform for basic arithmetic, bridging the gap between functional utility and scholarly software documentation.

### core mechanics
The application is governed by strict **computational design patterns** ensuring fidelity and responsiveness:
*   **Logical Precedence**: The engine utilizes a synchronous arithmetic pipeline, ensuring that every input event is processed in real-time with zero-latency state transitions.
*   **UI Symmetry**: Unlike generic utilities, the interface integrates a **ConstraintLayout-based geometry** that dynamically adapts to diverse mobile screen ratios, preserving visual balance.
*   **State Persistence**: Input handling is synchronized with the Android lifecycle, ensuring that the calculation corridor remains stable during orientation changes or system interruptions.

> [!TIP]
> **Sensory Feedback Integration**
>
> To maximize input clarity, the application employs a **Tactile Feedback System**. **Haptic triggers** synchronize with touch events, and **dynamic text scaling** visualizes the expression's complexity, strictly coupling user intent with system response. This ensures the user's mental model is constantly synchronized with the underlying arithmetic simulation without reliance on intrusive HUD elements.

---

<!-- STRUCTURE -->
<a name="project-structure"></a>
## Project Structure

```python
ANDROID-STUDIO-CALCULATOR/
│
├── docs/                            # Technical Documentation
│   └── SPECIFICATION.md             # Architecture & Design Specification
│
├── Mega/                            # Attribution Assets
│   ├── Filly.jpg                    # Companion (Filly)
│   └── Mega.png                     # Profile Image (Mega Satish)
│
├── Source Code/                     # Primary Application Layer
│   └── Calculator/                  # Android Studio Project Root
│       ├── app/                     # Main Application Module
│       ├── gradle/                  # Build Configuration
│       └── build.gradle             # Build Logic
│
├── Calculator.apk                   # Pre-compiled Executable
├── SECURITY.md                      # Security Protocols
├── CITATION.cff                     # Academic Citation Manifest
├── codemeta.json                    # Metadata Standard
├── LICENSE                          # MIT License (Verbatim)
└── README.md                        # Project Entrance
```

---

<!-- QUICK START -->
<a name="quick-start"></a>
## Quick Start

### 1. Prerequisites
- **Android Studio**: Required for building and development. [Download Android Studio](https://developer.android.com/studio)
- **Git**: For version control and cloning. [Download Git](https://git-scm.com/downloads)

> [!WARNING]
> **APK Execution Security**
>
> When installing the pre-compiled `Calculator.apk` on a physical Android device, you may encounter a **"Blocked by Play Protect"** or **"Unknown Apps"** warning. This is expected for scholarship-based, self-signed APKs. To proceed with the installation, select "Install anyway" or enable "Allow from this source" in your device's security settings.

### 2. Installation & Setup

#### Step 1: Clone the Repository
Open your terminal and clone the repository:
```bash
git clone https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR.git
cd ANDROID-STUDIO-CALCULATOR
```

#### Step 2: Open in Android Studio
1. Launch **Android Studio**.
2. Select **Open** and navigate to the `Source Code/Calculator` directory.
3. Wait for the **Gradle synchronization** to complete.

### 3. Build & Execution

#### Step 1: Generate Debug APK
Navigate to the build menu to generate a fresh executable:
1. Click on **Build** -> **Build Bundle(s)/APK(s)** -> **Build APK**.
2. Monitor the **Event Log** for completion.

#### Step 2: Locate Artifact
1. Click on **Locate** in the event log notification.
2. The generated `app-debug.apk` will be available in the `app/build/outputs/apk/debug/` directory.

> [!NOTE]
> ### 📥 Direct Download
> For immediate use without building from source, you can **[Download the pre-compiled Calculator.apk](https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR/blob/main/Calculator.apk?raw=true)** directly from the repository root.

---

<!-- USAGE GUIDELINES -->
<a name="usage-guidelines"></a>
## Usage Guidelines

This repository is openly shared to support learning and knowledge exchange across the academic community.

**For Students**  
Use this project as reference material for understanding **Android Activity Lifecycle**, **Java-based arithmetic logic**, and **responsive UI design with ConstraintLayout**. The source code is available for study to facilitate self-paced learning and exploration of **mobile application architecture**.

**For Educators**  
This project may serve as a practical lab example or supplementary teaching resource for **Mobile Application Development**, **Java Programming**, and **User Interface Design** courses. Attribution is appreciated when utilizing content.

**For Researchers**  
The documentation and architectural approach may provide insights into **academic project structuring**, **scholarly software documentation**, and **mobile state management heuristics**.

---

<!-- LICENSE -->
<a name="license"></a>
## License

This repository and all its creative and technical assets are made available under the **MIT License**. See the [LICENSE](LICENSE) file for complete terms.

Copyright © 2022 Amey Thakur & Mega Satish

---

<!-- ABOUT -->
<a name="about-this-repository"></a>
## About This Repository

**Created & Maintained by**: [Amey Thakur](https://github.com/Amey-Thakur) & [Mega Satish](https://github.com/msatmod)

<div align="center">

  🧠 **[Android Studio Calculator](https://github.com/Amey-Thakur/ANDROID-STUDIO-CALCULATOR)**

  ---

  ### 🎓 [Computer Engineering Repository](https://github.com/Amey-Thakur/COMPUTER-ENGINEERING)

  **Computer Engineering (B.E.) - University of Mumbai**

  *Semester-wise curriculum, laboratories, projects, and academic notes.*

</div>
