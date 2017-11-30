﻿﻿# ﻿ Neural Component Analysis for Fault Detection***- Code for the paper "Neural Component Analysis for Fault Detection"- Directory "data" contains the simulated TE data for experiments- File "myfunction\_pca_kde.m" is designed for performing PCA on TE data- File "myfunction\_kernel\_pca_kde.m" is designed for performing Kernel PCA on TE data- Please run the matlab code with the data in the same directory- File "kde.m" is used for density estimation - File "autoencoder.py" is designed for performing autoencoder on TE data- File "nca.py" is designed for performing NCA on TE data- The python codes is developed with the package PyTorch. Please install  the following python libraries before running the python codes*** ## Requirements for running the python codes, "nca.py" and "autoencoder.py"#####  Please install the following python libraries before running the code- python==3.52- numpy==1.13.3- PyTorch==0.20- scikit-learn==0.19.0##### RunOn linux:- python3 nca.py- python3 autoencoder.py