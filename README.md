# Unified Quantum–Classical Learning Framework for Cyber Threat Detection

## Abstract
This repository presents a **unified quantum–classical learning framework** for cyber threat detection designed under **near-term quantum (NISQ) constraints**. The framework integrates a **Quantum Support Vector Machine (QSVM)** and a **Variational Quantum Classifier (VQC)** into a single hybrid architecture, optimized using an **Improved Grey Wolf Optimizer (IGWO)** for feature selection and qubit efficiency.  
The proposed approach addresses key limitations of standalone quantum models—such as instability, excessive circuit depth, and noise sensitivity—by combining complementary quantum decision mechanisms within a classical fusion layer.

---

## Research Motivation
Quantum machine learning has shown strong theoretical potential, yet practical adoption remains constrained by:
- Limited qubit availability
- Circuit depth–induced noise and barren plateaus
- Poor cross-domain generalization

Most existing studies evaluate **isolated quantum models on single datasets**, limiting their applicability to real-world cybersecurity systems. This work focuses on **cross-domain cyber threat detection** using a **single unified quantum framework** capable of maintaining stability across heterogeneous attack scenarios.

---

## Methodology

### Feature Optimization Under Qubit Constraints
An **Improved Grey Wolf Optimizer (IGWO)** is employed to select a compact yet discriminative feature subset, explicitly constrained to an **8-qubit encoding limit**. This ensures:
- Reduced quantum circuit depth
- Improved robustness against noise
- Preservation of critical attack semantics

### Dual Quantum Learning Architecture
The optimized feature space is processed in parallel by two quantum models:

- **Quantum Support Vector Machine (QSVM)**  
  Provides margin-based classification stability and consistent generalization across structured attack patterns.

- **Variational Quantum Classifier (VQC)**  
  Utilizes parameterized quantum circuits to model nonlinear and adaptive threat behaviors.

### Classical Decision Fusion
A lightweight classical aggregation layer combines the outputs of QSVM and VQC, enabling:
- Reduction in false alarm rates
- Compensation for quantum model variance
- Improved decision confidence across datasets

---

## Experimental Scope
The framework is evaluated across **heterogeneous cybersecurity domains**, including:
- Network intrusion detection
- Distributed Denial-of-Service (DDoS) attacks
- Mobile malware classification

Evaluation metrics include **Accuracy, F1-Score, Detection Rate (Recall), Precision, and False Alarm Rate (FAR)** to ensure balanced performance analysis.

---

## Key Findings
- The unified framework consistently outperforms standalone QSVM and VQC models
- IGWO-based feature optimization significantly enhances quantum model stability
- Hybrid decision fusion reduces false positives without compromising detection accuracy
- The system demonstrates **cross-domain generalization**, critical for practical security deployment

---

## Research Significance
This work contributes:
- A **scalable design pattern** for hybrid quantum–classical cybersecurity systems
- Empirical evidence that **model fusion mitigates NISQ-era quantum instability**
- A practical pathway for applying quantum machine learning to real-world security problems

The framework aligns with ongoing research in:
- Quantum Machine Learning
- Trustworthy AI for Cybersecurity
- Hybrid Decision Systems under Hardware Constraints

---

## Author
**Samreen Fatima**  
Undergraduate Researcher – Quantum Machine Learning & Cybersecurity  
Keshav Memorial Institute of Technology, Hyderabad, India

---

## Supervisor
**Dr. Kishore Babu D**  
Keshav Memorial Institute of Technology
