# Evaluation of Applicants

This project shows how to perform extraction, transformation, and loading (ETL) of candidate data using Python and PostgreSQL. It includes tasks such as connecting to a PostgreSQL database, creating tables, importing data from CSV files, and performing basic SQL operations. It also includes exploratory data analysis and visualization to gain a better understanding of the data and the candidate sourcing process.

## About the datase

The dataset contains 50.000 rows of candidates information and these 10 columns:

    -   First Name
    -   Last Name
    -   Email
    -   Country
    -   Application Date
    -   Years of Expirience (YOE)
    -   Seniority
    -   Technical Interview Score
    -   Code Challenge Score

## Libraries Instalation

The libraries needed to run the project are listed in 'requeriments.txt', you can install them using a package manager such as pip and run the next command:

<div style="background-color: #000000;font-size: 14px ;color: #FFFFFF; padding: 10px; border: 1px solid #ccc">
    <pre>
        pip install - r requeriments.txt
    </pre>
</div>

It's recommended that you enable the digital environment (venv) and run the command to conserve your PC's resources.
However, you can run the command without using the environment just once and continue using the project without any problems.

## Content

You will find the following files and folders in the repository:

1. Migration_Database: This Jupyter notebook contains the connection to the PostgreSQL database and the creation of the table that will contain the dataset.

2. EDA: This file contains the EDA process applied to the dataset.

3. requirements: This file contains the information about the libraries that will be used.

4. dashboard: This is the final dashboard.

5. notebooks: This contains the notebooks that will be used to analyze the data set.

## How use it

1.  Clone the repository using the command:

<div style="background-color: #000000;font-size: 14px ;color: #FFFFFF; padding: 10px; border: 1px solid #ccc">
    <pre>
        git clone "https://github.com/DaviMartinez0423/Workshop_ETL"
    </pre>
</div>

2.  Run the ´Migration_Database.ipynb´ this will create a new database in PostgreSQL, create a new table and migrate the dataset to the new table.

3.  With the information in the database, run the ´EDA.ipynb´ this will take the data in the table and bring to the notebook where the information will pass throught the EDA process.