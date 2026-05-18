# Clinical Systems Safety & Operational Data Analytics

Welcome to my clinical systems engineering and data portfolio. This repository serves as a practical demonstration of applying quantitative data analysis, systematic risk assessment, and continuous workflow optimization within high-stakes, safety-critical medical environments. 

As a former Board-Certified Resident Physician transitioning into Medical Robotics and Automation, my objective is to bridge the gap between clinical domain expertise and robust systems engineering.

---

## 🛠️ Core Methodologies Applied
* **Systems Safety & Risk Analysis:** Root-Cause Analysis (RCA), Morbidity & Mortality (M&M) framework, Failure Mode tracking.
* **Data & Analytics:** Quantitative trend analysis, multi-ward operational KPIs, statistical data aggregation.
* **Process Optimization:** Corrective and Preventive Actions (CAPA), inter-departmental workflow standardization, protocol deployment.

---

## 🔍 Section 1: Systems Safety & Root-Cause Analysis (RCA)

This folder contains two comprehensive, fully anonymized structural reviews of critical workflow anomalies. The focus is placed entirely on systemic and latent organizational failures rather than individual human error, serving as a clinical equivalent to **Fault-Tree Analysis (FTA)**.

### Case Study 1: Systemic Latency in Hemorrhagic Shock Diagnosis
* **Context:** A high-risk patient experiencing post-delivery hemorrhagic decompensatory shock.
* **Methodology:** Analysis of measurement errors (visual estimation vs. quantitative tracking) and fluid delivery speeds.
* **Outcome:** Recommended shifting from visual estimation to hardware-based collection metrics (e.g., metric drapes) and mandating dual-sited, large-bore IV access triggered by high-risk patient admission parameters.
* **[View Case Analysis](./01_Root_Cause_Analysis/RCA_01_Hemorrhagic_Shock_Latency.md)**

### Case Study 2: Workflow Bottleneck Identification in Emergency Diagnostics
* **Context:** An acute abdominal emergency presenting with hypovolemic shock.
* **Methodology:** Chronological cycle-time tracking from patient admission to central laboratory verification and operating room (OR) deployment.
* **Outcome:** Identified critical data transit and processing latencies. Proposed localized "point-of-care" testing units to bypass centralized queuing bottlenecks and established multi-tier automated communication protocols triggered by physiological alert thresholds.
* **[View Case Analysis](./01_Root_Cause_Analysis/RCA_02_Emergency_Diagnostic_Bottlenecks.md)**

---

## 📊 Section 2: Multi-Ward Operational Data Analytics (1-Year Longitudinal Study)

This project tracks a full calendar year of operational, efficiency, and quality KPIs across three distinct clinical environments: **Obstetrics (OB), Gynaecology (Gyne), and the Neonatal Intensive Care Unit (NICU)**.

### Key Metrics Monitored & Modeled:
1. **Throughput & Capacity:** Monthly patient admission volumes, bed-occupancy cycles, and peak-load periods.
2. **Quality & Safety Indicators:** Adherence rates to standardized protocols, occurrence rates of expected complications, and systemic delays.
3. **Cross-Correlation:** Quantitative analysis mapping how peak-load occupancy in the primary ward downstream impacts admission velocities and baseline acuity levels in secondary wards.

### Engineering Applications:
* Demonstrates proficiency in handling multi-variable datasets.
* Experience modeling systemic dependencies (how a constraint in System A creates a compounding bottleneck in System B).
* Data-driven trend forecasting used to optimize resource allocation.

---

## 🔒 Compliance & Data Privacy (GDPR / Datenschutz)

**CRITICAL NOTE ON DATA PRIVACY:** To comply with strict European data privacy frameworks (GDPR) and medical confidentiality standards, all data and case details contained in this repository have been strictly filtered:
* All patient-identifiable parameters (names, specific dates, exact times, hospital numbers) have been permanently redacted or synthesized.
* Hospital identifiers and specific regional locations have been completely generalized.
* The focus of these files is strictly limited to **mathematical methodologies, systematic workflows, and engineering-process logic**.
