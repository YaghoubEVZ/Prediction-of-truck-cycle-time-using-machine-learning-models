# Prediction-of-truck-cycle-time-using-machine-learning-models

**Project Overview** 

This project focuses on predicting truck productivity within a copper open-pit mining operation using machine learning. By analyzing critical transportation metrics, this project aims to optimize cycle times and enhance overall productivity. The dataset includes 43 entries across 20 columns, capturing various operational metrics, such as haul and return times, load and dump durations, queue times, and travel distances.  

**Business Understanding**  
In mining operations, maximizing truck productivity is essential for reducing operational costs and improving efficiency. Truck cycle times directly impact the mine’s output, and unoptimized cycles can lead to significant delays, fuel costs, and maintenance expenses. The goal is to provide predictive insights into truck productivity, enabling better planning and decision-making in the transportation processes, ultimately supporting enhanced resource management and cost control.  

**Data Understanding**  
The dataset consists of various features related to truck cycles, including:
- **Numerical Variables**: `Return_Time`, `Haul_Time`, `Cycle_Time`, `Productive_Cycle`, `Total_Distance`, etc.
- **Categorical Variables**: Loading and dumping locations, truck types, and material categories.

Initial data preprocessing included removing irrelevant columns, such as `Spot_Load_Time (s)` and `Dump_Time (s)`, renaming for clarity, and addressing missing values. An exploratory data analysis (EDA) was conducted to assess distributions and relationships among variables. A correlation matrix helped identify the strength of relationships between features, assisting in feature selection.  

The selected variables were then used to train several machine learning models—Linear Regression, Decision Tree, Random Forest, and Gradient Boosting—to predict truck productivity, with model performance evaluated using MAE, MSE, and R-squared scores. The final model provides an actionable tool for predicting truck productivity, supporting optimized transport operations in open-pit mining.
