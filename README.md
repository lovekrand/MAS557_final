# MAS557, KAIST 2024 (SPRING) Final Project


Group2, Dept. of Mathematical Sciences, Sungjong Lee, Jingu Hwang, 

We modified the Multi-wavelet Operator[Gupta, et al, 2021] and designated it as Self-Adaptive Multiwavelet Operator. 
More experiment details are provided in the main.ipynb file.

### Requirements
The code package is developed using Python 3.9 and Pytorch 2.2 with cuda 12.3. 

### Disclaimer
The skeleton codes and baseline model are extracted from (https://github.com/gaurav71531/mwt-operator)

## Experiments
### Data
We have provided the entire pipeline code via main.ipynb file. You can simulate the figures appearing in the final paper by downloading one of the datasets provided below. In fact, Kdv and Burger's equation uses the same dataset as in the original MWO paper. The results appearing on the pipeline code learn Burger's equation with lesser training data(which was our last experiment setup), so some of the figures may seem disparate from the one on the paper. However, if you try with KdV data, you will be able to obtain the same results.

For KdV equation : A sample generated dataset for KdV is uploaded at [KdV data](https://drive.google.com/drive/folders/1--KYHPjl-pkrrGRtH8eg0aG7q8hUjiKg).

For Burgers equation : For the experiments on Burgers, the code package uses the datasets as provided in the following repository by the Authors Zongyi Li et al.

[PDE datasets](https://drive.google.com/drive/folders/1UnbQh2WWc6knEHbLn-ZaXrKUZhp7pjt-)

For Wave equation : To use the wave equation as data, run the ipynb file named wave_eqn_generate.ipynb and save the .npz file.

### Figures
You can check the experiment details, outcomes and figures of each PDE equation in the respective folders. We provided several figures and plots to verify our experiments were geniue.
