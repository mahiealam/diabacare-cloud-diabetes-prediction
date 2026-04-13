# The DiabaCare Cloud: Predicting Diabetes Using Machine Learning

#[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mahiealam/diabacare-cloud-diabetes-prediction/blob/main/notebooks/DIABACARE_Cloud_I1.ipynb)
#[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mahiealam/diabacare-cloud-diabetes-prediction/blob/main/notebooks/DIABACARE_Cloud_I2.ipynb)
#[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
#[![DOI](https://img.shields.io/badge/DOI-10.4025%2Factascitechnol.v46i1.64783-blue)](https://doi.org/10.4025/#actascitechnol.v46i1.64783)

## Project Overview
The **DiabaCare Cloud** project focuses on the implementation and evaluation of supervised Machine Learning (ML) algorithms to enhance the early detection of diabetes. Using a publicly available dataset of 768 individuals, this research explores the efficiency of various classification techniques—including Random Forest, Support Vector Machines, and others—to identify the most reliable model for clinical decision support systems.

The goal is to provide a scalable, cloud-compatible framework for predicting diabetic onset based on diagnostic measurements.

## Results
Through rigorous testing and hyperparameter optimization, the research found that the **Random Forest** algorithm outperformed all other tested classifiers.

* **Baseline Accuracy:** 78.44%
* **Optimized Random Forest Accuracy:** **79.52%**
* **Correct Predictions:** 173 out of 218 test samples.

The "tweaks" and optimizations performed on the Random Forest model provided a 1.08% improvement over the standard implementation, establishing it as the most effective model for this dataset.

## Dataset
This project uses the **Pima Indians Diabetes Database**. The dataset includes several medical predictor variables and one target variable (Outcome). 
- **Predictors:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age.
- **Target:** Outcome (0 for non-diabetic, 1 for diabetic).

## Usage
To run the code, you can open the notebook directly in Google Colab using the badge at the top of this file. Ensure you have the following libraries installed:
* `scikit-learn`
* `pandas`
* `numpy`
* `matplotlib`

## Citation
If you find this research or code useful, please cite the original paper:

### APA Format
Alam, M., Khan, I. R., Alam, M. A., Siddiqui, F., & Tanweer, S. (2023). The diabacare cloud: predicting diabetes using machine learning. *Acta Scientiarum. Technology*, 46(1), e64783. https://doi.org/10.4025/actascitechnol.v46i1.64783

### BibTeX
```bibtex
@article{Alam2023Diabacare,
  title={The diabacare cloud: predicting diabetes using machine learning},
  author={Alam, Mehtab and Khan, Ihtiram Raza and Alam, Mohammad Afshar and Siddiqui, Farheen and Tanweer, Safdar},
  journal={Acta Scientiarum. Technology},
  volume={46},
  number={1},
  pages={e64783},
  year={2023},
  doi={10.4025/actascitechnol.v46i1.64783}
}
