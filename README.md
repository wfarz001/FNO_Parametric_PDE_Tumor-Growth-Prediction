# FNO_Parametric_PDE_Tumor-Growth-Prediction
Developed experiments on reaction-diffusion PDE for tumor growth model. The proposed framework will apply FNO on the initial tumor density map to predict final tumor growth.

Partial differential equation (PDE) of reaction-diffusion type is applied to model the tumor growth, which describes the spatial distribution of tumor cell density and tumor behavior: proliferation and infiltration. Traditional PDE
solver such as finite element methods (FEM) and finite difference methods (FDM) rely on discretizing the space into a very fine mesh which can be slow and inefficient. The neural operator is mesh-independent, different from the standard deep learning
methods such as Convolutional Neural Network (CNN).

Fourier neural operator (FNO) leverages neural networks with Fourier transforms to map its input function to the target function in the frequency domain, showcasing notably superior performance compared
to traditional CNNs. The design of FNO utilizes global Fourier filters, whereas CNNs rely on local filters.

<img width="977" height="371" alt="FNO" src="https://github.com/user-attachments/assets/2a365834-97c5-4372-848e-4e33b69a0726" />

Generated Simulated Samples with solving Forward PDE model:

<img width="4500" height="2100" alt="sample_0_D_0 0002_r_0 0204" src="https://github.com/user-attachments/assets/83a2cc28-7c32-410e-9537-f9947dc6fdc8" />

<img width="4500" height="2100" alt="sample_1_D_0 0052_r_0 0551" src="https://github.com/user-attachments/assets/65fc3ab0-e9aa-4996-a392-043fdc2aeeac" />

<img width="4500" height="2100" alt="sample_2_D_0 0077_r_0 0279" src="https://github.com/user-attachments/assets/be4679a4-716c-4e75-9c1d-a95f37cf3d47" />



For Details Documentation:
Please refer to the pdf file and power point presentation.

Code Folder Structure:
1. PDE_Simulated_Samples : Codes for generating Samples
2. Neural_Networks_CNN_vs_FNO : Codes for comparison between CNN and FNO with different loss functions
3. Performace_Comparison: To ceate the performance comparison table

All codes are written within Jupter Notebooks and codes were run on High Performance Computing (HPC) with NVIDIA 16GB V100.
