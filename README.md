# Hi, I'm Mitchell Daneker

I'm a PhD candidate in Chemical Engineering at the University of Pennsylvania, specializing in machine learning for scientific computing, simulation, and biological systems. My work spans **physics-informed neural networks (PINNs)**, **Deep Operator Networks (DeepONets)**, **protein engineering**, **computational biology**, and **LLM training**, with a focus on deploying ML models in real-world, high-impact domains.

This GitHub contains select code, publications, and ongoing projects in:
- **ML-guided protein design**
- **Surrogate modeling for PDEs/ODEs**
- **Uncertainty quantification (UQ)**
- **Generative AI and LLM training**
- **Real-time ML deployment in simulation frameworks**

Due to the proprietary nature of some projects, not all work is publicly available. However, I’ve included links to published papers and open-source contributions where possible.

Feel free to reach out at **mitchelldaneker@gmail.com** for collaboration or questions.


## Papers

1. **[Engaging Alkenes and Alkynes in Deaminative Alkyl–Alkyl and Alkyl–Vinyl Cross-Couplings of Alkylpyridinium Salts](https://pubs.acs.org/doi/abs/10.1021/acs.orglett.9b03899)**  
   My first paper during undergrad at the University of Delaware with Dr. Mary P. Watson. I contributed to developing new cross-coupling reactions.

2. **[Systems Biology: Identifiability Analysis and Parameter Identification via Systems-Biology-Informed Neural Networks](https://link.springer.com/protocol/10.1007/978-1-0716-3008-2_4)**  
   Explores how physics-informed neural networks (PINNs) can solve inverse problems for biological ODEs. The paper also addresses structural and practical identifiability of parameters.  
   [GitHub Code](https://github.com/lu-group/sbinn)

3. **[Effective Data Sampling Strategies and Boundary Condition Constraints of Physics-Informed Neural Networks for Identifying Material Properties in Solid Mechanics](https://link.springer.com/article/10.1007/s10483-023-2995-8)**  
   Investigates how various data sampling techniques can enhance PINN performance in inverse problems related to solid mechanics.  
   [GitHub Code](https://github.com/lu-group/pinn-material-identification)

4. **[Transfer Learning on Physics-Informed Neural Networks for Tracking Hemodynamics in the Evolving False Lumen of Dissected Aorta](https://www.cell.com/nexus/fulltext/S2950-1601(24)00014-7)**  
   Uses PINN and MRI data to resolve the hemodynamic domain in aneurysms and introduces a transfer learning technique that reduces runtime across varied boundaries and resolutions.  
   [GitHub Code](https://github.com/lu-group/pinn-thrombus-mri)

5. **[Identifying Heterogeneous Micromechanical Properties of Biological Tissues via Physics-Informed Neural Networks](https://pmc.ncbi.nlm.nih.gov/articles/PMC11092874/)**  
   Solves inverse problems to learn parameter fields in realistic 2D tissues using PINN, outperforming other machine learning techniques.  
   [GitHub Code](https://github.com/lu-group/pinn-heterogeneous-material)

6. **[A noninvasive method for determining elastic parameters of valve tissue using physics-informed neural networks](https://www.sciencedirect.com/science/article/pii/S1742706125003472?via%3Dihub)**  
   Introduces ADEPT, a method using 3D transesophageal (TEE) imaging to predict patient-specific material properties of the tricuspid valve for better surgical modeling.  
   [GitHub Code (Under Revision)](https://github.com/lu-group/adept)

7. **[Physics-Informed and Black-Box Identification of Robotic Actuator with a Flexible Joint](https://www.sciencedirect.com/science/article/pii/S2405896324013181)**  
   Applies PINN to infer friction models in robotic actuators, comparing results to traditional black-box approaches.

## Current Projects

1. **DeepONet Integration at FM**  
  Developed and deployed a custom Deep Operator Network (DeepONet) framework into FireFOAM’s radiation solver, achieving over **44x speedup** in CFD inference. This work demonstrates real-time ML deployment in high-fidelity simulation environments and serves as a benchmark for surrogate modeling in industrial fire safety applications.

2. **SBINN Continuation:**  
   Collaborating with researchers at Johns Hopkins to solve inverse problems for large scale cell models, focusing on methods for low-data scenarios.

3. **DeepONet Uncertainty Quantification (UQ):**  
   Developing UQ methods for Deep Operator Networks, enhancing their potential for active learning in biological systems.

4. **DeepONet Surrogate Models:**  
   Creating surrogate models for spatiotemporal biological systems, simplifying complex models to temporal-only formats with UQ integration.

5. **Genetically Encoded Voltage Indicators (GEVIs):**  
   Applying machine learning to optimize GEVIs for brain studies through active learning techniques, aiming to improve experimental conditions.
---

## Retired Project

1. **LLM Training**  
  Contributed to supervised fine-tuning and RLHF workflows for large language models through freelance opportunities. Evaluated model outputs for alignment, safety, and performance across diverse domains, supporting the development of robust generative AI systems.
1. **Reinforcement Learning Betting Model**  
  Built a reinforcement learning model using login site data and web scraping to simulate betting decisions: selecting when to bet, what to bet on, and how much. The model achieved an ROI of 0.98, serving as a learning tool for reinforcement learning fundamentals and decision-making under uncertainty.




Thanks for visiting!
