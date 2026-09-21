# Welcome to Qiskit Fall Fest Repository! 

This is comprehensive archive of the Qiskit Fall Fest workshop curriculum. This repository serves as a centralized, maintained repository of notebooks spanning multiple iterations of the festival, optimized for pedagogical clarity and compatibility with contemporary quantum frameworks. Whether you are a quantum curious beginner or a seasoned quantum developer, this repository is your home base. In here, you will find resources to build real quantum applications using Qiskit.

This collection provides a structured progression through the evolution of Qiskit implementation paradigms over three consecutive years:

* **🍂 Qiskit Fall Fest '24** – Foundational quantum algorithms and baseline implementations align with modern execution standards.
* **🍁 Qiskit Fall Fest '25** – Intermediate computational methods and advanced workloads, updated to mitigate deprecation errors.
* **🔥 Qiskit Fall Fest '26** – **Current Iteration.** The latest research notebooks, workshop materials, and challenge sets from this academic year's event.

Researchers, students, and practitioners are invited to clone the repository, initialize their environments, and explore the computational notebooks. ⚛️

## 🗺️ Choose Your Quantum Adventure
We have structured our learning materials into three tailored tracks. Click a section below to jump straight to your skill level!

### 🟢 Track 1: Quantum Foundations (Beginner)
*For those completely new to quantum computing and Python.*

*   **Core Concepts:** Qubits, superposition, and entanglement.
*   **Qiskit Basics:** Creating quantum circuits, adding gates, and running simulations.
*   **Essential Reading & Tutorials:**
    *   [Introduction to Quantum Computing](https://qiskit.org) — The official interactive Qiskit textbook.
    *   [Hello Quantum World](./notebooks/1_hello_quantum.ipynb) — Your first 2-qubit circuit (Bell State).
    *   [Visualizing Qubits](https://qiskit.org) — Master the Bloch Sphere.

---

### 🔵 Track 2: Quantum Algorithms (Intermediate)
*For those who understand circuits and want to solve problems.*

*   **Core Concepts:** Phase kickback, quantum interference, and speedups.
*   **Algorithms Covered:** Deutsch-Jozsa, Grover’s Search, and Quantum Phase Estimation (QPE).
*   **Essential Reading & Tutorials:**
    *   [Understanding Quantum Gates](https://qiskit.orgcourse/ch-gates/introduction) — Deep dive into single and multi-qubit matrices.
    *   [Grover's Search Implementation](./notebooks/2_grovers_algorithm.ipynb) — Find the needle in the quantum haystack.
    *   [VQE & Optimization](https://qiskit.org) — Introduction to Variational Quantum Eigensolvers.

---

### 🟣 Track 3: Hardware & Error Mitigation (Advanced)
*For developers looking to run efficient circuits on real utility-scale hardware.*

*   **Core Concepts:** Dynamic circuits, layout mapping, routing, and error mitigation.
*   **Advanced Qiskit:** Working with Qiskit Runtime Primitives (Sampler and Estimator V2).
*   **Essential Reading & Tutorials:**
    *   [Transpilation & Layouts](https://ibm.com) — Learn how to optimize circuits for heavy-hex topologies.
    *   [Qiskit Runtime Primitives Guide](https://ibm.com) — Moving past basic local backend simulations.
    *   [Hardware-Efficient Layouts](./notebooks/3_hardware_transpilation.ipynb) — Minimize 2-qubit gate depth like a pro.


## 🏆 Daily Challenges & Hackathon Info

| Day | Challenge Link | Topic | Difficulty |
| :--- | :--- | :--- | :--- |
| **Day 1** | [Challenge 01](./challenges/day1.md) | Single Qubit Rotations | 🟢 Easy |
| **Day 2** | [Challenge 02](./challenges/day2.md) | Constructing GHZ States | 🟢 Easy |
| **Day 3** | [Challenge 03](./challenges/day3.md) | Implementing Quantum Teleportation | 🔵 Medium |
| **Day 4** | [Challenge 04](./challenges/day4.md) | Optimizing Qubit Layout Depth | 🟣 Hard |

---

## 💡 Quick Tips for Success
*   **Keep Circuit Depth Low:** When mapping to real backends, choose physical qubits that are close neighbors to prevent heavy Swap gate penalties!
*   **Utilize Parallelization:** Look for ways to execute 2-qubit gates simultaneously across your qubit chains.
*   **Ask for Help:** Join our event Discord channel `#fall-fest-help` to collaborate with mentors and peers.

✨ **Happy Coding, Future Quantum Engineers!** ✨

