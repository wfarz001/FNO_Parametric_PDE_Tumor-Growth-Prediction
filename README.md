# FNO_Parametric_PDE_Tumor-Growth-Prediction
Developed experiments on reaction-diffusion PDE for tumor growth model. The proposed framework will apply FNO on the initial tumor density map to predict final tumor growth.

Partial differential equation (PDE) of reactiondiffusion type is applied to model the tumor growth, which describes the spatial distribution of tumor cell density and tumor behavior: proliferation and infiltration. Traditional PDE
solver such as finite element methods (FEM) and finite difference methods (FDM) rely on discretizing the space into a very fine mesh which can be slow and inefficient. The neural operator is mesh-independent, different from the standard deep learning
methods such as Convolutional Neural Network (CNN).

Fourier neural operator (FNO) leverages neural networks with Fourier transforms to map its input function to the target function in the frequency domain, showcasing notably superior performance compared
to traditional CNNs. The design of FNO utilizes global Fourier filters, whereas CNNs rely on local filters.

<img width="977" height="371" alt="FNO" src="https://github.com/user-attachments/assets/2a365834-97c5-4372-848e-4e33b69a0726" />
