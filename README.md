# Repository Update in Progress

## Overview

This repository is currently undergoing a restructuring phase to improve the organization and quality of its projects. I am actively working on various offensive security and research-driven initiatives, which will be shared soon.

## Current Focus

- **Project Refactoring**: Consolidating private codebases for improved modularity and maintainability.
- **Security Research**: Ongoing vulnerability research and exploit development, focusing on Windows internals, Active Directory, and privilege escalation techniques.
- **Tool Development**: Creating custom tools and scripts for red teaming, malware development, and bypassing modern EDR/AV solutions.
- **Collaboration & Open Source**: Actively contributing to the offensive security community through shared research and participation in open-source projects.

## Upcoming Releases

Look forward to future releases on:

### Windows Post-Exploitation & Privilege Escalation

Refining known attack paths and discovering subtle misconfigurations in Windows environments:

- **LSASS credential dumping** via advanced **handle duplication** techniques to evade EDR detection.
- **Privilege escalation** through **Windows service misconfigurations**, weak service permissions, and **DLL hijacking** to achieve persistence.

### EDR Evasion Techniques

Strategies for bypassing modern EDR/AV solutions while maintaining stealth:

- Using **LOLBins (Living Off The Land Binaries)** to execute payloads without triggering EDR/AV alerts.
- **Unhooking EDR hooks** from key Windows functions to neutralize detection mechanisms.
- **Bypassing AMSI** (Antimalware Scan Interface) using memory patching and obfuscation for undetected PowerShell or C# payload execution.

### Reflection Loading & In-Memory Execution

Enhancing in-memory execution techniques to avoid detection:

- **Reflective DLL injection** for executing payloads entirely in memory, avoiding disk-based detection.
- **Reflection-based PowerShell execution** to bypass logging and AMSI by running code directly in memory.
- Research on **in-memory code execution** techniques to evade static and signature-based detection.

### Cloud & Container Security

As cloud adoption increases, securing cloud and containerized applications is paramount. This section will focus on:

- **Cloud misconfiguration tooling** for AWS, Azure, and GCP, targeting **IAM role abuse**, **S3 bucket vulnerabilities**, and **overly permissive configurations** leading to privilege escalation.
- Tools to identify and exploit vulnerabilities in **Docker** and **Kubernetes** environments.

## Stay Updated

For collaboration or to stay informed about upcoming releases, feel free to reach out or follow this repository for updates. New public content and contributions will be made available soon.

Thank you for your patience.

**Luca Demers | LLB, MD | CRTO, OSCP, OSEP**

lucademers [at] protonmail [dot] com
