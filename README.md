1. EDA & Feature Engineering Notebook
   File: Abb_case_study_prakhar_finalSubmission.ipynb and abb_case_Prakhar_finalSubmission.py
   Includes data loading, preprocessing, EDA, feature engineering and model building.
    
      Missing value treatment for Item_Weight and Outlet_Size
      
      Feature creation (Outlet_Age)
      
      Label encoding of categorical features
      
      Initial visualizations: item type distributions, sales vs. outlet type
      
      Scaling and PCA with variance retention check
    
2. Modeling Notebook
     
    Linear Regression (baseline RMSE)
    
    Random Forest (with GridSearchCV and parameter tuning)
    
    Neural Network (with EarlyStopping and Dropout)
    
    Stacked model approach (documented as less effective)


3. Approach Note

  Problem Solving Approach:
    Started with Exploratory Data Analysis to understand variable distributions and relationships.
    
    Performed missing value imputation and created a new feature Outlet_Age.
    
    Tried Linear Regression as a baseline which resulted in high RMSE.
    
    Implemented Random Forest with grid search but performance plateaued even with increased estimators.
    
    Switched to Neural Networks which showed better generalization and lower RMSE.
    
    Attempted stacking ensemble methods but did not yield significant improvements.
    
    Applied StandardScaler and PCA (retaining 95% variance), which enhanced neural network performance further.
    
    Final submission was made using the model with the lowest RMSE.

4. Screenshot of Best Rank & Score
![abb_case_rank_screenshot](https://github.com/user-attachments/assets/bb982f32-50e1-4984-8859-1c8c703e93f7)
