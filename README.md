# APK Insight

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

> A browser-based OSINT tool for static analysis of Android applications, identifying permissions, trackers, and other embedded SDKs.

**Live Demo:** [**https://0xspect3r.github.io/apk-insight/**](https://0xspect3r.github.io/apk-insight/)

---

## Overview

APK Insight is a web-based utility for cybersecurity researchers, privacy advocates, and developers to perform a quick, static analysis of Android application packages (`.apk` or `.xapk`). 

The tool provides a high-level overview of an application's potential behavior by performing a simulated scan for key components. This helps in understanding data collection points, required device permissions, and external dependencies without needing to decompile or execute the code.

## Features

- **Multiple Input Methods:** Analyze by file upload or by pasting a Google Play Store / direct download link.
- **Comprehensive Permission Analysis:** Identifies permissions requested by the app and highlights those considered "dangerous" by Android.
- **Extensive SDK Detection:** Scans for a wide range of embedded third-party libraries, including:
  - Ad Networks
  - Analytics & Trackers
  - Social & Authentication SDKs
  - Crash Reporting Services
- **AI-Powered Reports:** Utilizes an LLM to generate a concise summary of potential privacy and security implications based on the detected components.
- **Client-Side & Secure:** All analysis is performed within your browser. Your files are never uploaded to a server.
- **User-Friendly Interface:** A clean, responsive UI designed for quick and easy analysis.

## Usage

1.  **Open the Live Demo:** Navigate to [https://0xspect3r.github.io/apk-insight/](https://0xspect3r.github.io/apk-insight/).
2.  **Provide the App:**
    - **Option A (File):** Drag and drop an `.apk` or `.xapk` file onto the designated area, or click to select a file from your computer.
    - **Option B (URL):** Paste a link to a Google Play Store page or a direct link to an application file into the URL input field and click "Analyze".
3.  **Review the Report:** The tool will perform a scan and display a list of detected components.
4.  **Generate AI Summary:** If any components are found, click the "Generate AI Summary" button to get a detailed report on the potential privacy and security posture.

## Disclaimer

This tool is intended for **educational and research purposes only**. The analysis is a simulation based on known package name prefixes and manifest entries and does not represent a full, deep-code analysis. It does **not** decompile, modify, or reverse-engineer the provided files. The developer assumes no liability for any misuse of this tool.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

&copy; 2025 [Specter](https://github.com/0xSpect3r/)
