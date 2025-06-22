# 2D Unsteady Heat Diffusion (PINNs + FDM)

## 📝 Overview
This project explores the 2D unsteady heat diffusion equation in aluminum using:
- **Physics-Informed Neural Networks (PINNs)** (two different versions)
- **Finite Difference Method (FDM)** for comparison

We implement deep learning models that respect the heat equation as a constraint, then compare their accuracy and performance to a classical numerical solver.

## 🧑‍💻 What’s Included
- `square.ipynb` — First version of the PINN model
- `Final_void.ipynb` — Improved version of the PINN model
- `data/` — Input files (e.g. `.xlsx`)
- `figures/` — Plots and screenshots of results
- `requirements.txt` — Python dependencies

## ⚙️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Adi-0202/PINN-Heat-Diffusion.git
   cd PINN-Heat-Diffusion
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the scripts:
   ```bash
   Final_void.ipynb
   square.ipynb
4. Results:
   Visualizations and screenshots of results can be found in the figures/ directory.
   Examples:
      PINNs solutions vs. FDM baseline
      Error and convergence plots
5. Acknowledgement:
   Thanks to Professor Dr.Kritesh Gupta for guidance and support.
6.Keywords:
  Physics-Informed Neural Networks, Heat Diffusion, Finite Difference Method, Deep Learning, Numerical Methods


   
