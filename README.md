# Boundary Behaviour of Eigenfunctions and Superharmonic Functions on Harmonic Manifolds

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Research](https://img.shields.io/badge/Research-Paper%20Implementation-lightgrey.svg)

Welcome to the implementation of the research paper **"Boundary behaviour of eigenfunctions and superharmonic functions on harmonic manifolds of purely exponential volume growth"** by **Utsav Dewan**. This repository provides a Python implementation of the key concepts and results discussed in the paper, along with tools to explore the boundary behavior of eigenfunctions and superharmonic functions on harmonic manifolds.

---

## 📄 Paper Overview

The paper investigates the boundary behavior of eigenfunctions and superharmonic functions on non-positively curved harmonic manifolds of purely exponential volume growth. Key contributions include:

1. **Eigenfunctions**:
   - Analysis of complex-valued eigenfunctions lying outside the \(L^2\)-spectrum of the Laplace-Beltrami operator (\(\Delta\)).
   - Establishing almost everywhere existence of weighted non-tangential limits.
   - Sharp estimates for the Hausdorff dimension and measure of boundary exceptional sets for radial limits.

2. **Superharmonic Functions**:
   - Study of non-tangential and tangential boundary behavior of positive superharmonic functions.
   - Application of potential theory in the context of Gromov hyperbolic geometry.

The results are significant even in specific cases such as rank-one Riemannian symmetric spaces of non-compact type and Damek-Ricci spaces.

---

## 🚀 How It Works

This repository provides a Python implementation of the core mathematical concepts and algorithms presented in the paper. Here's an overview of the implementation:

### 1. **Harmonic Manifolds and Exponential Volume Growth**
   - The implementation models harmonic manifolds with purely exponential volume growth. These manifolds are characterized by their unique geometric and analytic properties.

### 2. **Eigenfunctions Analysis**
   - Computes eigenfunctions of the Laplace-Beltrami operator (\(\Delta\)) on harmonic manifolds.
   - Evaluates the boundary behavior of eigenfunctions, including:
     - Weighted non-tangential limits.
     - Radial limits and their exceptional sets.

### 3. **Superharmonic Functions**
   - Implements algorithms to study the boundary behavior of positive superharmonic functions.
   - Differentiates between non-tangential and tangential limits.

### 4. **Gromov Hyperbolic Geometry**
   - Adapts potential theory to the intrinsic Gromov hyperbolic geometry of the harmonic manifold.

### 5. **Visualization**
   - Includes utilities to visualize eigenfunctions, boundary behaviors, and exceptional sets.

---

## 🛠️ Installation

To use this implementation, ensure you have Python 3.8 or higher installed. Then, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/harmonic-manifold-boundary-behavior.git
cd harmonic-manifold-boundary-behavior
pip install -r requirements.txt
```

---

## 📚 Usage Instructions

The main implementation is in the `implementation.py` script. Below are the steps to use the script:

### 1. **Run the Script**
   To execute the script and analyze the boundary behavior, run:
   ```bash
   python implementation.py
   ```

### 2. **Input Parameters**
   The script allows you to specify the following parameters:
   - `manifold_dimension`: Dimension of the harmonic manifold (\(n \geq 3\)).
   - `eigenvalue`: Eigenvalue for the Laplace-Beltrami operator (\(\Delta\)).
   - `visualize`: Set to `True` to enable visualization of eigenfunctions and boundary behavior.

   Example:
   ```bash
   python implementation.py --manifold_dimension 3 --eigenvalue 2.5 --visualize True
   ```

### 3. **Output**
   - The script outputs the following:
     - Weighted non-tangential limits of eigenfunctions.
     - Hausdorff dimension and measure estimates for boundary exceptional sets.
     - Analysis of tangential and non-tangential limits for superharmonic functions.
   - If visualization is enabled, plots will be generated to illustrate the results.

---

## 📊 Example

Here’s an example of how to compute and visualize the boundary behavior of eigenfunctions:

```python
from implementation import analyze_eigenfunctions, visualize_results

# Define manifold parameters
manifold_dimension = 4
eigenvalue = 3.0

# Perform analysis
results = analyze_eigenfunctions(manifold_dimension, eigenvalue)

# Visualize results
visualize_results(results)
```

The output will include numerical results and visualizations of the eigenfunctions and their boundary behavior.

---

## 📦 Project Structure

```
harmonic-manifold-boundary-behavior/
│
├── implementation.py       # Main implementation of the paper
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
├── examples/               # Example scripts and notebooks
└── data/                   # Sample data for testing
```

---

## 🧪 Dependencies

This project uses the following Python libraries:

- `numpy`: For numerical computations.
- `scipy`: For scientific computing.
- `matplotlib`: For visualizations.
- `sympy`: For symbolic mathematics.
- `networkx`: For modeling Gromov hyperbolic geometry.

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

This implementation is based on the research paper [Boundary behaviour of eigenfunctions and superharmonic functions on harmonic manifolds of purely exponential volume growth](https://arxiv.org/pdf/2607.09636v1) by **Utsav Dewan**. Special thanks to the author for their groundbreaking contributions to the field of harmonic analysis and geometry.

For any questions or feedback, feel free to open an issue or reach out to the repository maintainer.

---

Happy coding! 😊