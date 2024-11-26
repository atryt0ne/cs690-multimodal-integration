# cs690-multimodal-integration

This repository contains the codebase and documentation for the final project of Group 1 in the course CS690, offered in 2024-25-I

## Environment Information

The models were trained and inferenced on a Kaggle T4 x2 GPU Environment whose specifications are -

- 30 GB CPU RAM
- 15 x2 GB GPU VRAM
- Python v3.10.14

It is advisable to use a separate python environment for each method. You can reproduce the python environment for scMODAL using the `requirements.txt` file. Alternately if running on Kaggle/Colab, please run the following command - `!pip install anndata scanpy numba umap-learn torch annoy gdown`.

## Dataset Information

All datasets are publicly available. For convenience, we have included code to download the datasets at the beginning of the notebook which will download the dataset for you. The details of the datasets used are -

1. PBMC
2. Tonsil
3. TeaSeq

## Code

Kaggle/Colab links for every notebook are provided at the top of every notebook. A brief description of each file is outlined below -

1. scMODAL_PBMC - Trains and runs scMODAL on the PBMC dataset using the protein-gene conversion matrix
2. scMODAL_CCA_PBMC - Trains and runs scMODAL on the PBMC dataset using CCA (?)
3. scMODAL_tonsil - Trains and runs scMODAL on the Tonsil dataset using CCA (?)
4. scMODAL_teaseq - Trains and runs scMODAL on trimodal data (?)
5. MaxFuse_PBMC - Trains and runs MaxFuse on PBMC data
6. MaxFuse_tonsil - Trains and runs MaxFuse on Tonsil data
