# Hospital Wait List Analysis:
This project provides an end-to-end data etl and visualization of hospital wait list data

## 📝 Table of Contents
- [Dashboard](#dashboard)
- [Setup & Requirements](#-setup--requirements)
- [Usage](#-usage)
- [Notes](#-notes)


## Dashboard
![Summary](images/Summary.png)
![Detail](images/Detail.png)

## 🛠 Setup & Requirements
1. **Knowledge requirements**: Python, SQL, Data Modeling, PowerBI.
2. **Python Libraries**: Install the required Python libraries with the `requirements.txt`.

## 🚀 Usage
1. **Data**: Data for project can found in `Data` directory.
2. **Connection to a database server**: A database server is needed either cloud or local on computer (local Postgres database server is used in this project).
3. **ETL**: ETL process of extracting, transform and load data into database is done in `etl.ipynb`. 
4. **Data modeling**: 
- ![Data Modeling](images/data_modeling.png)
5. **Visualization**: Dashboard file named `dashboard.pbix` for the project can be found in `Dashboard` directory.

## 📝 Notes
- Constraints for tables created in database and Dax code to create a date table in PowerBi data model can be found in `helper.txt`

