# Batch-Data-Engineering-Project
Building of a batch processing based data architecture for a data-intensive application, driven by: 
Researchers from a network of hospitals seeking to investigate the average billing amount for patients admitted to an hospital within the network.
The project is focused on the hospital and the billing amount listed on the date of discharge for each patient, more precisely to investigate the average bill amount by medical condition and hospital for insight into how the hospitals in the network are charging for various medical conditions.
Reading the data from a CSV file https://www.kaggle.com/datasets/prasad22/healthcare-dataset?select=healthcare_dataset.csv. The ingested data from the CSV file containings billing amount data for patients admitted to hospitals in the network enters a ETL pipeline.
The data is processed, aggregating the billing amounts to a monthly average per hospital after which the processed data is loaded to a database.
The algorithm K-Means clustering, is utilized on the processed data. 
Labels are added to the processed data that reveals the category of the billing amount for each hospital, this labeled data is then loaded per quarter to the database. 
The data both processed and categorized is visualized via HTML webpages. 
Upon completion of phase one (outlined above) phase two (excepted from this project is initiated to:
A- Average the billing amount by insurance providers.
B- Total the billing amounts by quarter.

# Project Architecture
![Project_DE_Architecture](https://github.com/user-attachments/assets/892e2c17-5fe1-4cad-b202-f6535c9ff453)

# Documentation
Each Component
-ETL Process
-ML Process
-Visualization
Fitted with ReadMe documentation outlining the details of the execution process.

