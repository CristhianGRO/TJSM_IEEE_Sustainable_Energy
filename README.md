<div align="center">
    <img src="sensitivity_4Bus.svg" style="width: 20vw">
    
    Data repository for journal paper "Three-Phase Jacobian-Based Voltage Sensitivity 
    Method for Hosting Capacity Analysis", submitted for IEEE Transactions on Sustainable Energy.
</div>

<br><br>

# ⛅ Introduction

This repository gathers the data used to develop the simulations and the results obtained, set out in the article _"Three-Phase Jacobian-Based Voltage Sensitivity Method for Hosting Capacity Analysis"_, submitted to the IEEE Transactions on Sustainable Energy.

This material aims to enable other researchers on the subject to use the model adopted for comparing and validating results and developing new research on the subject.

<br><br>

# 🗂️ Repository organization 

## Folder: _Results_
This folder contains the data from the distribution system model used for the simulations.

### - Subfolder: _Sensitivity Matrix_

This subfolder contains the voltage sensitivity matrix for the IEEE 4-node and 37-node feeder, considering all the load models analyzed in the paper.

- `active_sensitivity_4Bus_Pconst.csv`: Voltage sensitivity matrix due to active power injection for the IEEE 4-node feeder, considering loads as constant power model; 
- `reactive_sensitivity_4Bus_Pconst.csv`: Voltage sensitivity matrix due to reactive power injection for the IEEE 4-node feeder, considering loads as constant power model; 
- `active_sensitivity_37Bus_Pconst.csv`: Voltage sensitivity matrix due to active power injection for the IEEE 37-node feeder, considering loads as constant power model; 
- `reactive_sensitivity_37Bus_Pconst.csv`: Voltage sensitivity matrix due to reactive power injection for the IEEE 37-node feeder, considering loads as constant power model; 

### - Subfolder: _Voltage Estimation Error_

This subfolder contains the voltage estimation results for the IEEE 37-node feeder. Each file represents the data used to draw each of the paper's graphs.

### - Subfolder: _Maximum Allowable Injection Estimation_

This subfolder contains the Maximum Allowable Injection estimation results for the IEEE 37-node feeder. Each file represents the data used to draw each of the paper's graphs.

<br><br>

# 💾 Download
Download the data from this repository in `.zip` format [using this link](https://github.com/CristhianGRO/TJSM_IEEE_Sustainable_Energy/archive/refs/heads/main.zip)



<br><br>

# ✉️ Contact

Questions or suggestions? Get in touch with us:

- **E-mail:** cristhian_oliveira@usp.br | cristhiangro@gmail.com

<br><br>

# 💬 Cite this repository

```bibtex
@misc{Cristhian_TJSM_2025,
    title    = {Three-Phase Jacobian-Based Voltage Sensitivity Method for Hosting Capacity Analysis, submitted for IEEE Transactions on Sustainable Energy - Repository.},
    year     = {2025},
    url      = {https://github.com/CristhianGRO/TJSM_IEEE_Sustainable_Energy},
    author   = {Cristhian Gabriel da R. de Oliveira, Wandry R. Faria, Benvindo R. Pereira Jr. and João B. A. London Junior},
    keywords = {Distributed Generation, Photovoltaic Systems, Voltage Sensitivity Analysis, Unbalanced Networks.},
}
```
