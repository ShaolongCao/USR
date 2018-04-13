# USR
matlab code for USR variable selection.

# Abstract
Joint adjustment of cryptic relatedness and population structure is necessary to reduce bias in DNA sequence analysis; however, existent sparse regression methods model these two confounders separately. Incorporating prior biological information has great potential to enhance statistical power but such information is often overlooked in many existent sparse regression models. We developed a unified sparse regression (USR) to incorporate prior information and jointly adjust for cryptic relatedness, population structure, and other environmental covariates. Our USR models cryptic relatedness as a random effect and population structure as fixed effect, and utilize the weighted penalties to incorporate prior knowledge. As demonstrated by extensive simulations, our USR algorithm can discover more true causal variants and maintain a lower false discovery rate than do several commonly used feature selection methods. It can handle both rare and common variants simultaneously. Applying our USR algorithm to DNA sequence data of Mexican Americans from GAW18, we replicated three hypertension pathways, demonstrating the effectiveness in identifying susceptibility genetic variants.

# Reference
Shaolong Cao, Huaizhen Qin, Hong-Wen Deng and Yu-Ping Wang. “A unified sparse representation for sequence variant identification for complex traits”. Genetic Epidemiology, 38(8):671-9. doi: 10.1002/gepi.21849
