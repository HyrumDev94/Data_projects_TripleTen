# Model Comparison (Classification)  

**Goal:**  
Compare the performance of multiple classification models to predict user churn and identify the most effective algorithm.  

**Process:**  
- Prepared the dataset and split into train/test sets  
- Trained logistic regression, decision tree, and random forest models  
- Evaluated results using metrics: accuracy, precision, recall, F1, and ROC-AUC  
- Interpreted feature importance to explain model behavior  

**Result:**  
The Random Forest model achieved the highest overall performance, offering strong predictive accuracy and balanced precision-recall trade-offs.  

**Skills Used:** scikit-learn, pandas, machine learning, model evaluation, visualization  

**Files:**  
- `model_comparison.ipynb`

## View Project: [Notebook](https://github.com/HyrumDev94/Data_projects_TripleTen/blob/main/model_comparison/notebook-2.ipynb)


<img width="885" height="510" alt="Screenshot 2025-10-20 at 3 27 55 PM" src="https://github.com/user-attachments/assets/fd9ea803-8115-4e1e-a6ea-6c9894d82d25" />
<img width="887" height="563" alt="Screenshot 2025-10-20 at 3 28 16 PM" src="https://github.com/user-attachments/assets/8aaa5dc6-699a-40dc-86bf-a889ddbf18b0" />



## Future Improvements

- Apply hyperparameter tuning (GridSearchCV or RandomizedSearchCV) to further optimize model accuracy and reduce overfitting.  
- Add feature selection or dimensionality reduction (e.g., PCA or SelectKBest) to evaluate which features contribute most to model performance.  
- Deploy the trained model via a simple API endpoint or Streamlit app to make predictions interactively.  
- Incorporate cross-validation and ROC curve comparison for a more robust evaluation across multiple models.

