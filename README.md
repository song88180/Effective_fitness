# Effective fitness under fluctuating selection with genetic drift

Here are analysis scripts used in (Song & Zhang, 2023, in review) titled 
"Effective fitness under fluctuating selection with genetic drift"

### 1\_Introductory\_example.ipynb

This notebook contains scripts to generate an example where fluctuating selection 
generated a strongly deleterious genometric mean fitness $f_G$ ("strongly" means 
the selection coefficient $|s| > \frac{1}{N_e}$ in a haploid population). The 
example is used in **Figure 1** of the paper.

### 2\_Numerical\_validation.ipynb

This notebook contains scripts for numerical validation of question II in 
**Figure 2** of the paper. That is, whether the expected mutant frequency change 
under fluctuating selection in the presence of drift equals that caused by a 
constant selection with $f_G$ in the presence of drift. The results are shown in 
**Figure S1** of the paper.

### 3\_Simulations\_fG\_1\_fE\_1.ipynb

This notebook contains scripts for population genetic simulations wehre geometric 
mean fitness $f_G$ and effective fitness $f_E$ are controlled to be  strictly 
neutral ($f_G=1$, $f_E=1$). The results are shown in **Figure 3A** of the paper.

### 4\_Simulation\_bin\_by\_AF.ipynb

This notebook contains scripts for population genetic simulations under fluctuating 
selection. Simulation runs are collected if their final mutant frequencies are 
exaxtly 0.100, 0.200, ..., 0.900. See Methods in (Song & Zhang, 2023, in review) 
for details. Results are shown in **Figure 3BC** and **Figure S2AB** of the paper.

### 5\_AUC\_ROC\_fG\_fE.ipynb

This notebook contains scripts for calcualating the area under the receiver 
operating characteristic (ROC) curve, or AUC, of $f_E$ and $f_G$, with initial 
mutant frequency of 0.01 or 0.5. The results are shown in **Figure 3D** and 
**Figure S2C** of the paper. Because the difference in AUC between $f_E$ and $f_G$ 
is small when the initial mutant frequency is 0.5, we further focused on the 
simulation runs where $f_E$ contradicts $f_G$ for comparison. The results are 
shown in **Figure S2D** of the paper. 

### 6\_Contribution\_of\_selection.ipynb

This notebook contains scripts for calculating the contribution of selection 
in fluctuationg selection simulations starting from a single mutant. The results 
are shownin **Figure 4** of the paper.


