# PhD Dissertation LaTeX Source

This repository contains the LaTeX source files for my PhD dissertation titled **"PhD Dissertation: Hybrid Machine Learning and Numerical Analysis of Cartilage Biomechanics"**.

## Abstract
Articular cartilage (AC), a crucial soft tissue for pain-free movement, undergoes significant biomechanical stress, warranting research through non-invasive computer simulations. Such simulations commonly use time-intensive numerical methods, such as finite element (FE) analysis. Artificial intelligence (AI), with machine learning (ML) as a surrogate model, presents a faster alternative, imitating numerical analysis with numerical data samples. Despite its potential, this method often requires extensive training and large datasets, which is inefficient. This study first introduces an efficient biomechanical model incorporating multi-physics modeling and a novel pre-stressing algorithm (PSA), generating few training samples across different fidelities and scales. We then propose efficient, multi-fidelity, generalizable surrogate models, enhanced by innovative preprocessing and training algorithms. Finally, the research code, including our developed Fortran subroutines and Python scripts, is open-sourced. Empirical results emphasize the significance of pre-stressing in multiphasic modeling and the value of efficient surrogate modeling in reducing computational time. The scalability and generalizability of the hybrid ML (HML) framework are confirmed through multiscale simulations, demonstrating the impact of our physics-constrained data augmentation (DA) and graph neural network (GNN) implementation. Therefore, while this study potentially advances the field with the developed PSA implementation, it also presents a straightforward approach to address computational challenges and data scarcity in ML-based

## Requirements
To compile this dissertation, you need:

- A LaTeX distribution (e.g., [Overleaf](https://www.overleaf.com/))
- A PDF viewer for output

Enjoy!
