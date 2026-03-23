# ⚛️ Quantum Computing — A Personal Study Repository

> A curated collection of notes, tutorials, and explorations on quantum computing — from foundational theory to advanced techniques.

---

## 📖 About This Repository

This repository documents a personal journey through quantum computing, spanning both the mathematical foundations and modern algorithmic techniques. It is organized as a self-contained reference: whether you are a student taking your first steps into quantum mechanics, or a researcher looking for concise notes on a specific topic, you should find something useful here.

The materials are a mix of **Jupyter notebooks**, **written tutorials**, and **handwritten theory notes** — reflecting the process of learning and thinking through these ideas.

---

## 🗺️ Repository Map

### 🌱 Introductory Tutorials
Start here if you are new to quantum computing. These tutorials cover the core concepts needed to understand the rest of the repository:

- Qubits, superposition, and entanglement
- Quantum gates and circuits
- Measurement and the Born rule
- Basic quantum algorithms (e.g. Deutsch–Jozsa, Bernstein–Vazirani)

> **Recommended for:** Beginners with a background in linear algebra and basic probability.

---

### 📐 ZX-Calculus
An introduction to the **ZX-calculus** — a graphical language for reasoning about quantum circuits and quantum processes. Topics include:

- Z-spiders and X-spiders
- Rewrite rules and diagrammatic proofs
- Applications to circuit optimization and verification

> ZX-calculus offers a powerful, intuition-friendly alternative to the standard circuit model for understanding how quantum information flows.

---

### 🔄 Cliffordization
Notes and explorations on **Clifford circuits** — the class of quantum circuits that can be efficiently simulated classically. Topics include:

- The Clifford group and Clifford gates (H, S, CNOT)
- The Gottesman–Knill theorem
- Stabilizer formalism and tableau representation
- Applications in quantum error correction

---

### ⏱️ Trotterization
A detailed look at **Trotterization** (Trotter–Suzuki decomposition) — a core technique for simulating quantum Hamiltonians on a quantum computer. Topics include:

- Product formulas and their error bounds
- First- and second-order Trotter decompositions
- Applications in quantum chemistry and quantum simulation
- Connections to variational algorithms (e.g. QAOA, VQE)

---

### 🛡️ Surface Codes
An introduction to **surface codes** — the leading candidate for fault-tolerant quantum computation. Topics include:

- The toric code and surface code geometry
- Logical qubits, stabilizers, and syndrome measurement
- Error correction and threshold theorems
- Lattice surgery and logical operations

---

### 📝 Handwritten Theory Notes
Short, dense handwritten notes covering foundational and advanced theory. These are intended as quick references and thinking aids, not polished expositions. Topics include quantum information theory, density matrices, channels, entanglement measures, and more.

---

## 🧭 Suggested Learning Path

If you are working through this repository from scratch, here is a recommended order:

```
Introductory Tutorials
        ↓
   ZX-Calculus
        ↓
  Cliffordization
        ↓
  Trotterization
        ↓
  Surface Codes
        ↓
Handwritten Theory Notes (as supplementary reference throughout)
```

Feel free to jump to any section directly if you already have the prerequisites.

---

## 🛠️ Prerequisites

Most of the material assumes familiarity with:

- **Linear algebra** (vector spaces, matrices, eigenvalues)
- **Basic probability** and complex numbers
- **Python** and **Jupyter notebooks** (for the computational parts)

Some sections (Trotterization, Surface Codes) additionally assume comfort with:

- Elementary quantum mechanics (Hilbert spaces, Hamiltonians)
- Basic group theory (for Clifford group material)

---

## 📚 References & Further Reading

Here are some resources that complement the material in this repository:

- *Quantum Computation and Quantum Information* — Nielsen & Chuang
- *An Introduction to Quantum Computing* — Kaye, Laflamme & Mosca
- [Quirk](https://algassert.com/quirk) — an interactive quantum circuit simulator
- [PennyLane](https://pennylane.ai/), [Qiskit](https://qiskit.org/) — quantum computing frameworks used in the notebooks
- *ZX-Calculus for the Working Quantum Computer Scientist* — van de Wetering (arXiv:2012.13966)

---

## 🤝 Contributing

This is a personal repository, but feedback, corrections, and suggestions are warmly welcome. If you spot an error or have a suggestion for improving the notes, feel free to open an issue.

---

## 📄 License

This repository is shared for educational purposes. Please credit appropriately if you reuse or adapt any of the materials.

---