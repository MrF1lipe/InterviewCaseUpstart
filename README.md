Steps of the project:

1 - First run CATALOG _CREATION.ipynb to create the environment, with catalog, schemas, volumes and tables

2 - Run the Bronze/BRONZE_CSV_LOADING.ipynb to fill the raw tables

3 - Run the Silver/SILVER_CSV_PROCESSING.ipynb to fill the store tables

4 - Run the Gold/GOLD_CSV_TRANSFORMATIONS.ipynb to fill the publish tables

5 - Run the Gold/GOLD_CSV_ANALYTICS.ipynb to see the answers to analytics questions of the case
