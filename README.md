Chronic Liver Disease Risk Assessment with Machine Learning
This project focuses on utilizing advanced machine learning techniques to predict and assess the risk of chronic liver disease (CLD). The study aims to enhance early detection and improve patient outcomes by leveraging predictive models.

Group Members
Imtiaj Uddin Ahamed
Department of Computer Science
University of South Dakota
imtiajuddin.ahamed@coyotes.usd.edu

Abdullah Al Rakin
Department of Computer Science
University of South Dakota
abdullahal.rakin@coyotes.usd.edu

Mohammad Navid Nayyem
Department of Computer Science
University of South Dakota
mohammadnavid.nayyem@coyotes.usd.edu

Md Azad Hossain Raju
Department of Computer Science
University of South Dakota
mdazadhossain.raju@coyotes.usd.edu

Project Description
Chronic liver disease poses significant global health challenges, often advancing unnoticed until severe stages. By using machine learning models, this project aims to predict the presence and progression of liver disease based on patient data, enabling early diagnosis and intervention.

Key Features
Dataset: The project uses the Indian Liver Patient Dataset (ILPD) from the UCI Machine Learning Repository.
Algorithms: Techniques like Random Forest, XGBoost, Logistic Regression, and Ensemble Learning (Stacking and ExtraTrees) were applied to achieve high accuracy and robustness.
Preprocessing: Includes label encoding, feature scaling, and dimensionality reduction (PCA) to prepare the dataset for machine learning.
Optimization: Hyperparameter tuning through Bayesian Optimization was performed to enhance model performance.
Performance
The best-performing model in the study was the Bayesian Optimized ExtraTrees Classifier, achieving:

Accuracy: 97.3%
Precision: 98.31%
Recall: 96.5%
ROC-AUC: 99.7%
Repository Structure
Code Files: Contains all the Python scripts used for data preprocessing, model training, evaluation, and visualization.
README: Overview of the project, methods, and team members (this file).
References: Comprehensive list of references for the methodologies and data sources.
Installation & Usage
Clone the repository.
Ensure Python and required libraries (listed in requirements.txt) are installed.
Run the scripts sequentially to reproduce the results.
References
Primary Dataset: ILPD - UCI Machine Learning Repository
