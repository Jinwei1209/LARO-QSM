# LARO: Learned Acquisition and Reconstruction Optimization to accelerate Quantitative Susceptibility Mapping
Code of LARO for multi-echo gradient echo (mGRE) acceleration for Quantitative Susceptibility Mapping ([NeuroImage 2023](https://www.sciencedirect.com/science/article/pii/S1053811923000356), [MICCAI 2021](https://link.springer.com/chapter/10.1007/978-3-030-87231-1_23) and [MLMIR@MICCAI 2020](https://link.springer.com/chapter/10.1007/978-3-030-61598-7_9))

The multi-contrast extension, mcLARO, for simultaneous T1, T2, T2, and QSM mapping is available in [MRM 2024](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.29854).

Network architecture of LARO. (a) deep ADMM reconstruction. (b) sampling pattern optimization module. (c) temporal feature fusion module:
![Network architecture of LARO. (a): deep ADMM reconstruction. (b): sampling pattern optimization module. (c): temporal feature fusion module.](https://raw.githubusercontent.com/Jinwei1209/LARO-QSM/main/figures/figure1.png)

Illustration of (a) the proposed segmented k-space ordering strategy of ten echoes and (b) pulse sequence design:
![Illustration of (a): the proposed segmented k-space ordering strategy of ten echoes and (b): pulse sequence design.](https://raw.githubusercontent.com/Jinwei1209/LARO-QSM/main/figures/figure2.png)

TFF reconstructions on prospectively under-sampled raw k-space data of one healthy subject with acceleration factor R=8:
![TFF reconstructions on prospectively under-sampled raw k-space data of one healthy subject with acceleration factor R=8.](https://raw.githubusercontent.com/Jinwei1209/LARO-QSM/main/figures/figure7.png)


To simultaneously update the multi-echo sampling pattern and image reconstruction network, run:

```python main_multi_echo_MS.py --flag_train=1 --K=2 --loupe=2```

Please contact jwzhang@jhu.edu for questions and data sharing. 
