The general workflow for building an adult PBPK model has been described by Kuepfer et al. ([Kuepfer 2016](#5-References)). Relevant information on the anthropometry (height, weight) was gathered from the respective clinical study, if reported. Information on physiological parameters (e.g. blood flows, organ volumes, hematocrit) in adults was gathered from the literature and has been incorporated in PK-Sim® as described previously ([Willmann 2007](#5-References)). The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available 'PK-Sim® Ontogeny Database Version 7.3' ([PK-Sim Ontogeny Database Version 7.3](#5-References)).

Only the  S-enantiomer of mephenytoin is modeled. The modeling work flow can be summarized as following:

| **Modelling step**                                           | **Data used / comment**                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **1.) Development of mean po model (no i.v. data  available)** | IVIVE based on physico-chemistry and in vitro  metabolization or recalculated in vivo clearance.  Alternative middle out fits to in vivo data were tried but could not improve DDI prediction significantly. Additional limited data lead to identifiability problems. |
| **2.) Evaluation of p.o. model with virtual PK-Sim  population** | Range and mean plasma profiles after p.o. admininstration for the study population was in line with the PK-Sim in-built variability of  CYP2C9 and CYP2C19. |

The predefined “Standard European Male for DDI” individual was used (age = 30 y, weight = 73 kg, height = 176 cm, BMI = 23.57 kg/m2). CYP2C19 expression from the PK-Sim in-built RT-PCR database was added.

Due to the limited data, an IVIVE approach has been selected. Parameters describing intrinsic CYP2C19 clearance were recalculated from CL/F ([Adedoyin 1998](# 5 References)) and in vitro metabolism data from human microsomes CYP2C19 clearance and CYP2C9 clearance ([Steere 2015](# 5 References)).

A simulation of a population with 2000 virtual individuals according to the biometrics of the individuals (8 males and females, 32-78 years) used in a study by [Adedoyin 1998](# 5 References) was carried out. Additional variability was included on CYP2C19 among the population, by using the geometric SD as derived from reported CL/F values in [Olivares-Morales 2016](# 5 References).

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#2.2-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#2.3-Model-Parameters-and-Assumptions).

