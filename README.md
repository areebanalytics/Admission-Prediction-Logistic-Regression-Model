🎓 SAT Admission Prediction using Logistic Regression

This project predicts student admission decisions based on their SAT scores and gender using Logistic Regression.

🧠 Project Overview

The goal of this project is to build a logistic regression model to classify whether a student gets admitted (1) or not (0) based on SAT scores.
The dataset contains SAT scores and gender information for several students.

import pandas as pd
import numpy as np
import statsmodels.api as sm
import matplotlib.pyplot as plt
import seaborn as sns
sns.set()

Dataset

The dataset contains the following columns:
SAT – Student SAT scores
Gender – Male/Female (encoded)
Admitted – Admission decision (1 = admitted, 0 = not admitted)



Steps Performed
Loaded and explored the dataset
Visualized data using Seaborn and Matplotlib
Built a Logistic Regression model using StatsModels
Evaluated model accuracy using a confusion matrix







https://colab.research.google.com/drive/1hMK8tFlLGPHGRomjwXaeqs6vNkn16a_S?usp=drive_link
