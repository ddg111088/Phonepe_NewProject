# Phonepe_NewProject

Data Visualization and Exploration A User-Friendly Tool Using Streamlit and Plotly Phone Pe

### Want to see demo video of my project? - [Click here](https://www.linkedin.com/feed/update/urn:li:ugcPost:7062018049565949952/)

# What is PhonePe Pulse?

The [PhonePe Pulse website](https://www.phonepe.com/pulse/explore/transaction/2022/4/) is an impressive showcase of the digital payment habits of India's consumers. It presents a fascinating interactive map that highlights over 2000+ Crore transactions, reflecting PhonePe's significant 45% market share. The website offers valuable insights on the nation's payment trends, drawing from a comprehensive analysis of PhonePe's transaction data and informative interviews with both merchants and customers.

The report is an excellent resource for anyone interested in understanding the landscape of digital payments in India, and it is available for free download on both the [PhonePe Pulse website](https://www.phonepe.com/pulse/explore/transaction/2022/4/) and [GitHub](https://github.com/PhonePe/pulse).

# Libraries/Modules needed for the project!

1.	pandas - A data manipulation library used for data analysis and cleaning.
2.	mysql.connector - A module that provides an API for connecting to MySQL databases.
3.	streamlit - A web framework used for building interactive web applications with Python.
4.	plotly.express - A library for creating interactive and visually appealing plots and charts.
5.	os - A module providing a way of using operating system dependent functionality.
6.	json - A module used for working with JSON data.
7.	csv - A module for working with CSV files.
8.	streamlit_option_menu - A module used for creating dropdown menus in Streamlit.
9.	PIL - The Python Imaging Library, used for opening, manipulating, and saving many different image file formats.
10.	subprocess - A module for working with additional processes(To clone the GitHub repository).

# workflow
# Step 1: Clone the Github repository

You can use the subprocess.run command to clone the Phonepe Pulse Github repository. For example, you can run the following command in your terminal:
subprocess.run(["git", "clone", "https://github.com/PhonePe/pulse.git"])

# Step 2: Data cleaning and pre-processing

Once you have cloned the repository, you can use Python and its libraries like Pandas to clean and pre-process the data. Transforming the data into a suitable format for analysis and visualization. 

# Step 3: Insert data into a MySQL database

Next, you can use the mysql-connector-python library to connect to a MySQL database and insert the transformed data using SQL commands. You can create a new database, create a table, and insert the data into the table using the Python script


# Step 4: Create a live geo-visualization dashboard

You can use the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard. You can use Plotly's built-in geo map functions to display the data on a map and Streamlit can be used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.

# Step 5: Fetch data from the MySQL database

You can use the mysql-connector-python library to connect to the MySQL database and fetch the data into a Pandas dataframe. You can use the data in the dataframe to update the dashboard dynamically.

# Step 6: Deployment

Once you have created the dashboard, you can test it thoroughly and deploy it, making it accessible to users. 

# Learning outcomes

By completing this project, you will gain hands-on experience with data extraction, processing, and visualization, as well as experience working with databases, dashboards, and web development. You will also learn how to develop a comprehensive and user-friendly solution, from data extraction to dashboard deployment. You will also learn how to test and deploy the solution to ensure it is secure, efficient, and user-friendly.






