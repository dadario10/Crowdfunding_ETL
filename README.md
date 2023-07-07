# Crowdfunding ETL Project
Brettney Chau-Dang and Dario Micucci 
----------------------------------
## Instructions
The instructions for this mini project are divided into the following subsections:
- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database

### Create the Category and Subcategory DataFrames
1. Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame that has the following columns:
    - A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories
    - A "category" column that contains only the category titles

2. Export the category DataFrame as category.csv and save it to this GitHub repository.

3. Extract and transform the crowdfunding.xlsx Excel data to create a subcategory DataFrame that has the following columns:
    - A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories
    - A "subcategory" column that contains only the subcategory titles

4. Export the subcategory DataFrame as subcategory.csv and save it to your GitHub repository.

### Create the Campaign DataFrame
1. Extract and transform the crowdfunding.xlsx Excel data to create a campaign DataFrame that has the following columns:
    - The "cf_id" column
    - The "contact_id" column
    - The "company_name" column
    - The "blurb" column, renamed to "description"
    - The "goal" column, converted to the float data type
    - The "pledged" column, converted to the float data type
    - The "outcome" column
    - The "backers_count" column
    - The "country" column
    - The "currency" column
    - The "launched_at" column, renamed to "launch_date" and with the UTC times converted to the datetime format
    - The "deadline" column, renamed to "end_date" and with the UTC times converted to the datetime format
    - The "category_id" column, with unique identification numbers matching those in the "category_id" column of the category DataFrame
    - The "subcategory_id" column, with the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame

2. Export the campaign DataFrame as campaign.csv and save it to this GitHub repository.

### Create the Contacts DataFrame
1. The creates DataFrame has the following columns:
    - The "contact_id" column
    - The "first_name" column
    - The "last_name" column
    - The "email" column

2. Export the contacts DataFrame as contacts.csv and save it to this Github repository
        
### Create the Crowdfunding Database
1. The database schema labeled crowdfunding_db_schema.sql was created 

2. A crowdfunding_db is created using the crowdfunding_db_schema.sql file 

3. Primary and Foreign keys are given to the appropriate columns

4. All CSV files is imported into the appropriate table 

5. The data from each table is displayed using a SELECT * statement

## Getting Started 
 - This project used Jupyter Notebook and Visual Studio to run the Python code. It also used "https://app.quickdatabasediagrams.com/#/d/VCaXwp" and pgAdmin4 to create tbales and export/import data into the appropriate tables to obtain the required information

## Acknowledgements
 - Jupyter Notebook
 - Visual Stupdio
 - pgAdmin4
 - "https://app.quickdatabasediagrams.com/#/d/VCaXwp"
 - with assistance from our Teaching Assistence, tutors, and fellow classmates
