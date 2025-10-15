# Entanglement Workshop  
*A hands-on Qiskit notebook series for quantum computing instruction*

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)  
[![Qiskit](https://img.shields.io/badge/Qiskit-2.x-blue)](https://qiskit.org/)  
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

---

## 🎯 Project Overview

This repository contains a curated set of **four Jupyter notebooks** developed for a quantum computing workshop held at **CESUPA (Faculdade CESUPA)**. The goal is to introduce students to quantum programming, linear algebra of quantum states, and quantum teleportation using *Qiskit*. All examples are designed to be clear, modular, and instructive.

This workshop was conducted at CESUPA (Faculdade CESUPA) by [Carlos Esteves](https://github.com/10CarlosEsteves) and [Lucca Nobre](https://github.com/Lucca0404)  in may 2025 for undergraduate students interested in quantum computing. The series is intended as a didactic introduction, balancing theoretical foundations with hands-on simulation.

---

## 📂 Notebook Contents & Structure

Below is an organized summary of each notebook and its educational purpose:

| Notebook | Title | Focus / Highlights |
|---|---|---|
| **Code 001 – Statevectors and Operators** | Statevectors and Operators | Introduces matrix algebra, statevectors, and how quantum gates act on states. |
| **Code 002 – Noise Free Simulation** | Noise Free Simulation | Builds and simulates quantum circuits using noise-free backends (e.g. Qiskit’s Aer simulator). |
| **Code 003 – Noisy Simulation** | Noisy Simulation | Introduces noise models, simulates errors, and observes their impact on results. |
| **Code 004 – Quantum Teleportation** | Quantum Teleportation | Step-by-step implementation of the quantum teleportation protocol (ideal/noiseless version). |

These are arranged in increasing complexity, culminating in the teleportation example.

---

## 🧠 Key Concepts Covered

- **Quantum state representation** (statevectors, basis states)  
- **Quantum gates and operations** via matrix algebra  
- Execution of **ideal (noise-free)** quantum circuits  
- Introduction to **noise modeling** and how errors propagate  
- Implementation of **entanglement** and **quantum teleportation** protocols  

---

## 🛠️ Prerequisites & Setup

### Requirements

- Python 3.12 or above
- Qiskit 2.x
- Jupyter Notebook or JupyterLab  

### Installation & Running

```bash
# Clone the repository
git clone https://github.com/10CarlosEsteves/Entanglement-Workshop.git
cd Entanglement-Workshop

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
