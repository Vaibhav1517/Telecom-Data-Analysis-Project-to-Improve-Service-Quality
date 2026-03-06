# Telecom-Data-Analysis-Project-to-Improve-Service-Quality
The telecommunications industry is a rapidly growing sector that is constantly evolving to meet the demands of consumers. As technology advances and user behavior changes, telecom operators face a variety of challenges that can impact their business success. In order to stay competitive and meet customer needs, it is important for telecom companies to regularly analyze their data to identify relevant problems and opportunities for improvement.

The aim of this project is to explore the telecom data and find relevant problems faced by telecom operators. By conducting an exploratory data analysis (EDA) on a large volume of telecom data, we can gain valuable insights into user behavior, network performance, customer demographics, and more. Through this analysis, we hope to identify potential areas for improvement, such as  improving customer satisfaction, optimizing network performance and increasing revenue through targeted marketing efforts.

The insights gained from this project can help telecom operators make informed decisions about their business strategy, enabling them to better meet the needs of their customers and stay competitive in the market. 



## **Approach**

* Univariate Data Analysis:
    * Create histograms to visualize the distribution of the variables related to the hypotheses.
    * Use countplots to compare the frequencies of different categorical variables with respect to the hypotheses.
    * Create box plots to visualize the median, quartiles, and outliers of the continuous variables with respect to the hypotheses.


* Bivariate Data Analysis:
    * Create scatter plots to investigate the relationship between two continuous variables related to the hypotheses.
    * Create box plots to compare the distributions of the continuous variables with respect to the categorical variables related to the hypotheses.
    * Chi-Square Test and ANOVA:
        * Perform the chi-square test to evaluate the relationship between two categorical variables related to the hypotheses.
        * Use ANOVA to evaluate the difference in means between two or more groups related to the hypotheses.

* Multivariate Data Analysis:
    * Use correlation analysis to investigate the strength and direction of the relationship between multiple continuous variables related to the hypotheses.


* Project Summary:
    * Analyze the results obtained from the above tests to draw conclusions about the hypotheses.
    * Provide recommendations to improve customer satisfaction and retention based on the findings.



## **Execution Instructions**



### **Installation and Setup for IPYNB**

For the best experience, please stay connected to the internet while executing this Project

#### **Running an IPYNB on Google Colab**:

* Open the [Google Colab website](https://colab.research.google.com/).
* Click on the "New Notebook" button.
* Click the "File" menu in the new notebook and choose "Upload notebook."
* Select the IPYNB file(notebooks/telco_data_analysis.ipynb) you want to upload.
* Once the file is uploaded, click on the "Runtime" menu and choose "Run all" to execute all the cells in the notebook.
* Alternatively, you can execute each cell individually by clicking the "Play" button next to the cell OR by pressing `"shift” + "enter"`.
* The Default version of Python that Colab uses currently is 3.8

#### **Python setup steps for Local Machine**:
* If you're using a local machine and do not have Python installed, follow these steps to set up Python:
* Download and install the latest version of Python from the official Python website: https://www.python.org/downloads/.
* Once the installation is complete, open a command prompt/terminal and type the following command to check if Python is installed `python –-version`
* If Python is installed, the version number will be displayed.
* This Project has been created using **Python version 3.8.10**

#### **Setting up a Python Virtual Environment on Windows**

* Open a command prompt by pressing `Windows Key + R`, type `cmd`, and press `Enter`.
* Navigate to the directory where you want to create the virtual environment.
* Install virtualenv by running the command in the command prompt `pip install virtualenv`
* Create a new virtual environment by running the command `virtualenv env`
* This will create a new directory called `env`, containing the virtual environment.
* Activate the virtual environment by running the command `env\Scripts\activate`
* You can now install packages and work on your project within this virtual environment.
* To deactivate the virtual environment, simply run the command `deactivate`

#### **Setting up a Python Virtual Environment on Mac**

* Open the Terminal by pressing `Command + Spacebar`, type `Terminal`, and press `Enter`.
* Navigate to the directory where you want to create the virtual environment.
* Install virtualenv by running the following command in the terminal `pip install virtualenv`
* Create a new virtual environment by running the following command `virtualenv env`
* This will create a new directory called `env`, containing the virtual environment.
* Activate the virtual environment by running the following command `source env/bin/activate`
* You can now install packages and work on your project within this virtual environment.
* To deactivate the virtual environment, simply run the following command `deactivate`

#### **Setting up a Python Virtual Environment on Linux**

* Open the Terminal by pressing `Ctrl + Alt + T`.
* Navigate to the directory where you want to create the virtual environment.
* Install `virtualenv` by running the following command in the terminal `sudo apt-get install python3-virtualenv`
* Create a new virtual environment by running the following command `virtualenv -p python3 env`
* This will create a new directory called `env`, containing the virtual environment.
* Activate the virtual environment by running the following command `source env/bin/activate`
* You can now install packages and work on your project within this virtual environment.
* To deactivate the virtual environment, simply run the following command `deactivate`

#### **Installing Jupyter with pip**
If pip is installed on your local machine, you can install Jupyter. 

Here are the steps:
* Open the command prompt (Windows) or terminal (Mac/Linux).
* Install Jupyter with pip by running the following command `pip install jupyter`
* Launch Jupyter Notebook by running the following command `jupyter notebook`

#### **Installing Jupyter with Conda**

* Download and install Anaconda from the official website: https://www.anaconda.com/products/individual.
* Open the Anaconda Navigator App and launch Jupyter Notebook 
* Running IPYNB in Jupyter Notebook
* Open Terminal / Command Prompt and Navigate to the notebooks directory using cd
* Launch Jupyter Notebook by running the following command jupyter notebook
* This will open a browser window displaying the Jupyter interface.
* Click on the IPYNB file you want to open.
* To execute all the cells in the notebook, click on the "Cell" menu and choose "Run all".
* Alternatively, you can execute each cell individually by clicking on the "Play" button next to the cell.



# Executing the project via Modular Code
1. Install the dependencies using the command, navigate to the **Telecom Data Analysis Project to Improve Service Quality** directory where the requirements.txt file exists, and run ***pip install -r requirements.txt*** in the terminal/CMD.
2. Run the jupyter notebook "telco_data_analysis.ipynb" present in the notebooks folder.

3. Note: As this is an exploratory data analysis project, the analysis work is primarily done in the Jupyter notebook. Therefore, we have not created separate modular source codes for this project. Please use the project structure to run the codes in the Jupyter notebook accordingly.
    

![eda_project_structure.png](data:image/png;base64,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)











	


## **Data Reading from Different Sources**









### **Files**

In many cases, the data is stored in the local system. To read the data from the local system, specify the correct path and filename.

### **CSV Format**
Comma-separated values, also known as CSV, is a specific way to store data in a table structure format. The data used in this project is stored in a CSV file. Download the data for the project.


Use following code to read data from csv file using pandas. 
```
import pandas as pd
csv_file_path= "D:/ProjectPro/Telecom-Data-Analysis/data/raw_telecom_data.csv.csv"
df = pd.read_csv(csv_file_path)
```
With appropriate csv_file_path, pd.read_csv() function will read the data and store it in df variable.
 
If you get *FileNotFoundError or No such file or directory*, try checking the path provided in the function. It's possible that python is not able to find the file or directory at a given location.


### **Colab - CSV Format**

```
# mount the google drive
from google.colab import drive
drive.mount('/content/drive')
csv_file_path= '/content/drive/MyDrive/project_pro/Telecom Data Analysis Project to Improve Service Quality/raw_telecom_data.csv.csv'
df = pd.read_csv(csv_file_path)
```

### **AWS S3 - CSV**
Use the S3 public link to read the CSV file directly into a pandas DataFrame
```
s3_link = 'https://s3.amazonaws.com/projex.dezyre.com/telecom-data-analysis-project/materials/raw_telecom_data.csv'
df = pd.read_csv(s3_link)
```

### **Database**
Most organizations store their data in databases such as MS SQL. Microsoft SQL Server (MS SQL) is a relational database management system developed by Microsoft. A BAK file in Microsoft SQL Server is a backup file that contains a copy of a SQL Server database at a specific point in time. It is essentially a binary representation of the database and includes all its data, tables, schema, indexes, stored procedures, and other objects.

#### **Installing MS SQL Management Studio**
To install Microsoft SQL Server Management Studio, you can follow these steps:

* Go to the Microsoft SQL Server Downloads page (https://www.microsoft.com/en-us/sql-server/sql-server-downloads) and click on the "Download now" button for the version of SQL Server Management Studio that you want to install.
* Follow the instructions on the screen to download the installation file to your computer.
* Once the download is complete, locate the installation file and double-click on it to start the installation process.


#### **Restore a BAK file in MS SQL**

* Open SQL Server Management Studio and connect to the SQL Server instance to which you want to upload the BAK file.
* Right-click on the Databases folder in the Object Explorer pane and select "Restore Database..." from the context menu.
* In the "Restore Database" dialog box, select the "Device" option under the "Source" section.
* Click on the "..." button to open the "Select backup devices" dialog box.
In the "Select backup devices" dialog box, click on the "Add" button to add the BAK file that you want to upload.
* In the "Locate Backup File" dialog box, browse to the location where the BAK file is stored in the Telecom Data Analysis Project to Improve Service Quality directory under the ‘data’ folder, select the file, and click on the "OK" button.
* Back in the "Select backup devices" dialog box, the BAK file you added should now be listed under "Backup media:".
* Click on the "OK" button to close the "Select backup devices" dialog box.
In the "Restore Database" dialog box, you should see the BAK file listed in the "Backup sets to restore" section.
* By default, the original database name and file locations from the BAK file will be used. If you want to restore the database with a different name or to a different location, you can modify the "To database" and "Restore as" options under the "General" section.
* Click the "Options" tab for additional restore options.
* If you want to overwrite an existing database with the same name, you can select the "Overwrite the existing database (WITH REPLACE)" option under the "Restore options" section.
* Click on the "OK" button to start the restore process.
* Once the restore process is complete, you should see a message indicating that the restore was successful.

#### **Read Data from DB to Python**
 The data can be accessed by secret credentials, which will be in the following format.
```
import pyodbc
import pandas as pd
connection = pyodbc.connect('DRIVER={ODBC Driver 17 for SQL Server};\
                       SERVER=server_name;\
                       PORT=1433;\
                       DATABASE=database_name;\
                       UID=admin;\
                       PWD=password')
```
#### **Steps to install ODBC driver**
* Go to the Microsoft Download Center page for the ODBC Driver 17 for SQL Server: https://www.microsoft.com/en-us/download/details.aspx?id=56567
* Select the download button that corresponds to the operating system you are using.
* Select the language you want to use for the installer, then click the download button.
* Once the download is complete, run the installer.
* Accept the license terms, then select the features you want to install.
Choose a location to install the driver, or use the default location.
* Complete the installation process by following the instructions provided by the installer.
* Once the installation is complete, you can use the ODBC Driver 17 for SQL Server to connect to SQL Server databases from applications that support ODBC connectivity.

#### **Query to read the data into Pandas**

```
query = '''select * from raw_month_1_data
           UNION ALL
            select * from raw_month_2_data
            UNION ALL
            select * from raw_month_3_data
            UNION ALL
            select * from raw_month_4_data
            UNION ALL
            select * from raw_month_5_data
            UNION ALL
            select * from raw_month_6_data
            UNION ALL
            select * from raw_month_7_data
            UNION ALL
            select * from raw_month_8_data
            UNION ALL
            select * from raw_month_9_data
            UNION ALL
            select * from raw_month_10_data
            UNION ALL
            select * from raw_month_11_data
            UNION ALL
            select * from raw_month_12_data
            UNION ALL
            select * from raw_month_13_data
            UNION ALL
            select * from raw_month_14_data'''
raw_data = pd.read_sql(query,connection)

```
