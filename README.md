As a core data engineers bootcamp participant, i have been tasked to design and implement a dimensional model that was previously designed. After several discussions, the team has decided to use dbt for the transformation layer. 

# Tasks: 

# Step 1: Develop a Dimensional Model (This has been done)

# Step 2: Prototype Using Seed Data

Since real data is not yet available, you are asked to generate synthetic data. You can use

Python’s Faker library or a GenAI tool to generate this data. The generated data will serve as

seeds for your dbt project.

# Step 3: Implement dbt Models

● Sources: Create source models for the raw data tables, ensuring you define freshness

tests for your sources.

● Staging Models: Implement staging models that map 1:1 with the source tables and

apply only light transformations (e.g., renaming columns, casting data types).

● Intermediate Models (Optional): If needed, create intermediate models to further refine

the data before feeding it into the final models.

● Dimensional Models: Build dimension and fact models based on your business

process.

# Step 4: Add Tests and Documentation

● Add generic and custom tests (e.g., uniqueness, non-null constraints, accepted values)

to your models to ensure data quality.

● Document each of your models.

# Step 5: Automate User Access Requests

Currently, a user (joseph) needs access to new tables/models after they are created. He

manually contacts the team for access. How can access be given to this user after each dbt

execution?

# Note:

I can use dbt core or dbt cloud
