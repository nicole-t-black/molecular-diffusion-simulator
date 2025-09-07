# Random Walk and Diffusion Simulations  

This project explores particle motion through random walks and molecular diffusion in cells. Key highlights:

- **2D Random Walks**:  
  - Simulate and visualize individual paths.  
  - Analyze end-to-end distances over many walks—distribution is right-skewed, reflecting limited extreme displacements.  

- **Return-to-Origin Probabilities**:  
  - Compute likelihood of walkers returning to their starting point for various walk lengths.  
  - Compare 2D vs 3D lattices—3D walks have lower return probabilities, highlighting benefits of 2D confinement for cellular signaling.  

- **Diffusion Coefficient Estimation**:  
  - Use particle trajectories to estimate diffusion constants for GFP molecules.  
  - Demonstrate limitations of conventional microscopy due to long exposure times.  
  - Shorter exposures improve accuracy, yielding estimates consistent with literature (~28 µm²/s).  

- **Experimental Considerations**:  
  - Obstacles in cells or molecular interactions can bias diffusion estimates, often underestimating true movement.  

- **Technical Details**:  
  - Fully vectorized simulations for efficiency.  
  - Python 3 with numpy, matplotlib, seaborn.  

This repository allows you to explore how random walks and diffusion behave in different dimensions and under varying experimental conditions.
