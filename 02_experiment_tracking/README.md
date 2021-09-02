## 2. Experiment versioning (tracking)

Discuss how we could track the model based on the v2 notebook.
Track by saving metrics to txt. => But this only tracks model performance. 
When we have many versions -> readability. What about env?

**Objectives:**
 
- Demonstrate how experiment tracking helps with linking the code, the results and the environment details. 
- Pay attention about how this increases the reproducibility.

Dependencies:

- script: `wine_linear_regression.py` 

**Instructions:**

1. Connect to [Databricks Community Edition](https://community.cloud.databricks.com/login.html) and create your account
2. Start the cluster
3. Upload the script
4. Install `mlflow` to the cluster
5. Modify the script to track the model metrics
6. Test the different parameters of the model
7. Change the model to Random Forest
8. Track some more experiments and compare the results

**External links:**

- article [Experiment tracking with MLflow on Databricks Community Edition](https://www.adaltas.com/en/2020/09/10/databricks-community-edition-mlflow/)
- article [MLflow tutorial: an open source Machine Learning (ML) platform](https://www.adaltas.com/en/2020/03/23/mlflow-open-source-ml-platform-tutorial/)
