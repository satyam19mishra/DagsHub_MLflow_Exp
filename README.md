# DagsHub_MLflow_Exp
# What is DagsHub 
    DagsHub is a platform for data scientists and machine learning engineers to version their data, models, experiments, and code.
# Features of DagsHub that will leave you awestruck.
    1. Comparison of ML metrics
    2. Data version control
    3. Track ML experiments
    4. ML flow integration and pipeline visualization
    5. DVC and Git integration
    6. Label Annotation via The Label Studio and others.
# What is Mlflow
    MLflow is an open-source platform for managing machine learning workflows. It is used by MLOps teams and data scientists. MLflow has four main components:
    
    1. The tracking component allows you to record machine model training sessions (called runs) and run queries using Java, Python, R, and REST APIs.
    2. The model component provides a standard unit for packaging and reusing machine learning models.
    3. The model registry component lets you centrally manage models and their lifecycle.
    4. The project component packages code used in data science projects, ensuring it can easily be reused and experiments can be reproduced.
    
    There are two other key concepts in MLflow:
    1. A run is a collection of parameters, metrics, labels, and artifacts related to the training process of a machine learning model.
    2. An experiment is the basic unit of MLflow organization. All MLflow runs belong to an experiment. For each experiment, you can analyze and compare the results of different runs, and easily retrieve metadata artifacts  
       for analysis using downstream tools. Experiments are maintained on an MLflow tracking server hosted on Azure Databricks.
# For Mlflow to integrate with DagsHub You will need 
    1. MLFLOW_TRACKING_URI= < you will get it from dagshub when you connect your GitHub repo to dagshub >
    2. MLFLOW_TRACKING_USERNAME=< you will get it from dagshub when you connect your GitHub repo to dagshub >
    3. MLFLOW_TRACKING_PASSWORD=< you will get it from dagshub when you connect your GitHub repo to dagshub >

# Screenshot of this Project In DagsHub and MLflow
   # 1. DagsHub repo
![Screenshot (125)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/0cc8db7f-3ed1-43cb-a29f-97f93a7af00c)
   # 2. DagsHub Experiments - 1
![Screenshot (120)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/ab1a0bea-cc98-424b-b787-81dd73db83ca)
   # 3. DagsHub Experiments - 2
![Screenshot (121)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/61399a55-8e38-4481-8b96-c9dc55a84280)
   # 4. DagsHub Experiments - 3
![Screenshot (122)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/efe89e56-0804-43fd-9181-82f6debc1e23)
   # 5. DagsHub Mlflow - 4
![Screenshot (116)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/962789eb-c1cc-47af-b891-6b400cd29547)
   # 6. DagsHub Mlflow - 5
![Screenshot (117)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/28fe831b-c721-4a33-9a3b-c3c21a098248)
   # 7. DagsHub Mlflow - 6
![Screenshot (118)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/bb1df2e8-3a40-46a9-9e11-f28a055a1bdf)
   # 8. DagsHub Mlflow - 7
![Screenshot (119)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/20a06039-1b93-49d0-92b3-fb393139e29d)
   # 9. DagsHub Mlflow - 8
![Screenshot (123)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/887ea1a4-fc48-4de6-9ab0-55e34397e66f)
   # 10. DagsHub Mlflow - 9
![Screenshot (124)](https://github.com/satyam19mishra/DagsHub_MLflow_Exp/assets/103360091/31e6301e-d015-4203-8129-7df171222a13)
