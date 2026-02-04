# Quantum Foundations & Verification Study

> **A self-study repository documenting the transition from Classical CS Theory to Quantum Computing.**

## 📌 Overview
I am a Computer Science graduate (UBC) specializing in **Theory**, **Algorithms**, and **Optimization**. This repository serves as a "living document" of my preparation for graduate research in **Quantum Software and Verification** at National Taiwan University (NTU).

My goal is to bridge the domain gap between my background in formal methods and the physical principles of quantum mechanics. This project focuses on:
1.  **Mathematical Foundations:** Linear algebra, tensor products, and unitary evolution.
2.  **Implementation:** Building quantum protocols from scratch using **Python (NumPy)** and **Qiskit**.
3.  **Literature Review:** Analyzing state-of-the-art quantum compilers, specifically **VOQC (Verified Optimizer for Quantum Circuits)**.

## 📚 Study Roadmap & Progress
*Current Focus: Nielsen & Chuang, Chapter 2 & Qiskit Fundamentals*

### 1. Mathematical Foundations (Nielsen & Chuang)
- [ ] **Linear Algebra Review:** Vector spaces, inner products, and Hilbert spaces.
- [ ] **The 4 Postulates:** Understanding State Space, Evolution, Measurement, and Composite Systems.
- [ ] **Tensor Products:** Manual calculation of multiqubit states (e.g., $H \otimes I$).
- [ ] **Density Operators:** Understanding mixed states and noise.

### 2. Quantum Algorithms (Qiskit & Python)
- [ ] **"Hello Quantum":** Implementing a single-qubit superposition.
- [ ] **Bell States:** Creating and verifying entanglement ($|\Phi^+\rangle$).
- [ ] **Teleportation Protocol:** Implementing the circuit and verifying state transfer.
- [ ] **Superdense Coding:** Transmitting classical bits via entangled pairs.

### 3. Literature Review (Verification & Optimization)
- [ ] **Paper Analysis:** *VOQC: A Verified Optimizer for Quantum Circuits* (Hietala et al., 2021).
    - [ ] Understanding circuit equivalence rules.
    - [ ] Analyzing optimization passes (gate commutation, cancellation).
    - [ ] [My Notes & Questions](./literature_review/voqc_notes.md)

## 📂 Repository Structure

```text
.
├── 01_linear_algebra/     # NumPy implementations of QM math (No Qiskit)
│   ├── tensor_product.py  # Manual implementation of tensor products
│   └── unitary_check.py   # Verifying if a matrix is unitary
├── 02_qiskit_protocols/   # Circuit implementations using IBM Qiskit
│   ├── teleportation.ipynb
│   └── bell_state.py
├── 03_literature_review/  # Notes and summaries of research papers
│   └── voqc_summary.md    # Deep dive into Prof. Hung's VOQC paper
└── README.md
