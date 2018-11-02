# Causal Survival Analysis

This repository contains the materials for the Causal Survival Analysis presented at the Kolokotrones Symposium at Harvard TH Chan School of Public Health on November 2, 2018, and developed by Ellie Caniglia, Ellie Murray, and Lucia Petito. 

This workshop is designed to provide an overview to causal inference for survival outcomes with point exposures or time-varying exposures for which static interventions, which are known at baseline, are of interest using inverse probability weighting. A static intervention is one where the exposure should take the same value at every time point (e.g. continuous treatment versus no treatment). 

The basic concepts here also apply to dynamic interventions, such as "take treatment until a side effect develops", but dynamic interventions require more complex stabilization of inverse probability weighting. Interventions which are not known at baseline, such as those allowing grace periods, will also rely on many of the basic concepts presented here, but typically require copying or "cloning" all person-time and censoring these copies when the intervention each individual actually follows can be determined. Adjustment for censoring of clones can be done using inverse probability weighting.

The data for the workshop are a simulated version of the Coronary Drug Project trial. The workshop is available for both SAS and R users. Please ensure that you have downloaded the correct version of the dataset for your preferred coding language. The workshop instructions are provided as a single file regardless of programming language. A solutions manual will be available upon completion of the live version of the workshop.

Please direct any comments, errors, or suggestions to Ellie Murray at emurray@mail.harvard.edu.

