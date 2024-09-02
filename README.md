# Bayesian Analysis: Modeling for Medical Insurance Costs Bayesian

To create optimal medical insurance products, insurers rely on historical data to estimate individual medical expenses. This data allows for precise pricing models, strategic insurance planning, and effective portfolio management. The primary goal is to accurately predict insurance costs using various predictor variables. The dataset used for this analysis is available from Synthesized at this URL:  https://www.synthesized.io/data-template-pages/medical-cost-personal-dataset

---

## Data set
The dataset analyzed contains 1,339 medical insurance records, aiming to predict individual medical costs ("Charges"). It includes six features: 
- Age (numerical): The age of the insurance contractor
- Sex (categorical):  Indicates the insurance contractor gender (male of female)
- BMI (numerical): Body mass index of the client (kg/m^2)
- Children (numerical): Number of children of the client
- Smoker (categorical): Whether the contractor smokes or not
- Region (categorical): Beneficiary’s residential in the United States (northeast/southeast/southwest/northwest)
- Charges represent the target variable (numerical): Individual medical costs billed by health insurance
  
Due to privacy concerns, synthetic data with 95% similarity to the original was used to ensure compliance with regulations like GDPR while maintaining statistical integrity.

---

## Libraries required
```r
c("dplyr", "MCMCpack", "coda", "R2OpenBUGS", "mixAK", "brms")
```

---
