# 👋 Hi, I'm Armin
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

### 🔹 PCC-FECalc: Free Energy Calculator for PCCs
End-to-end Python framework for automating binding free energy calculations of protein-catalyzed capture agents. Integrates structure building, parametrization, PBMetaD simulations (GROMACS), and post-processing to deliver ΔG and Kd with uncertainty estimates.

### 🔹 EF-TSS (Eigenvector Following Transition State Search)
A Python implementation of the eigenvector-following transition state search (EF-TSS) algorithm, leveraging the PRFO method and Bofill's Hessian estimation via Gaussian. Users input a settings JSON and initial coordinates, and the tool iteratively converges on a transition state by calling Gaussian for energy and Hessian evaluations, with built-in pytest coverage.  

### 🔹 Bayesian Optimization for Screening
Applied Bayesian optimization to accelerate **protein-ligand screening**, integrating molecular dynamics with ML-based surrogate models.

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
