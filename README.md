# Batch-Data-Engineering-Project-
Building of a batch processing based data architecture for a data-intensive application, executed as follows: 
Researchers from a network of hospitals seek to investigate the average billing amount for patients admitted to an hospital within the network.
The project is focused on the hospital and the billing amount listed on the date of discharge for each patient.
Reading the data from a CSV files https://www.kaggle.com/datasets/prasad22/healthcare-dataset?select=healthcare_dataset.csv. The ingested data from the CSV file containings billing amount data for patients admitted to hospitals in the network enters a ETL pipeline.
The data is processed, aggregating the billing amounts to a monthly average per hospital after which the processed data is loaded to a database.
The algorithm K-Means clustering, is utilized on the processed data. 
Labels are added to the processed data that reveals the category of the billing amount for each hospital, this labeled data is then loaded per quarter to the database. 
The data both processed and categorized is visualized via HTML webpages. 
