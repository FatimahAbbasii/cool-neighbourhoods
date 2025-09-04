# Cool Neighbourhoods 

A supervised machine learning project to study **heat wave patterns** and predict temperature using historical sensor data.  
This work is part of the **[Cool Neighbourhoods](https://coolneighbourhoods.nweurope.eu/)** initiative, an **[Interreg](https://interreg.eu/)** subsidized project aimed at combating heat stress in disadvantaged neighborhoods through **data-driven insights**.

---

## Project Overview
Urban heat stress is a growing public health and sustainability concern. Vulnerable communities are often disproportionately affected by heat waves and urban heat island effects.  
This internship project contributes to the Cool Neighbourhoods initiative by building predictive models to help identify and mitigate heat stress through **temperature forecasting**.

---

## Background
Sensors are deployed in multiple pilot areas across the **Benelux region**, collecting real-time environmental data.  
By leveraging these datasets, the project aims to:
- Predict temperature patterns under varying weather conditions,  
- Provide insights into heat stress risk,  
- Support decision-makers in designing interventions for more resilient urban spaces.  

---

## Core Assignment
**Objective:**  
Develop a supervised regression model to predict temperature using historical sensor data from pilot locations.  

**Available resources:**  
- Historical sensor datasets from multiple pilot areas,  
- Measurements include temperature, humidity, and related environmental variables,  
- Prepared and structured data files ready for analysis.  

---

## Methodology (CRISP-DM Framework)
The project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** cycle:

1. **Business Understanding** → Define the heat stress challenge and project goals.  
2. **Data Understanding** → Explore sensor datasets, check quality, and identify relevant variables.  
3. **Data Preparation** → Clean, preprocess, and engineer features for modeling.  
4. **Modeling** → Train supervised regression models (baseline → advanced).  
5. **Evaluation** → Assess models with metrics such as MAE and RMSE.  
6. **Deployment** → Summarize results, provide recommendations, and document insights.  

---

## Planned Iterations
1. **Baseline Regression** → Simple temperature prediction model.  
2. **Weather Data Integration** → Incorporate external weather data (temperature, humidity, etc.).  
3. **Stronger Models** → Apply ensemble methods (Random Forest, Gradient Boosting).  
4. **Extension: Heat Stress Event Classification** → Binary classification of “heat stress events” (e.g., `Temp > X°C & Humidity > Y%`).  

---

## Repository Layout


```text
cool-neighbourhoods/
├── src/                     # Core source code (modules, utils, pipelines)
│   └── cool_neighbourhoods/ # Main package
├── notebooks/               # Jupyter notebooks for exploration & prototyping
├── configs/                 # Configuration files (YAML/JSON) for experiments
├── tests/                   # Unit and integration tests
├── data/                    # Datasets (ignored in Git; tracked with DVC)
├── model_card.md            # Model documentation (assumptions, limitations)
├── dataset_datasheet.md     # Dataset documentation (provenance, structure)
└── .github/
    └── workflows/ci.yml     # CI/CD pipeline for testing & linting
```
---

## Tech Stack
- Python, pandas, scikit-learn  
- DVC (data & pipeline tracking)  
- MLflow (experiment tracking)  
- pytest (testing)  

---

## Contact
[![Email](https://img.shields.io/badge/Email-fatimahabbasi96%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:fatimahabbasi96@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fatimah%20Abbasi-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/fatimah-abbasi-6b4706315)

---

