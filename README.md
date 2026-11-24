## Hi, welcome to my profile!

I'm a scientist with a background in chemical engineering
and a passion for problem-solving, analytical thinking,
and exploring new technologies.

I have professional experience in the pharmaceutical and
consumer products industries and have expanded my expertise
into data science and machine learning.

I'm particularly interested in applying statistical analysis,
predictive modeling, and computational techniques to solve
real-world problems.

# Data Science Portfolio

Below are some data science projects I've worked on through 
my time at Johns Hopkins, using traditional data science 
tools such as Python, R, SQL, machine learning, 
and statistical analysis.

## Featured Projects

## Titanic Survival Predictions

Developed machine learning models to predict passenger
survival using the Titanic dataset. Explored data
preprocessing, feature engineering, and model evaluation
to assess predictive performance.

### Model Performance and Visualization

| Model | Accuracy | F1 Score |
|-------|----------|----------|
| K-Nearest Neighbors | 79% | 0.79 |
| Support Vector Machine | 84% | 0.84 |
| Random Forest | 81% | 0.81 |

![Titanic Model Results](https://raw.githubusercontent.com/Jeremy-Hirschler/data-science-portfolio/main/ML_Results.png)

### Conclusion: 
All models performed in a similar manner for this dataset, but the Support Vector Machine model achieved a slightly higher accuracy and F1 score among the evaluated models. See full project below:

**[View Full Project, Code, and Analysis](https://github.com/Jeremy-Hirschler/data-science-portfolio/blob/main/TitanicPredictions_ML/JHirschler_PA1.ipynb)**

---

## 📈 Zero-Inflated vs. Hurdle Regression

Conducted a comparative analysis of Zero-Inflated Poisson
and Hurdle regression models for count data containing
excess zeros. Explored differences in model assumptions,
estimation, and performance.

**Model Performance Comparison**

| Model | AIC | BIC | Log-Likelihood | MAE | RMSE |
|-------|----:|----:|---------------:|---------:|---------:|
| Poisson | 2462.5 | 2487.1 | -1226.3 | 0.781 | 1.001 |
| Zero-Inflated Poisson | 2454.9 | 2504.0 | -1217.4 | 0.771 | 0.998 |
| Hurdle | 2467.6 | 2516.6 | -1223.8 | 0.781 | 1.001 |

### Conclusion: 
Both models demonstrated comparable overall performance for different metrics such as Log-Likelihood and Mean Absolute Error (MAE), highlighting their ability to accommodate excess zeros despite differences in their underlying modeling assumptions. 

However, because synthetic data was generated for this project using a ZIP Poisson model, it was expected that the ZIP model would demonstrate a stronger performance on the dataset, consistent with the underlying data-generating process. See the full report and associated R code below:

**[View Full Research Report (PDF)](https://github.com/Jeremy-Hirschler/data-science-portfolio/blob/main/ZeroInflated_vs_Hurdle_Regression/JHirschler_ZIP_Hurdle.pdf)**

**[View R Source Code](https://github.com/Jeremy-Hirschler/data-science-portfolio/blob/main/ZeroInflated_vs_Hurdle_Regression/Zero_Inflation.R)**
