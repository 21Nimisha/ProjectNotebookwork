# Real Estate Price Prediction Project for Gurgaon Properties:

## 🏡 Project Overview:
In this project, I dive into the dynamic world of real estate in Gurgaon, utilizing advanced data science techniques to analyze and predict property prices. My goal is to uncover the key factors driving the housing market and transform raw data into actionable insights.

## 📚 *Notebooks Overview*

### *1*: Data Import and Cleaning
I start by importing the dataset and executing initial cleaning steps to ensure data quality and readiness for analysis.

### *2*: Exploratory Data Analysis (EDA)
I perform a deep-dive analysis using Pandas Profiling, uncovering hidden patterns and relationships in the dataset to lay the groundwork for informed modeling.

### *3*: Outlier Treatment and Analysis
I identify and manage outliers in critical features like Price and Area, using logical reasoning to enhance the dataset's integrity and robustness.

### *4*: Feature Selection Techniques
I leverage eight powerful feature selection techniques, revealing that Built-up Area is the standout predictor for property prices, optimizing model performance through informed feature choices.

### *5*: Model Training and Evaluation
I implement a sophisticated preprocessing pipeline with One-Hot Encoding and Scaling, evaluating models like Linear Regression and SVR. I discover that SVR dramatically outperforms linear models, significantly reducing prediction errors.

### *6*: Model Selection and Finalization
I finalize the most effective models through rigorous evaluation and hyperparameter tuning, ultimately selecting Random Forest and Extra Trees for deployment-ready performance.

## 📈 Key Findings
- **Premium Sectors**: Sectors 25, 26, and 27, owned by DLF, showcase the highest property prices.
- **Old vs. New Gurgaon**: Sectors 1 to 10 represent "Old Gurgaon," with prices ranging from 1 lakh to 2 crores, while newer sectors (above 70) are still developing and more affordable.
- **Data Insights**: My analysis reveals intricate relationships between property features, driving informed decision-making in the real estate landscape.

## 🔍 Final Model Selection
After extensive testing, I identify Extra Trees and Random Forest as the top contenders, achieving a remarkable drop in Mean Absolute Error (MAE) from 0.94 to 0.50. These models are now primed for deployment, ready to deliver real-time price predictions.

## 🚀 Deployment Ready
I have packaged the final model and preprocessing steps for deployment, creating df.pkl and pipeline.pkl. This facilitates seamless integration into web applications for instant property price predictions.

## 🛠 Technologies Used
- **Python**: The backbone of my analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For efficient numerical computations.
- **Scikit-learn**: The go-to library for machine learning.
- **XGBoost**: For advanced boosting algorithms.
- **Matplotlib/Seaborn**: For stunning visualizations and insights.

## 📂 Main Resources

- [Notebooks](https://github.com/21Nimisha/ProjectNotebookwork/blob/main/notebooks/README.md)
- [Documentation](https://github.com/21Nimisha/ProjectNotebookwork/tree/main/docs)
- [Data](https://github.com/21Nimisha/ProjectNotebookwork/tree/main/data)
