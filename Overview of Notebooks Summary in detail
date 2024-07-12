# Real Estate Data Analysis Project

Welcome to the Real Estate Data Analysis Project, where we explore and analyze housing trends in Gurgaon using advanced data science techniques. This project aims to provide insights into property pricing, trends, and factors influencing real estate in the region.

## Notebooks Overview

### Notebook 1: Basic Data Preprocessing
**Summary:** In this notebook, the primary focus was on performing basic data preprocessing tasks on the flats dataset. The following key steps were undertaken:
- **Duplicate Values Check:** Ensured the dataset was free from duplicate entries.
- **Missing Values Check:** Identified columns with missing values, noting that most columns had some missing data.
- **Column Dropping:** Removed unnecessary columns such as 'Link' and 'Property-id' which were not required for the analysis.
- **Univariate Analysis:** Conducted univariate analysis on every column to understand the distribution and basic statistics of each feature.

This notebook lays the groundwork for further data cleaning and analysis by ensuring the dataset is clean and well-understood.

### Notebook 2: Basic Data Preprocessing for Independent House Data
**Summary:** This notebook focuses on the basic preprocessing of the independent house dataset, similar to the flats data. The following steps were completed:
- **Duplicate Values Check:** Verified that there were no duplicate entries in the dataset.
- **Missing Values Check:** Identified missing values across most columns.
- **Column Removal:** Dropped the 'Link' and 'Property-id' columns, which were not needed for the analysis.
- **Univariate Analysis:** Performed univariate analysis on all columns to understand the distribution and basic statistics.

The outcome of this notebook is a cleaned version of the independent house data, saved as "house_cleaned.csv", ready for further analysis.

### Notebook 3: Merging Cleaned Datasets
**Summary:** In this notebook, the focus was on merging the cleaned datasets of flats and independent houses. The key steps undertaken include:
- **Loading Cleaned Data:** Imported the cleaned datasets for flats and independent houses.
- **Merging Datasets:** Combined both datasets into a single dataset to have a comprehensive view of properties.
- **New Dataset:** The merged dataset was saved as "gurgaon_properties.csv".

This step unified the data from different property types into one consolidated file, facilitating holistic analysis in subsequent steps.

### Notebook 4: Further Cleaning and Feature Extraction
**Summary:** In this notebook, further cleaning and feature extraction were performed on the final merged dataset. The following steps were completed:
- **Property Name Cleaning:** Removed extraneous words and numbers from "Property_name" to extract only the essential property name.
- **Sector Extraction:** Created a new column "Sector" by extracting sector information from the cleaned "Property_name".
- **Sector Name Imputation:** For entries where the sector name was missing but the colony name was available, the sector name was extracted from Google and replaced the colony name with the sector name.
- **Column Dropping:** Removed the unnecessary columns "Property_name", "address", "description", and "rating".
- **Export Cleaned Data:** The further cleaned dataset was saved as "gurgaon_properties_cleaned_v1.csv".

This notebook enhanced the dataset's quality by extracting meaningful features and removing redundant information, resulting in a more refined dataset for analysis.

### Notebook 5: Detailed Data Transformation and Feature Engineering
**Summary:** This notebook focuses on enhancing the dataset through detailed data transformation and feature engineering. Key steps include:
- **Area with Type:** Split "areaWithType" into three columns: "Super Built-up Area", "Built-up Area", and "Carpet Area". Standardized all area values to square feet.
- **Additional Room Encoding:** One-hot encoded additional room types (Servant, Pooja, Study, Store, Others).
- **Age Possession Categorization:** Classified "age possession" into categories: "New Property", "Relatively New", "Moderately Old", "Old Property", and "Under Construction".
- **Furnish Details:** Categorized into "furnished", "semi-furnished", and "unfurnished".
- **Luxury Score:** Created a "Luxury Score" feature.
- **Column Dropping:** Removed redundant columns after feature extraction.

The resulting dataset, saved as "gurgaon_properties_cleaned_v2.csv", is now more structured and informative for subsequent analysis.

### Notebook 6: Exploratory Data Analysis (EDA)
**Summary:** This notebook focuses on Exploratory Data Analysis (EDA) to understand the dataset's characteristics and identify key patterns and insights. The steps involved are:
1. **Univariate Analysis:** Analyzed each column to understand data distribution, missing values, and potential outliers.
   - **Society:** Top 75 apartments account for approximately 50% of the data.
   - **Sector:** 113 unique sectors, with 3 sectors having more than 100 listings.
   - **Price:** Median price is 1.52 crores, with significant positive skewness and high kurtosis indicating heavy tails and outliers.
   - **Price per sqft:** Median is around 9000 rupees, with notable outliers.
   - **Bedrooms:** 43.59% are 3 BHK, followed by 2 BHK and 4 BHK.
   - **Bathrooms:** 3 bathrooms are most common (31.73%).
   - **Balcony:** "3+ balconies" are most frequent (31.87%).
   - **Floor Number:** Most properties are on lower floors (1 to 4).
   - **Facing:** North-east and east-facing flats are most common.
   - **Age Possession:** 1600 properties are relatively new (2 to 3 years old).
   - **Super Built-up Area:** Median is 1828 square units with significant variability.
   - **Built-up Area:** Most properties range between 500 sq.ft and 3,500 sq.ft with outliers on the higher side.
   
2. **Pandas Profiling:** Conducted to cross-verify the univariate analysis and ensure consistency in findings.

3. **Multivariate Analysis:** Explored relationships between columns to detect multicollinearity and useful features for predictive modeling.

**Key Observations:**
- The dataset has a high concentration of listings in certain societies and sectors.
- Price distribution shows significant skewness and outliers.
- Data on floor numbers and facing directions have notable gaps and variability.

This EDA provided a comprehensive understanding of the data, which is crucial for feature selection and predictive modeling.

### Notebook 7: Exploratory Data Analysis (EDA) with Pandas Profiling
**Summary:** This notebook conducts an extensive exploratory data analysis using Pandas Profiling, generating an interactive report that summarizes the dataset's characteristics, including data types, missing values, correlations, and distributions. This provides valuable insights into the data's structure and informs subsequent analysis steps.

### Notebook 8: Multivariate Analysis of Property Data
**Summary:** This notebook conducts a multivariate analysis examining the relationships between property type and various factors, including price, area, price per square foot, and luxury score. Key visualizations include heatmaps and bar plots analyzing property characteristics and sector trends. Findings indicate that:
- Sectors 25, 26, and 27, owned by DLF, are the most expensive.
- Sectors 1 to 10, known as "old Gurgaon," have property prices ranging from 1 lakh to 2 crore.
- Newer sectors (above 70) tend to have lower prices due to ongoing development.

### Notebook 9: Outlier Treatment and Analysis
**Summary:** This notebook focuses on identifying and addressing outliers in key columns, including:
- Price
- Price per sqft
- Area
- Bedroom
- Bathroom
- Super Built-up Area
- Carpet Area
- Luxury Score

It also calculates the area/bedroom ratio to detect additional outliers. Outliers are tackled using logical reasoning to ensure data integrity and improve model performance, enhancing the overall quality of the dataset for further analysis.

### Notebook 10: Data Imputation and Handling Missing Values
**Summary:** This notebook addresses missing values in the dataset by filling the Built-up Area column using Super Built-up Area, Carpet Area, and Area, due to over 50% missing entries. Additionally, it identifies and addresses missing values in:
- Society (1 row)
- Floor Number (17 rows)
- Facing (1011 values)
- Undefined entries in Age Possession

This ensures data completeness for further analysis.

### Notebook 11: Feature Selection Techniques
**Summary:** This notebook applies eight feature selection techniques to identify key predictors of property prices:
1. **Correlation Analysis:** Reveals strong linear dependencies, particularly that Built-up Area and the number of bedrooms significantly influence price.
2. **Random Forest Feature Importance:** Indicates Built-up Area as the most important feature, highlighting its critical role in predictions.
3. **Gradient Boosting Feature Importance:** Functions similarly to Random Forest, reinforcing the importance of Built-up Area.
4. **Permutation Importance:** Evaluates feature significance by shuffling values; features with negative importance indicate a lesser impact on predictions.
5. **Lasso:** Identifies Built-up Area as the most significant feature while requiring feature scaling.
6. **Recursive Feature Elimination (RFE):** Iteratively removes features, consistently showing Built-up Area as the most important.
7. **Linear Regression Weights:** Provides feature importance, but is less reliable for this dataset due to encoding choices.
8. **SHAP (SHapley Additive exPlanations):** Offers a detailed understanding of each feature's contribution to predictions, emphasizing the importance of Built-up Area.

Overall, Built-up Area is identified as the most critical feature across various techniques, while some features show negative importance values, suggesting minimal impact on the target variable.

### Notebook 12: Model Training and Evaluation
**Summary:** In this notebook, after performing feature selection, One-Hot Encoding, Standard Scaling, and Log Transformation were applied through a Pipeline. Two models, Linear Regression and Support Vector Machine (SVR), were trained and evaluated:
- **Mean Absolute Error (MAE) for Linear Regression:** 0.64, indicating a prediction error of 64 lakhs. For example, if the actual property price is 1 crore, the model predicts 1.64 crores, showcasing significant deviation.
- **SVR:** Achieved a reduced MAE, improving predictions by 11 lakhs compared to Linear Regression, demonstrating better model performance for the dataset.

### Notebook 13: Model Selection and Finalization
**Summary:** This notebook is crucial for selecting the final model for deployment. Key steps include:
1. **Data Preprocessing:** Applied Ordinal Encoding to categorical columns and used a Column Transformer to standardize numerical features and encode categorical features.
2. **Model Evaluation:** Implemented K-fold cross-validation to assess model performance, with a focus on Mean Absolute Error (MAE). Linear Regression produced an MAE of 0.94, while tree-based models significantly outperformed linear models.
3. **Model Comparison:** Evaluated multiple models, including Linear Regression, SVR, and various tree-based models. The R² score improved to approximately 0.88, and MAE reduced from 0.94 to 0.50.
4. **Final Model Selection:** Extra Trees and Random Forest were identified as the best-performing models. Target Encoding was also applied for high cardinality features.
5. **Hyperparameter Tuning:** Tuned parameters for Random Forest and XGBoost to optimize performance.
6. **Pipeline Creation:** Developed a final pipeline for deployment using Random Forest with 500 estimators and exported the model and preprocessor as df.pkl and pipeline.pkl.

This process ensures a robust model ready for implementation in a web application.


