# GALATEA1 - HMI Object Library

## Project State: Extraction / Modularization Phase
GALATEA1 is a permissive, programmable SVG object library built to enforce strict High-Performance Human-Machine Interface (HPHMI) design paradigms across industrial and emergency control environments. Originally extracted from the primary core of the **ECHO1** pipeline simulator dashboard, this library isolates visual assets from application logic to ensure cross-platform rendering consistency.

### Current Maturity & Structural Baseline
* **Active Asset:** The repository currently consists of `galatea-core.js`. 
* **Deployment Note:** Because this component is tightly coupled with edge gateway visualization, users deploying the **IYNX1** Incident Command Center may already have this core factory file mirrored within their local `iynx` client setups. This repository serves as the definitive, standalone open-source home for the library as it decouples from legacy frameworks.

---

## The Strategic Benefits of Object Libraries:

Decoupling visual objects into a dedicated factory library facilitates three critical engineering advantages for modern industrial control systems: HMI Standardization, Operator Situation Awareness and Accelerated Usability Testing

---
