# eCG VSCode Extension - Software Testing Documentation

Welcome to the central repository for all software testing documentation, test plans, and quality assurance artifacts for the **eCG (Electronic Cardiogram) VSCode Extension**. 

This repository serves as the single source of truth for our QA processes, ensuring that the extension safely, accurately, and reliably visualizes and analyzes eCG data within Visual Studio Code.

---

## 📂 Repository Structure

The documentation is organized by testing phase and type. Please maintain this structure when adding new documentation:

```text
├── .github/                 # CI/CD workflows for doc linting/hosting
├── test-strategy/           # High-level Test Strategy and Master Test Plan
├── test-suites/             # Detailed test cases and suites
│   ├── UI-UX/               # Extension views, webviews, and theme compatibility
│   ├── parsing-engine/      # eCG data parsing (HL7, DICOM, JSON, XML)
│   ├── performance/         # Rendering speeds, memory leaks, large file handling
│   └── security/            # Data privacy, local storage, HIPAA compliance
├── automation/              # Test scripts, fixtures, and E2E testing guides (Playwright/WDIO)
├── reports/                 # Historical test execution reports and sign-offs
└── resources/               # Sample eCG files (.dat, .xml, .edf) used for testing
