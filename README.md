# Movies-ETL
### Overview of the analysis:
Load and refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and perform the ETL process by adding the data to a PostgreSQL database.

### Processes:
- Deliverable 1: Write an ETL Function to Read Three Data Files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle Data
- Deliverable 4: Create the Movie Database with two tables

### Results:
Deliverable 1 to get three dataframes

    1. wiki_movies_df 

  ![image](https://user-images.githubusercontent.com/103073631/172075356-d749f595-7c2a-4d4d-9c30-e6ed86199852.png)
    
    2. kaggle_metadata

  ![image](https://user-images.githubusercontent.com/103073631/172075368-f936143b-1f11-4668-9560-1f703b63bc02.png)

    3. ratings
  
  ![image](https://user-images.githubusercontent.com/103073631/172075378-a2cad9a7-d413-48b9-9ead-e2ec14177f87.png)

  Deliverable 2 and 3 : clean and transform the Wikipedia data, Kaggle and rating data
  
  Deliverable 4: Connect Pandas and SQL & Load the data to a PostgreSQL Movie Database
  
  - Table Movies has 6052 rows
   
   ![image](https://user-images.githubusercontent.com/103073631/172075692-6177cd42-b246-489f-82b4-0eed34a12f13.png)

- Table Ratings has 26,024,289 rows

   ![image](https://user-images.githubusercontent.com/103073631/172075717-f9e47c2f-8659-46ec-a570-19a78bf2af63.png)
