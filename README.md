# ICML2024_rebuttal
Supplementary file and data for ICML 2024 

Here we provide detailed pseudo-code.

## Inference
$N_{step}$ is the inference step, $N_{seq}$ is the M-H sampling step in sequence model, $L$ is the length of proteins, $\theta$ is the network parameters.

![avatar](https://github.com/2024-anonymous/ICML2024_rebuttal/blob/main/INFERENCE.png)

## Training 
$N_{seq}$ is the M-H sampling step in sequence model, $\mathbf{s}^{GT}$ is the natural protein sequence, $\mathbf{T}^{(0)}$ is the natural protein structure.

![avatar](https://github.com/2024-anonymous/ICML2024_rebuttal/blob/main/Training.png)
### ReverseDiffusion

![avatar](https://github.com/2024-anonymous/ICML2024_rebuttal/blob/main/ReverseDiffusion.png)
### DesignSequence

![avatar](https://github.com/2024-anonymous/ICML2024_rebuttal/blob/main/DesignSequence.png)
### MHSampler
$\psi_s$ and $\psi_p$ represent the conservation bias and pairwise coupling terms from the MRF model.

![avatar](https://github.com/2024-anonymous/ICML2024_rebuttal/blob/main/MHSampler.png)
