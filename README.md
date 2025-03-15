# PML Final Project Repository

This repository contains the code and data for the PML Final Project by Elizaveta Ignatova, Nicola Bertoni and Giovanni Lombardi (Group 04).

## Project Overview

This project explores **diffusion-based generative models** and **function fitting with constraints**, focusing on two key problems:

1. **Diffusion-Based Generative Models**  
   - Implemented and analyzed variations of a Denoising Diffusion Probabilistic Model (DDPM) on MNIST.  
   - Explored alternative loss estimations, continuous-time diffusion models (SDEs), and conditional image generation.  
   - Evaluated model performance using Inception Score (IS), Fréchet Inception Distance (FID), and likelihood estimation.

2. **Function Fitting with Constraints**  
   - Developed Gaussian Process (GP) models with and without integral constraints.  
   - Compared MAP estimation vs. Bayesian sampling (NUTS) for parameter inference.  
   - Analyzed how enforcing an integral constraint affects model predictions.

The full report is available in `docs/project_report.pdf`.

## Repository Structure

- **`notebooks/`** – Jupyter notebooks with solutions to Problems A and B.
- **`data/`** – Pre-trained models and other stored variables in `.pth` and `.pkl` format.
- **`docs/`** – Contains the **final project report** and additional documentation.
- **`README.md`** – Instructions and overview of the repository.

## Running the Notebooks

You can run the notebooks directly on Google Colab without any local setup.

### **Open in Colab**

To open the notebooks in Google Colab, click the **Open In Colab** badges below. The table also provides descriptions detailing each group member's contributions.

| Notebook      | Description                                                                                                               | Open in Colab                                                                                                       |
|---------------|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| **Problem_A_** | Contains solutions to the first two bullet points of Problem A.1 and the comparison of corresponding models (part of Problem A.2). Contributions: **Bertoni 50%**, **Lombardi 50%**. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GioLombardi/PML-Final-Project/blob/main/notebooks/Problem_A_.ipynb) |
| **A_Ignatova**| Includes solutions to the last two bullet points of Problem A.1 and the comparison of the corresponding models (part of Problem A.2). Authored entirely by **Ignatova**. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GioLombardi/PML-Final-Project/blob/main/notebooks/A_Ignatova.ipynb) |
| **Problem_B** | Contains the solution to Problem B. Contributions: **Lombardi 50%**, **Bertoni 50%**.                                    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GioLombardi/PML-Final-Project/blob/main/notebooks/Problem_B.ipynb)  |

### **Manual Access**

If you prefer to access the Colab notebooks manually, please follow these steps:
1. Go to [Google Colab](https://colab.research.google.com/).
2. Click on **"File"** > **"Open notebook"**.
3. Select the **"GitHub"** tab.
4. Enter the repository URL: `https://github.com/GioLombardi/PML-Final-Project`.
5. Choose the notebook you wish to open and click **"Open"**.

## Notes

- **Execution Environment:** All code was developed and executed using Google Colab.

- **Dependencies:** The necessary Python packages are installed directly within the notebooks using `pip`. Ensure that you run all cells in the notebooks to install any required dependencies before executing the main code.

- **Repository Structure:** Maintaining the directory structure (`/notebooks` and `/data`) is crucial for the seamless loading of data files within the notebooks.
