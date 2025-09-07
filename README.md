# 👋 Hi, I'm Armin Shayesteh Zadeh

🎓 Postdoctoral Researcher @ University of Chicago (PME)  
⚛️ Computational Chemist • Machine Learning Researcher • HPC Enthusiast  

I build methods and tools at the intersection of **molecular modeling, machine learning, and high-performance computing**. My research focuses on enabling simulations of biomolecular systems at scale, designing enhanced sampling algorithms, and integrating ML potentials into molecular dynamics frameworks.  

---

## 🔬 Research & Technical Interests

- **Molecular Simulations**: OpenMM, GROMACS, ASE, CHARMM-GUI, QM/MM methods  
- **Enhanced Sampling & Rare Events**: Metadynamics, GADES (Generalized Adaptive Dynamics for Escape Sampling), free energy methods  
- **Machine Learning for Molecular Modeling**: Bayesian optimization, VAMPnets, GFlowNets, ML interatomic potentials (e.g., Meta’s UMA)  
- **Topological Data Analysis**: Vietoris–Rips complexes, persistent homology, Betti numbers for hydrogen-bond networks  
- **High-Performance Computing**: SLURM workflows, NSF ACCESS allocations (PI), Dockerized simulation environments  

---

## 🚀 Selected Projects

### 🔹 GADES: Rare Event Sampling
Adapted the **saddle-seeking principle of GAD** into a practical scheme for enhanced molecular dynamics. Instead of inverting unstable modes, GADES gently damps the softest Hessian direction, allowing trajectories to escape local minima without trapping at saddles.

### 🔹 EF-TSS (Eigenvector Following Transition State Search)
Developed a Python class implementing **transition state search** algorithms, with full `pytest` coverage:
- Gaussian job management  
- Gradient/Hessian analysis & eigenmode alignment  
- Numerical stability and regression testing  

### 🔹 CalcD5 Regression Suite
Built a comprehensive set of regression tests for the **CalcD5** class, ensuring reproducibility and stability of descriptor calculations.

### 🔹 FAIR Chemistry Collaboration
Benchmarked and validated **Meta’s UMA MLIP** for protein simulations, exploring how MLIPs compare with classical force fields.

### 🔹 Bayesian Optimization for Screening
Applied Bayesian optimization to accelerate **protein-ligand screening**, integrating molecular dynamics with ML-based surrogate models.

### 🔹 TDA for Molecular Networks
Used **persistent homology** to characterize hydrogen bond networks in water and biomolecular systems, employing Vietoris–Rips complexes and correlation-based feature bagging.

---

## 📦 Tools & Code Contributions

- ⚙️ **HPC Workflows**: Parallelized job submission, regression testing, Docker + GROMACS/PLUMED environments  
- 🧩 **ML + Physics Integration**: Differentiable PCA in PyTorch, jit-compilable tensor ops for periodic inputs  
- 📊 **Visualization**: Matplotlib/Plotly for free energy surfaces, VMD/NGLView for molecular interactions  

---

## 📫 Let’s Connect

- 🌐 [Google Scholar](#)  
- 💼 [LinkedIn](#)  
- 🐦 [Twitter](#) (optional if you want to include)  
- ✉️ armin@example.com  

---

⭐️ *Always excited to collaborate on projects that combine physics, chemistry, ML, and scalable computing.*
