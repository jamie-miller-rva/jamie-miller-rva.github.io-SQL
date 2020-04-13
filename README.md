# jamie-miller-rva.github.io-SQL
This Repository is a postgresql demonstration where I was asked to create a Corporate Employee Database having six tables (one each for the six csv files provided). I was asked to conduct data analysis using SQL commands and add visual analysis using Pandas and matplotlib.

Key elements of my work:
  - Created a postgresql database named Employee_db_2
  - Created a schema.sql file to create six tables (department, dept_emp, dept_manager, employees, salaries and titles) from the six csv files provided in the data folder. Note the inclusion of the open and from commands to import the six csv files (after the tables are created).
  - Created a queries.sql file to answer the eight questions raised as part of this project. Note for each question I was asked to answer, I created a View to hold the answer in the postgresql database.
  - Imported the SQL database into Pandas (in Jupyter Notebook) using SQLAlchemy and create a histogram of common salary ranges for employees and a barchart of average salary by title.
  
