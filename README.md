# Evaluation of Applicants

This project evaluates the results of an exam taken by candidates who participated in selection processes to work for a company.

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

Also, if you want to use by your own, you will need to download PostgreSQL and create the file 'config.json' and replace the values there with yours, like this

<div style="background-color: #000000;font-size: 14px ;color: #FFFFFF; padding: 10px; border: 1px solid #ccc">
    <pre>
        {
            "POSTGRES_USER": "your_postgres_user",
            "POSTGRES_PASSWORD": "your_postgres_password",
            "POSTGRES_HOST": "host",
            "POSTGRES_PORT": your_port_number,
            "POSTGRES_DB": "your_database_name",
            "POSTGRES_TABLE": "the_name_of_the_table"
        }
    </pre>
</div>

Also, you must create a folder called 'data' and inside there, put the csv file with your dataset, and of course, change the neccesaries values in the notebooks (The path to the dataset, the name of the columns when you create the table, the values for the graphics).

## How use it

    1.  Run the ´Migration_Database.ipynb´ this will create a new database in PostgreSQL, create a new table and migrate the dataset to the new table.

    2.  With the information in the database, run the ´EDA.ipynb´ this will take the data in the table and bring to the notebook where the information will pass throught the EDA process.