# **Uncertainty Quantification in Neural-Network Based Pain Intensity Estimation**

This repository contains code for implementing "Uncertainty Quantification in Neural-Network Based Pain Intensity Estimation" paper. The code is organized into several Jupyter notebooks, each serving a specific purpose in the pipeline of pain intensity estimation.

## **Contents:**

- **PainPredictionInterval.ipynb** : This is the main code to develop prediction intervals for pain intensity estimation. Prediction intervals provide a range of values where the true pain intensity is likely to fall with a certain level of confidence. It uses gradient descent algorithm.

- **Plots_GA_vs_GD_vs_Bootstrap.ipynb**: This notebook contains the code to compare different methods used in pain intensity estimation, including gradient descent, genetic algorithm, and bootstrap. Comparing these methods helps in understanding their strengths and limitations in the context of pain intensity estimation.

- **ParameterTuning_Lambda_Softening.ipynb**: This notebook contains the code for parameter tuning, particularly focusing on the lambda and softening parameters. Parameter tuning is crucial for optimizing the performance of the neural network model.

- **Clustering.ipynb**: This notebook contains the code for clustering the data. Clustering is an important preprocessing step for pain intensity estimation as it helps in identifying patterns and grouping similar data points together.

- **Plot_Grouped_Bar_Chart.ipynb**: This notebook contains the code for generating grouped bar charts. These charts are helpful in visualizing and comparing different aspects of the data, such as pain intensity across different groups or categories.

You can access the paper through the following link: https://arxiv.org/abs/2311.08569


