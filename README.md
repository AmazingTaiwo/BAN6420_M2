# BAN6420_M2
BAN6420 - Module 2 Assignment

BAN6420: Programming in R & Python
Module 2 Assignment
Salary Function

Student Name: Taiwo Babalola
Learner ID: 162894

	Employee Salary Fubction

		This project is designed to process and analyze employee salary data, generate visualizations, and extract detailed information for individual employees. The script performs the following tasks:

		- Loads an employee salary dataset.
		- Inspects the data to provide summary statistics.
		- Allows querying of employee details by name.
		- Generates various visualizations.
		- Saves employee details into a CSV file and zips it for easy storage and sharing.



	Overview

		This project provides an easy-to-use script for analyzing employee salary data. It reads data from a CSV file, processes it, and offers the following features:

		1. Dataset Inspection: Information about the dataset, including rows and columns, and the first few rows.
		2. Data Cleaning: Converts certain columns to numeric types for consistent analysis.
		3. Salary Analysis: Provides descriptive statistics for key salary columns.
		4. Employee Query: A function to query employee details based on the employee's name.
		5. Visualizations: KDE plots for the distribution of pay and bar plots for salary trends.
		6. File Output: Employee details are saved in a CSV file and zipped for easier sharing.

	Requirements

	To run this script, you need to install the following libraries in your Python environment:
		- numpy
		- pandas
		- seaborn
		- matplotlib


	Data Preparation

		1. Clone or Download the Repository:
   			If this project is available on GitHub, clone it using:

  			 ```bash
   			git clone https://github.com/yourusername/employee-salary-processing.git
 			cd employee-salary-processing
  			 ```

		2. Place the CSV File: 
   			Ensure that the employee salary data file `emp_salary_data.csv` is in the same directory as the script or provide the correct path in the code.

		3. Ensure File Path is Correct: 
   			Update the path to the CSV file in the script if necessary, e.g., `df = pd.read_csv('emp_salary_data.csv')`.

	Usage

		1. Load and Inspect Data:
   			The script starts by loading the `emp_salary_data.csv` file into a pandas DataFrame and displaying some basic information about the dataset.

		2. Query Employee Details:
   			The `get_employee_details(EmployeeName)` function allows you to fetch details for a specific employee. Update the `EmployeeName` variable to the desired employee's name:

   			```python
   			EmployeeName = "VICTOR WYRSCH"
   			EmployeeName_details = get_employee_details(EmployeeName)
   			print(EmployeeName_details)
   			```

		3. Visualizations:
   			The script generates various plots to help visualize salary distributions and trends:
   			- KDE Plots for Total Pay and Base Pay.
   			- Bar Plot for Total Pay by Year.

		4. Generate Output Files:
   			After querying the employee details, the script generates:
   			- A CSV file containing the employee details.
   			- A ZIP file containing the CSV file, making it easy to store or share.

   			The files will be saved in a folder named after the employee, e.g., `VICTOR_WYRSCH_details.zip`.

		5. Run the Script:
   			You can run the script directly in your Python environment:

  			 ```bash
  			 python salary_function.py
  			 ```
  		Make sure the script is in the same directory as the `emp_salary_data.csv` file.


	Unzip the Employee Profile details
		1. Launch Rstudio App
		2. Download the BAN6420)m2.zip file and extract it
		2. Navigate to Open a file in the menu bar
		3. Navaigate to the just downloaded BAN6420_m2 R file and open it
		4. Run the file using the run button.
