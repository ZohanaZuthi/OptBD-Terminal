# OmniTerm (Codename)
A specialized, hardware-accelerated Linux terminal emulator designed for native Complex Text Layout (CTL) support, NLP dataset visualization, and integrated cybersecurity operations.

## 🚀 The Vision
Traditional terminal emulators prioritize raw speed over specialized developer workflows. OmniTerm bridges the gap by introducing native support for Indic scripts (Bangla), built-in NLP tokenization debugging, and native cybersecurity traffic/log interception—all wrapped in a custom OpenGL/HarfBuzz rendering pipeline.

## ✨ Core Novelties
*   **Native Bangla (CTL) Engine:** Bypasses standard grid-based character limits using HarfBuzz, ensuring perfect rendering of Bangla conjuncts (যুক্তবর্ণ) for localized development and data pipelines.
*   **Token-Aware NLP Visualizer:** Integrates a Byte-Pair Encoding (BPE) tokenizer to visually highlight exact token boundaries and chunks directly in the standard output.
*   **Integrated SecOps & CLEF Parsing:** Natively intercepts and parses cybersecurity tool outputs (using standards like Common Log Event Format - CLEF) to provide visual vulnerability highlighting and automated threat dashboards without relying on external UI wrappers.

## 🛠️ Tech Stack
*   **Systems Programming:** C++ (or Rust)
*   **PTY & State Management:** POSIX APIs (`openpty`), `libtsm` (Terminal State Machine)
*   **Text Shaping:** HarfBuzz, FreeType
*   **Graphics & Windowing:** OpenGL, GLFW (or SDL2)
*   **Security Integration:** `libpcap` (for network intercepts), CLEF/CEF parsing logic

## 📦 Installation & Build
*(Instructions to be added as the build system (CMake/Make) is configured during Phase 1)*

## 🤝 Contributing
This project is currently in the architectural planning phase. See `roadmap.md` for the step-by-step development breakdown.