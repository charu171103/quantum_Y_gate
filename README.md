# Quantum Y Gate Demonstration

This repository showcases how the **quantum Pauli-Y gate** acts on six essential quantum states:
**|0⟩**, **|1⟩**, **|+⟩**, **|−⟩**, **|i⟩**, and **|−i⟩**.

The Y gate is a fundamental single-qubit quantum gate defined as:

$$
Y = \begin{bmatrix}
0 & -i \\
i & 0
\end{bmatrix}
$$

It performs a **π rotation around the Y-axis** of the Bloch sphere and introduces complex phase changes in qubit states.

---

## 💡 Input States and Their Representations

| State | Vector Form                                             |
| ----- | ------------------------------------------------------- |
| \|0⟩  | $\begin{bmatrix}1 \\ 0\end{bmatrix}$                    |
| \|1⟩  | $\begin{bmatrix}0 \\ 1\end{bmatrix}$                    |
| \|+⟩  | $\frac{1}{\sqrt{2}}\begin{bmatrix}1 \\ 1\end{bmatrix}$  |
| \|−⟩  | $\frac{1}{\sqrt{2}}\begin{bmatrix}1 \\ -1\end{bmatrix}$ |
| \|i⟩  | $\frac{1}{\sqrt{2}}\begin{bmatrix}1 \\ i\end{bmatrix}$  |
| \|−i⟩ | $\frac{1}{\sqrt{2}}\begin{bmatrix}1 \\ -i\end{bmatrix}$ |

---

## ⚙️ What Happens When Y Gate is Applied?

The Y gate applies a **90° rotation with phase**. This repository computes:

* **Matrix multiplication** of each input state with the Y matrix.
* **Resulting state vectors** after applying Y.
* **Bloch sphere visualization** (optional future addition).
* **Interpretations** of the transformations.

Example transformation:

```
Y |0⟩ = i|1⟩
Y |+⟩ = i|−⟩
Y |i⟩ = |−i⟩
```

---

## 📂 Contents

* `y_gate_demo.ipynb` – Jupyter notebook with:

  * Definitions of Y gate and input states
  * Matrix operations for each case
  * Explanations and output interpretations

---

## 📘 Prerequisites

* Python 3.x
* NumPy
* Jupyter Notebook

You can install dependencies using:

```bash
pip install numpy notebook
```

---

## 🚀 Run the Notebook

```bash
jupyter notebook Ygate.ipynb
```

---

## 📌 Summary

This notebook helps understand how the **Pauli-Y gate** modifies various quantum states through phase shifts and amplitude changes. It is a beginner-friendly demonstration of **quantum gate operations** using Python and linear algebra.

