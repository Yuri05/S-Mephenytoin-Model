### 2.3.1 Absorption

Intestinal permeability is calculated by PK-Sim. No data are available to estimate the parameter.

### 2.3.2 Distribution

Partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard` have been assumed. Identification of the best suited calculation methods was not possible due to lack of i.v. data.

### 2.3.3 Metabolism and Elimination

Two linear metabolic pathways for S-mephenytoin were implement in the model:

* CYP2C19
* CYP2C9

Additionally, glomerular filtration was implemented with assumed GFR fraction of 1. No active renal excretion described in literature. Renal clearance is minor compared to overall plasma clearance ([Jacqz 1986](# 5 References)) and can be described by glomerular filtration.

### 2.3.5 Automated Parameter Identification

Performing parameter identification on lipophilicity, CYP2C19 intrinsic clearance, and intestinal permeability did not improve the performance of the model. Therefore, no parameters have been estimated.
