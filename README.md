# 📚 Lab FAQ & Knowledge Base

Welcome to the central technical troubleshooting and documentation hub for our research laboratory.

> **⚠️ Security Warning:** This repository and its associated Wiki are **publicly accessible**. Never publish credentials, passwords, API tokens, internal IP addresses, or unreleased research data/manuscript drafts here.

---

## 🎯 Purpose of This Hub
This repository serves as the single source of truth for lab-wide technical documentation. Its primary function is hosting the **Wiki**, where students and researchers can find:
- Standardized software installation and environment setup guides.
- Laboratory hardware interfacing and sensor communication guidelines (e.g., IMU streaming, motor controllers like ODrive).
- A catalog of recurring technical bugs and their validated solutions.

---

## 🔍 How to Find Solutions
All documentation, setup manuals, and debugging logs are organized inside the Wiki:

[![Lab Wiki](https://img.shields.io/badge/Documentation-Lab%20Wiki-0969da?style=for-the-badge&logo=github)](https://github.com/Neurorobotics-Intelligent-Assistance/FAQ/wiki)

👉 **[Apri la Wiki del Laboratorio](https://github.com/NOME-ORGANIZZAZIONE/FAQ/wiki)**

- **Browse Categories:** Use the sidebar on the right to navigate by topic (e.g., *IMU Sensor Troubleshooting*, *Motor Control & Drivers*, *Environment Setup*).
- **Search Keywords:** Use the Wiki search bar to look up specific error codes, terminal outputs, or hardware names.

---

## 💡 How to Contribute a New Solution (Via Issues)
Direct editing of the Wiki is reserved for Lab Administrators to keep documentation organized and protected. If you solve a hardware or software problem (for instance, fixing a missing IMU data stream or debugging a motor blockage), follow these steps to add it to the Wiki:

1. Navigate to the **[Issues](../../issues)** tab in this repository.
2. Click **New Issue**.
3. Use the following structure to describe the problem and your solution:
   - **Title:** `[Request] Add troubleshooting page/section for`
   - **Problem Description:** Describe the symptom (e.g., *"The IMU stops streaming data after 5 minutes"* or *"The brushless motor locks up under heavy load"*).
   - **Symptoms / Error Log:** Exact terminal output, error code, or screenshots (you can simply paste screenshots with `Ctrl+V` or drag and drop logs/images directly into the issue box).
   - **Proposed Solution / Steps to Fix:** Detail the exact fix, commands, or configuration changes you tested and verified.
4. Submit the issue. A lab administrator will review your contribution, format it, and publish it as an official page or section in the Lab Wiki.
