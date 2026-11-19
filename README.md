# Brain Stroke Risk and Binary Response Models

This project presents an empirical analysis of **stroke risk using binary response models**, developed as part of the Econometrics II course. Using a real-world health dataset, we study how demographic and medical factors influence the probability of an individual experiencing a stroke.

## Objective

The main goal of this project is to estimate and interpret the marginal effects of key risk factors—such as age, hypertension, and heart disease on stroke occurrence, while comparing different econometric models for binary outcomes.

## Data

**Source**: Kaggle – Brain Stroke Dataset

**Observations**: 4,981 individuals

**Variables** include demographic characteristics, health conditions, lifestyle indicators, and stroke occurrence (binary outcome).

## Methodology

We estimate and compare three binary response models:

- Linear Probability Model (LPM)

- Logit Model

- Probit Model

Model selection is guided by interpretability, statistical significance, and the Akaike Information Criterion (AIC). The Probit model is chosen as the preferred specification due to its overall performance and better fit.

## Key Findings

- Stroke risk increases significantly with age, hypertension, and heart disease.

- Hypertension alone raises the probability of stroke by approximately 1.03 percentage points, on average.

- The Probit model is statistically significant at the global level and performs well despite the low prevalence of stroke in the sample.

## Model Evaluation

Classification accuracy is high, though results must be interpreted cautiously due to class imbalance.

The model achieves a **Pseudo R² of 0.205**, indicating a satisfactory fit for a health-related binary outcome.

## Limitations

Stroke is a rare event, which affects predictive performance.

The analysis focuses on association rather than causality.

Relevant variables such as physical activity, diet quality, or genetic factors are not available and may lead to omitted variable bias.

## Output

The repository includes:

R scripts and RMarkdown analysis

Cleaned dataset

Final empirical poster summarizing the results
