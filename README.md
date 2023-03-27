# LARO: Learned Acquisition and Reconstruction Optimization to accelerate Quantitative Susceptibility Mapping
Code of LARO for multi-echo gradient echo (mGRE) acceleration for Quantitative Susceptibility Mapping ([NeuroImage 2023](https://www.sciencedirect.com/science/article/pii/S1053811923000356), [MICCAI 2021](https://link.springer.com/chapter/10.1007/978-3-030-87231-1_23) and [MLMIR@MICCAI 2020](https://link.springer.com/chapter/10.1007/978-3-030-61598-7_9))

To simultaneously update the multi-echo sampling pattern and image reconstruction network, run:

```python main_multi_echo_MS.py --flag_train=1 --K=2 --loupe=2```
