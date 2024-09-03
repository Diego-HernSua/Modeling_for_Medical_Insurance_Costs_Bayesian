# Bayesian Analysis: Modeling for Medical Insurance Costs

📊 **Overview**: To create optimal medical insurance products, insurers leverage historical data to estimate individual medical expenses. This data helps in developing precise pricing models, strategic insurance planning, and effective portfolio management. The primary aim is to predict insurance costs accurately using various predictor variables. The dataset used for this analysis is available from Synthesized at this URL: [Synthesized Medical Cost Personal Dataset](https://www.synthesized.io/data-template-pages/medical-cost-personal-dataset)

---

## 📋 Data Set

The dataset analyzed contains **1,339** medical insurance records, aiming to predict individual medical costs ("Charges"). It includes the following features:

- **Age** (numerical): The age of the insurance contractor
- **Sex** (categorical): Gender of the insurance contractor (male or female)
- **BMI** (numerical): Body mass index of the client (kg/m²)
- **Children** (numerical): Number of children of the client
- **Smoker** (categorical): Whether the contractor smokes or not
- **Region** (categorical): Beneficiary’s residence in the United States (northeast/southeast/southwest/northwest)
- **Charges** (numerical): Individual medical costs billed by health insurance

*Note:* Due to privacy concerns, synthetic data with **95% similarity** to the original was used to ensure compliance with regulations like GDPR while maintaining statistical integrity.

---

## 📚 Libraries Required

The following R libraries are needed for the analysis:
```r
c("dplyr", "MCMCpack", "coda", "R2OpenBUGS", "mixAK", "brms")
```

---

## 🔄 Preprocessing
I applied various modifications to the original dataset, such as converting categorical variables to binary, changing the format of some variables, among other changes, with the goal of making the dataset easier to work with.

---

## 📈 Models employed
### Lineal models
- Markov Chain Monte Carlo sampling techniques
- OpenBUGS
- Frequentist Generalized Linear Models (GLM)
- Bayesian Generalized Linear Models (GLM)
- Normal Mixture Markov Chain Monte Carlo

### Non Lineal Models
- Markov Chain Monte Carlo sampling techniques
- Bayesian Generalized Additive Models (GAM) [Non-linear]

---

## 📝 Conclusions
The detailed conclusions and results are presented in the files, where graphs and other relevant information are also shown.
