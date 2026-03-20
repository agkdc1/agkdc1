# 🩺 Architecting the Next-Generation "Hospital OS"

**Practicing Orthopaedic Surgeon | Cloud Infrastructure Builder | AI System Architect**

Welcome. I am a practicing orthopaedic surgeon based in Tokyo, Japan, bridging the catastrophic gap between clinical realities and modern IT capabilities. 

The tech industry is pouring billions into "Diagnostic AI"—a sector stalling due to unshareable clinical liability. Meanwhile, hospitals are drowning in archaic operational friction (manual telephony, fragmented logistics, and redundant paperwork) that drives surgeons away from the operating room and pushes healthcare systems toward collapse. 

I do not build isolated diagnostic algorithms. **I build the cloud-native, "Zero-Trust" operational backbone required to return human cognitive capacity to the patient.**

Read my full thesis here: [🔗 Thus Spoke Zarathustra? The Myth of the AI Surgeon and the True Battlefield of Healthcare IT](https://www.linkedin.com/pulse/thus-spoke-zarathustra-myth-ai-surgeon-exodus-from-true-ahn-1pisc)

---

## 🏗️ Featured Architecture & Projects

### 1. [OsteoTwin](https://github.com/agkdc1/OsteoTwin) | *Zero-Trust Surgical Planning & FEA Pipeline*
The ultimate countermeasure to AI hallucination in critical medical decision-making. OsteoTwin is an advanced dual-tier LLM pipeline integrated with 3D simulation and DICOM processing.
* **Zero-Suggestion Architecture:** The AI is strictly hardcoded to act as a biomechanical discriminator. It audits human-generated 3D plans (e.g., complex composite fractures) for spatial conflicts and FEA (Finite Element Analysis) stress points against the THUMS model, but is prohibited from suggesting unverified solutions.
* **Tech Stack:** `Python`, `GCP Vertex AI (Deep Think/Batch Prediction)`, `SOFA Framework`, `3D Biomechanical Simulation`.

### 2. Abstracted Logistics (Private/WIP)
Replacing the manual and handwritten based logistics business operations with a fully automated, event-driven abstracted layer. 
* **Real-time Unified Logistics:** Custom plugin development for **InvenTree** to track physical inventory and supplies via QR codes, integrated with automated shipping label APIs (CUPS, Selenium).
* **Telephony & Network Overhaul:** Designing flawless, multi-site operational networks utilizing `Asterisk`, and `MikroTik ` / `Synology` ecosystems to eradicate communication latency in critical care environments.
* **Tech Stack:** `GCP Cloud Run`, `Pub/Sub`, `Docker`, `Asterisk/SIP`, `Python/Selenium`, `K8s`.

### 3. [ROBOT4KID](https://github.com/agkdc1/ROBOT4KID) | *LLM-based GAN for the Physical World*
An experimental architecture testing the boundaries of LLMs in physical mechanics.
* **Concept:** Utilizing LLMs not just as text generators, but as physical world "discriminators" to orchestrate 3D printing and hardware inverse kinematics (e.g., Webots simulations).
* **Tech Stack:** `C++`, `Python`, `Webots`, `OpenSCAD`.

---

## ⚙️ Technical Arsenal

* **Cloud & Serverless:** GCP (Cloud Run, Vertex AI, Pub/Sub, IAM/IAP Zero-Trust Security)
* **Languages & Frameworks:** Python, C++, Flutter
* **Infrastructure & Networking:** Docker, MikroTik RouterOS, Proxmox, Kubernetes, Ceph
* **Medical & Physics:** DICOM processing, FEA (Finite Element Analysis), Anatomy, Orthopedic surgery

---
*“Technology should not replace the physician's judgment; it should eradicate the operational friction that prevents it.”*
