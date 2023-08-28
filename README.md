# IOD_mini_project2
Summary of project: [IOD_mini_project2](IOD_mini_project2.pdf)

This mini project encapsulate modules 4-6:
   - Git Version Control
   - Environment Management
   - Data Retrieval
   - Data Preprocessing
   - SQL Database Integration
   - Exploratory Data Analysis (EDA)
   - Model exploration and build (Regression,Classification,Clustering)
   - Conclusion and Reporting

Project intructions: (Follow these steps to reproduce the code and results)

1. Dependencies:
   - Download [requirements](requirements.txt) file for the full list of dependencies used in this project
   - Use command line `pip install -r <downloadpath>/requirements.txt` to install dependencies

2. Data Retrieval and SQL Database setup:
   - Download and open jupyter notebook [Project_Dependencies](Initialization/Project_Dependencies.ipynb) for details on the dependencies used for this project
   - Download and open jupyter notebook [Database_Integration](Initialization/Database_Integration.ipynb) for details on data retrieval and storage done for this project
   - Read data from [project_db](Database/project.db) to skip data retrieval and storage step
   
3. Model exploration and build:
   - Download and open jupyter notebook [Task1_Regression](Task1_Regression/Task1_Regression.ipynb) for details regression model exploration and build done for this project
   - Download and open jupyter notebook [Task2_Classification](Task2_Classification/Task2_Classification.ipynb) for details classification model exploration and build done for this project

| Files         | Description   | Type |
| ------------- | ------------- | ------------- |
| [IOD_mini_project2](IOD_mini_project2.pdf) | Summary of the project which includes visualizations and key findings | PDF file |
| [requirements](requirements.txt) | Dependency requirements used for this project | Text file |
| [Project_Dependencies](Initialization/Project_Dependencies.ipynb) | Steps on project dependencies | Jupyter Notebook |
| [Database_Integration](Initialization/Database_Integration.ipynb) | Steps on data retrieval and storage | Jupyter Notebook |
| [Task1_Regression](Task1_Regression/Task1_Regression.ipynb) | Steps on regression model exploration and building | Jupyter Notebook |
| [Task2_Classification](Task2_Classification/Task2_Classification.ipynb) | Steps on classification model exploration and building | Jupyter Notebook |
| [project_db](Database/project.db) | Database used for data storage | Sqlite db file |
| [housing_profiling](Task1_Regression/housing_profiling.html) | Profiling report done during EDA | HTML |
| [healthcare_profiling](Task2_Classification/healthcare_profiling.html) | Profiling report done during EDA | HTML |
| [healthcare-dataset-stroke-data](Initialization/healthcare-dataset-stroke-data.csv) , [housing](Initialization/housing.csv) , [marketing_campaign](Initialization/marketing_campaign.csv) | Downloaded data files from kaggle | csv |
| [reg](ML_models/reg.pkl) , [ridgeCV](ML_models/ridgeCV.pkl) , [lassoCV](ML_models/lassoCV.pkl) , [LogRegCV](ML_models/LogRegCV.pkl) , [MNB](ML_models/MNB.pkl) , [randf_clf](ML_models/randf_clf.pkl) | Pickle file of trained models | pkl |
