# 🛡️ CISA & FEMA Critical Infrastructure Simulation Portal

Welcome to the **National Infrastructure Coordinating Center (NICC) Training Portal Sandbox**. This repository hosts a lightweight, interactive web terminal designed specifically for **Career and Technical Education (CTE) Justice, Law and Security students** to learn risk engineering and disaster preparedness.

This project completely removes the need for local code execution, allowing students to securely map out real-world infrastructure vulnerabilities and run mathematical risk calculations on any school-issued device.

---

## 🗺️ 4-Week Curriculum Quick Reference
Each instructional day runs for a **100-minute block** divided into: **Learn It** (Theory), **Lab It** (Simulator Interactive Practice), and **Document It** (Portfolio Writing).

*   **Week 1: Cyber-Physical Architecture** | Mapping the 16 CISA sectors, analyzing IT vs. OT networks, and exploring SCADA vulnerabilities.
*   **Week 2: FEMA National Priorities** | Applying the 5 Core Mission Areas and creating a Threat Hazard Identification Assessment (THIRA).
*   **Week 3: Local Infrastructure & Risk Math** | Interviewing the local **Director of Public Works** and calculating risk via the formula: `Risk = Threat × Vulnerability × Consequence`.
*   **Week 4: Executive Mitigation & Pitch** | Designing technical/physical security controls and pitching a completed security brief to a mock "City Council."

---

## 🖥️ Student Sandbox Command Guide

Students can interact with this simulator by typing commands into the terminal console or by using the quick-access action panel underneath the display box.

### 📋 Phase 1: Sector & Framework Discovery
*   `sectors` - Prints the official government registry of the 16 critical infrastructure sectors.
*   `fema-codes` - Pulls up the FEMA National Preparedness Framework's Core Mission Areas (Prevention, Protection, Mitigation, Response, Recovery).

### 💧 Phase 2: Technical Asset Blueprints
Generates an industrial asset profile exposing unique **Technical, Physical, and Human vulnerabilities** for portfolio analysis:
*   `blueprint water` - Municipal Water Treatment Facility (District 4)
*   `blueprint power` - Regional Electrical Substation (Grid East)
*   `blueprint transit` - Metro Light Rail Transit Control Center

### 🌪️ Phase 3: THIRA Hazard Assessment
Generates historical probability frequencies (scored 1-5) for context-based threat modeling:
*   `thira-hazard natural` - Category 3 Hurricane / Regional Flash Flooding
*   `thira-hazard tech` - Catastrophic Grid Transformer / SCADA Logic Crash
*   `thira-hazard adversarial` - State-Sponsored Ransomware Deployment on Plant OT

### 🧮 Phase 4: Risk Engineering Calculator
*   `matrix-tool` - Launches an interactive pop-up prompt wizard. Multiplies user inputs to calculate a final **Risk Priority Number (RPN)** out of 125 and delivers a color-coded enterprise security tier warning (LOW, MEDIUM, or CRITICAL).
*   `clear` - Purges the terminal history log and resets the console workspace.

---

## 🎓 Instructor & Setup Notes
*   **Zero-Dependency Deployment:** This simulator uses pure static HTML/JavaScript. It requires no APIs, no databases, and has zero server operating costs.
*   **School Filter Friendly:** Being entirely client-side, this page bypasses floating AI message limits and loads reliably past strict school district network firewalls.
*   **The Two-Window Method:** Instruct students to tile their screens side-by-side, placing this live link on the left half of the display and their Master Portfolio Document (Google Doc / Word) on the right half to avoid losing focus.

---
*Developed for Career and Technical Education (CTE) Pathways. Aligned with CompTIA Security+ and CISA Cross-Sector Cybersecurity Performance Goals.*
