# Non-Graded Challenge

_Non-graded challenge is designed for practice based on the tasks that have been assigned._

---

## Non Graded Challenge 1 : Python Syntax, Variables, and Data Type

### Task #1

Given list of customer_id that doing transaction in 1 day:
   customer_id = ['B818', 'A461', 'A092', 'A082', 'B341', 'A005', 'A092', 'A461','B219', 'B904', 'A901', 'A083', 'B904', 'A092', 'B341', 'B821','B341', 'B821', 'B904', 'B818', 'A901', 'A083', 'B818', 'A082','B219', 'B219', 'A083', 'A901', 'A082', 'B341', 'B341', 'A083','A082', 'B219', 'B439', 'A461', 'A005', 'A901', 'B341', 'A082','A083', 'A461', 'A083', 'A901', 'A461', 'A083', 'A082', 'A083','B341', 'A901', 'A082', 'A461', 'B219', 'A083', 'B818', 'B821','A092', 'B341', 'A461', 'A092', 'A083', 'B821', 'A092']
   
How many unique customer_id from above list?

### Task #2

Given list of:
   Data = [1, 4, 9, 16, 25, 36, 49,  64, 81, 100]
   
Use indexing so you can get this output:
   1. 16
   2. [36, 49, 64, 81]
   3. [100, 81, 64, 49, 36, 25, 16, 9, 4, 1]

### Task #3
Given a dictionary of:
   provinsi = {'Nanggroe Aceh Darussalam': 'Aceh',
               'Sumatera Selatan': 'Palembang',
               'Kalimantan Barat': 'Pontianak',
               'Jawa Timur': 'Madiun',
               'Sulawesi Selatan': 'Makassar',
               'Maluku': 'Ambon'}
   
What python command can be use to:
   1. Get list of keys available in dictionary
   2. Change 'Jawa Timur' value from 'Madiun'  to 'Surabaya'

---

## Non Graded Challenge 2 : Python Function, Conditional, and Loop

### Task #1 - Number of Word

**Create a function that count the number of word in a sentence.**
**Instruction:**
   1. Create function called `number_of_word`.
   2. This function takes 1 input, `sentence`.
   3. Inside this function, you can utilize `.split()` method to split the sentence into list of word(s).
   4. Also, `len()` function to count the element inside a list.
   5. Return the number of word from the sentenc?

**Example:**
   - Input: number_of_word(sentence = ’Hello World!’)
   - Output: 2
   
   - Input: number_of_word(sentence = ’Once Upon a Time in a faraway land’)
   - Output: 84


### Task #2 - Find Multiple

**Create a function that will get list of number(s) from a certain range that multiples of given number.**

**Instruction:**
   1. Create function called `find_multiples`.
   2. This function takes 3 input: `start_range`, `end_range`, and `multiple`.
   3. From every number within the given range, check if that number is the mutliples of `multiple`.
   4. Return list of the possible multiple number(s).
   
**Example:**
   - Input: find_multiple(start_range= 1, end_range= 20, multiple= 5)
   - Output: [5, 10, 15, 20]

   - Input: find_multiple(start_range= 1, end_range= 50, multiple= 10)
   - Output: [10, 20, 30, 40, 50]

### Task #3 - Grade Converter

**Create a function that will convert student’s grade to GPA.**

**Instruction:**
   1. Create function called `Grade_Converter`.
   2. This function takes input: `convert_to` and n-paired of student(s) name with its respective score.
   3. Input argument for `**convert_to**` is either `**letter_grade**` or `**gpa**`.
   4. You can utilize **kwargs input argument to generate n-length paired of student(s) name with its respective score (Dictionary).
   5. This function will return dictionary of student’s name along with converted Letter Grade or GPA, depending on user input in `convert_to` parameter
   
| Score Range | Letter Grade | GPA 4.0 Scale |
|-------------|--------------|---------------|
| 85 - 100    | A            | 4.0           |
| 70 - 84.99  | B            | 3.6           |
| 60 - 69.99  | C            | 2.5           |
| 50 - 59.99  | D            | 1.5           |
| 40 - 49.99  | E            | 1.0           |
| 0 - 39.99   | F            | 0.0           |

**Example:**
   - Input: Grade_Converter(convert_to='gpa', Adam=62, Faiz=91)
   - Output: {'Adam': 2.5, 'Faiz': 4}
   
   - Input: Grade_Converter(convert_to='letter_grade', Albert=90, Dwi=82, Syahdan=58, Veronica=84)
   - Output: {'Albert': 'A', 'Dwi': 'B', 'Syahdan': 'D','Veronica': 'B'}

---

## Non Graded Challenge 3 : OOP and Exception HandlingFTDS Phase 0 - Week 1
### task
Create a library catalog system using OOP. The system should allow users to add books to the catalog, search for books by title or author, and remove books from the catalog.
Requirements:
   1. Each book should have a title, author, and unique identifier
   2. The system should provide the following functionality:
      - Adding a book to the catalog.●Searching for books by title or author.
      - Removing a book from the catalog.
      - Displaying all books in the catalog.
   3. Do the exception handlin

---

## Non Graded Challenge 4 : Testing
### Task 
Do unit testing for a library system from the previous NGC

---

## Non Graded Challenge 5 : DDL & DML
### Task
- You are asked to create a customer and order table as follows "Customers" and "Orders". Determine the right datatype to create the two tables. Here are the structures and data for both tables:

| customer_id | customer_name | city |
|-------------|--------------|---------------|
| 1  | John Doe         | New York           |
| 2  | Jane Smith       | Los Angeles        |
| 3  | David Johnson       | Chicago        |

| order_id | customer_id | order_date | total_amount |
|-------------|--------------|---------------|--------|
| 1  | 1      | 2022-01-10        | 100.00 |
| 2  | 2      | 2022-02-15        | 150.00 |
| 3  | 3      | 2022-03-20        | 200.00 |
| 4  | 4      | 2022-04-25        | 50.00  |

- Once you have successfully created both tables, create a query to retrieve the total number of orders made by each customer along with the customer name from the "Customers" and "Orders" tables. Expected Output:

| customer_name | total_orders |
|-------------|--------------|
| John Doe         | 2          |
| Jane Smith       | 1          |
| David Johnson    | 1          |

---

## Non Graded Challenge 6 : Basic Data Wrangling in SQL
### DATA
You will use austin_bikeshare dataset from Google BigQuery Public Dataset. For example, you can change the following syntax:
```from google.colab import auth from google.cloud import bigqueryimport pandas as pdauth.authenticate_user()project_id = "your_project_id"client = bigquery.Client(project=project_id)# put your query herequery = """SELECT*FROM`bigquery-public-data.austin_bikeshare.bikeshare_trips`'"""# Set up the queryquery_job = client.query(query).to_dataframe()query_job```

### TASK
Create a query to answer the following questions:
   - How many tables are in the austin_bikeshare dataset?
   - How many columns in the bikeshare_stations table have STRING data?

Create a query to filter data based on the following conditions:
   - Retrieve all trips where the bike_id is not null and the duration is greater than 1000 minutes.
   - Filter trips where the trip_id is "Walk Up" and the end_station_name  is "Stolen".

---

## Non Graded Challenge 7 : Data Wrangling in SQL
### TASK
You are a Data Scientist who works for the Ministry of Law and Human Rights in a department that deals with patent archives. Your supervisor wants to see the cumulative number of patents related to cancer on an annual basis in the ministry database with condition :
   - the patent was registered in 2012 to 2023
   - the patent contains the keyword "data mining"
   
Display the cumulative number of patents sorted by largest year and smallest month

### DATA
To answer this question, you will use dataset from Google BigQuery.
   1. Log in to Google Cloud Console and select Google BigQuery.
   2. In the Google BigQuery search bar, please type “patents”. You will see the result as shown beside.
   3. Under patents-public-data, you will use dataset with name uspto_oce_cancer and table publications

### OUTPUT
Below is the expected output from your query. The query will output 12 entries of data.

| Row | year | month | total_patent |
|-------------|--------------|---------------|--------|
| 1  | 2014      | 4        | 1 |
| 2  | 2014      | 12       | 1 |
| 3  | 2013      | 3        | 1 |
| 4  | 2013      | 8        | 2 |
| 5  | 2013      | 11       | 1 |
| 6  | 2012      | 1        | 3 |
| 7  | 2012      | 2        | 1 |
| 9  | 2012      | 4        | 1 |
| 8  | 2012      | 6        | 3 |
| 10 | 2012      | 10       | 3 |
| 11 | 2012      | 11       | 1 |
| 12 | 2012      | 12       | 1 |

---

## Non Graded Challenge 8 : DDL, DML, and Basic DQL
### Dataset
You can access the data here:
https://github.com/FTDS-learning-materials/phase-0/raw/main/src/data_ngc.csv4

### TASK
This Non-Graded Challenge is done in notebook format with several mandatory criteria as follows:
   1. The library used is Pandas.
   2. The project is considered complete and ready for assessment if, when "Run All" is executed in the notebook, all cells successfully run to the end.
   3. The notebook's content should follow the outline below:
      - Introduction
         > The introduction section must contain the identity, background of the problem, and the problem statement to be discussed.
      - Import necessary libraries
         > The first cell in the notebook must contain and only contain all the libraries used in the project.
      - Data Loading
         > This section contains the queries that have been created and the data loading process, followed by simple data exploration.
      - Data Cleaning
         > This section contains the data preparation process, such as data cleaning, before further data exploration. The cleaning process may include assigning new names to each column, filling in missing values, deleting unused columns, and so on.e.
      - Data Exploration
         > This section contains data exploration on the dataset above using queries, grouping, and so on.
      - Conclusion
         > In this final section, there must be conclusions that reflect the results obtained by comparing them with the problem statement written in the introduction section.

---

## Non Graded Challenge 9 : Web Scraping
### Task 1
Scrape coins price from https://coinmarketcap.com/ with following requirements:
   - Scrape up to 1000 coins
   - Including Price, Market Cap, Volume, and Coin supply
   - Save into Pandas DataFrame and then save into excel or csv file

### Task 2 
- Get weather data from 54 locations in Indonesia from https://www.timeanddate.com/weather/indonesia. You should include the information of:
   > Temperature
   > Feels Like
   > Wind Speed
   > Wind Direction
   > Humidity
   > Dew Point
   > Visibility
   > Probability of Rain
   > Amount of Rain
- Only take the closest day and time (morning/evening) from the time you do this task
- Save into Pandas DataFrame and then save into excel or csv file

---

## Non Graded Challenge 10 : API
### Task 1 
- Create an API using FastAPI to provide weather data for different locations. Implement HTTPException to handle errors, and add API Key authentication for secure access.
- Assume we have a dictionary containing weather data for three locations: "New York City," "Los Angeles," and "Chicago." Each location has temperature and weather condition information.
- Create a FastAPI app and define two endpoints:
   > Endpoint 1: /weather/{location}
   This endpoint will provide weather data for a specific location.
   > Endpoint 2: /authenticate
   This endpoint will handle API Key authentication.
- Use HTTPException to handle cases where the requested location is not available in the weather_data dictionary.

---

## Non Graded Challenge 11 : Practical Statistics
### Task 1 
**The "Top 10000 Spotify Songs - ARIA and Billboard Charts" is a comprehensive collection of 10,000 of the most popularsongs that have dominated the music scene from 1960 to the present day.You can get the Data** [here](https://raw.githubusercontent.com/DianCA26/Dataset/main/top_10000_1960-now.csv)
   1. Get the Measures of the Central Tendency and Measures of Variation from data “Top 10000 Spotify Songs”. Measurethe popularity based on the year. Comment on the results.

### TASK 2
   1. Conduct the hypothesis testing from data “Top 10000 Spotify Songs” to check whether the Popularity of Britney Spearsand Taylor Swift is statistically different by using a 0.05 significance level to evaluate the null and alternativehypotheses. Before doing hypothesis testing, check the related assumptions. Comment on the results.

