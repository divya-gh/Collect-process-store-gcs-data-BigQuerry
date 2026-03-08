# Collect-process-store-gcs-data-BigQuerry
BigQuery Soccer Data Ingestion: Importing external sports data sources into BigQuery tables

# Objective : Upload files from Google Cloud Storage into BigQuery tables using the Cloud Console.
- Create database/dataset to store external data
- Ccreate custom Tables:  
  - Load data into the tables in the database
  - Methods:
    - LOAD JSON/CSV DATA - sql
    - Create Table console
    - Use Data Analytics Hub -From google cloud storage
- Query table
    -Check for:


1. Create database/dataset to store external data:
   - The dataset is used to add data to the project. Datasets utilize *tables and views* to help control access to data within a project.
   image

2. Load data into the tables in the database :
   - LOAD JSON DATA - sql:
   image
3. Create Table console:
   image

4. Preview tables:
image

##Querrying:
###  1. Query player data:
##### Top 10 tallest defenders (for whom height is available) in the players table.
image

### 2. Query events data:
#### Total count of all the event types found in the event table
image

#### 3. Total domestic leagues in the competitions table

CITATION: part of gc data analytics certification program.
