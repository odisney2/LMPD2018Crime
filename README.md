# Orris J. Disney II
# Python/SQL project for spring 2019

# LMPD2018Crime

This shows the number of crimes documented by the LMPD in 2018

This project was an attempt to answer the following question:

  "In 2018, how many crimes has been reported in Louisville Metro Police Department LMPD monthly?"

## The data gathered for this project is the monthly count for the following items:

  a. Crimes happening in Louisville, ky in 2018
  
## 1. The following steps of this project:

  a.  Download/create the one csv file
  
    - Daily crime report from LMPD
    
    
  b.  Create a database only if it is not already created or connect to the database if it already exists.  The name of the database is 2018CrimeData2.db.   It's created in the same folder as the python program and the one CSV file.
  
  c.  In the SQLite database, import the data from the one csv files into one table:
        
      - If the tables already exist, they will be deleted to prevent importing duplicate csv files into the same table
      
      - Once the table is created, the data will be imported
  
  d. Once the import is completed, a printout of the data in the one table is displayed. The printout will confirm that the data was correctly imported from the CSV file to the sqlite database table.
  
  e.  Create a query that Groups the data via each month and count the crime that happened during that month.  
        
  f.  Data results are graphed using matplotlib.
  
## 2.  Dependencies:

  a. sqlite3
  
  b. csv
  https://data.louisvilleky.gov/dataset/crime-reports
  c. matplotlib.pyplot
  
  d. panda 

## 3.  Make sure the following files in the same folder:

  a.  LMPD_Crimes.ipynb

  b.  Crime_Data_2018.csv.csv
  
  
Please reach out to me if you found any issues or have any questions.  

Thanks.


References:

1.Daily Crime being reported for 2018
  https://data.louisvilleky.gov/dataset/crime-reports
  
2.  Help from mentors with the programming and the wording in my README.md.   Thank you!



