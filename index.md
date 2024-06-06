---
layout: default
title: My Work experience
description: QA testing and technical writing
---
Over 10 years in the software quality assurance industry,
I gained experience in testing and documenting.

### Projects I was involved testing:

## 1 Google Assistent (e2e) testing


| Feature        | Regression | Triage | Comparison<br>(deepDives) | Dogfood |
|:-------------|:---------------------------------|:------|:--------------------------|:------|
| Actions(Date Questions)           | DONE                             | DONE  | DONE                      | DONE  |
| My Day(DaylyBrief)                | DONE                             | DONE  | DONE                      | DONE  |
| Actions(Device Questions)         | DONE                             | DONE  | DONE                      | DONE  |
| Music(providers, Youtube. Spotify, Pandora)           | DONE                             | DONE  | DONE                      | DONE  |
| News(Sports, NPR)                 | DONE                             | DONE  | DONE                      | DONE  |
| Remote Casting( Youtube, Netflix) | DONE                             | DONE  | DONE                      | DONE  |
| Actions( Misc)                    | DONE                             | DONE  | DONE                      | DONE  |
| Radio, Podcast( Questions)        | DONE                             | DONE  | DONE                      | DONE  |
| Productivity Actions( Allarm, Timer, Reminder)        | DONE                             | DONE  | DONE                      | DONE  |
| Answers(Nutrition. Pronounce, Spelling, Web answers)  | DONE                             | DONE  | DONE                      | DONE  |
| Personal Answers(Calendar. Photos, Flights, and more) | DONE                             | DONE  | DONE                      | DONE  |

```
* Contributed massively to the Google Assistent triage playbook.
* Created the handbooks for 
  * onboarding, 
  * flashing Google Assistent, 
  * writing bugreports, 
  * and so on.
```

## 2 Google Assistent with wearables (verification testing)
  - Headphones,
  - Watches,
  - Loudspeakers, and more

## 3 Alexa  (verification testing)
  - Screens,
  - Monitors,
  - Loudspeakers,
  - Headphones,
  - Watches, and more

## 4 Google Embedded infotainment system
  - GM,
  - Ford,
  - Volvo,
  - and more

## 5 Fitbit
- [update in progress]

## 6 Pixel 5G power performance testing

| Feature        | 12V device| 8V device| Triage | 
|:-------------|:------------------|:------|:------|
| AirplaneRockbottom          | DONE | DONE  | DONE  |
| Bouncy Ball                 | DONE | DONE  | DONE  |
| Chrome Browsing Wifi        | DONE | DONE  | DONE  |
| Chrome Browsing scroll      | DONE | DONE  | DONE  |
| GFX                         | DONE | DONE  | DONE  |
| Keepress OOB                | DONE | DONE  | DONE  |
| LocalYoutube Music          | DONE | DONE  | DONE  |
| Partial Wakelock            | DONE | DONE  | DONE  |
| Photos (4K60FPSH265)        | DONE | DONE  | DONE  |
| Photos (AVI)                | DONE | DONE  | DONE  |
| Photos (MFC)                | DONE | DONE  | DONE  |
| Static Display              | DONE | DONE  | DONE  |
| Youtube Wifi                | DONE | DONE  | DONE  |
| Youtube stream              | DONE | DONE  | DONE  |

- Pixel-thermal (99 degC)
- Power Stats (mWs of Cellular, Modem, CPU, etc)
    - Core >> Wake Lock
    - System > Foreground or App Wakeups
    - Hardware
        - Brightness
        - GPS (Signal Quality)
        - Audio
    - Battery
        - Plugged
        - Charging
    - Connectivity
        - Phone signal
        - Mobile Radio
        - Data connection
        - Conn Change
    - Wifi
        - Wifi scan
- Data connectivity
- Cellular network type
- Cellular Rx signal strength
- Wifi Rx signal strength
- Wifi app scan
- Kernel Wakeup reasons
- CPU Usage by App
- Mobile Radio Activity per app
- App Wakeup Alarms


### My Guideline
I use in my Playbooks, Handbooks, and Userguides following perspectives as guideline:
- the logical sequence to get things done.
- the step by step approach that allows any user to accomplish goals.
- readability, readability, readability!

***

## Last project related to programming and database management: 
- Use Python and SQL together to manage databases, perform data analysis, and build data-driven applications.

Breakdown of the essential skills: 

## Python Skills:

### Basic Python Programming:
- [x] Understanding of Python syntax and basic constructs (variables, loops, functions, etc.).
- [x] Familiarity with data structures like lists, dictionaries, and tuples.

### Libraries for Database Interaction:
- [x] SQLite: sqlite3 module.
- [x] MySQL: mysql-connector-python or PyMySQL.
- [ ] PostgreSQL: psycopg2.
- [ ] SQLAlchemy: An ORM (Object Relational Mapper) for Python.

### Data Manipulation and Analysis:
- [x] Pandas: For data manipulation and analysis.
- [x] NumPy: For numerical operations.
- [x] Matplotlib/Seaborn: For data visualization.

### File Handling:
- [x] Reading from and writing to CSV, Excel, and other file formats.

### Exception Handling:
- [x] Managing exceptions and errors that occur during database operations.

--

## SQL Skills:

### Basic SQL Commands:
- [x] SELECT, INSERT, UPDATE, DELETE.
- [x] CREATE, ALTER, DROP tables.

### Advanced SQL Queries:
- [ ] Joins (INNER, LEFT, RIGHT, FULL).
- [ ] Subqueries and nested queries.
- [x] Aggregate functions (SUM, AVG, COUNT, etc.).
- [x] Grouping and sorting results.

### Database Design:
- [ ] Normalization and database schema design.
- [x] Understanding primary keys, foreign keys, and indexes.

### Transaction Management:
- [ ] BEGIN, COMMIT, ROLLBACK.

### Stored Procedures and Functions:
- [80%] Creating and using stored procedures and user-defined functions.

--

## Integrating Python with SQL:

### Connecting to a Database:
- [x] Establishing a connection to the database from Python.
- [x] Understanding connection parameters (host, port, database name, user, password).

### Executing SQL Queries from Python:
- [x] Using cursor objects to execute SQL commands.
- [x] Fetching results from executed queries (e.g., fetchone(), fetchall()).

### Data Insertion and Retrieval:
- [x] Inserting data into tables from Python.
- [x] Retrieving and processing data within Python.

### Data Cleaning and Transformation:
- [x] Cleaning and transforming data before inserting it into the database.
- [50%] Using Python for ETL (Extract, Transform, Load) processes.

### Automating Database Tasks:
- [ ] Automating routine database tasks and maintenance using Python scripts.

--

## Practical Application:

### Building a Sample Project:
- [x] Combining Python and SQL skills to build a sample project, such as a simple web application, data analysis tool, or a data pipeline. (so far 1 project: EV market in Germany and the US)

### Debugging and Optimization:
- [%50] Debugging database connectivity issues.
- [ ] Optimizing SQL queries for better performance.

## Example Workflow:

- [x] Connect to Database:

```python
import sqlite3
conn = sqlite3.connect('example.db')
cursor = conn.cursor()
```

- [x] Create a Table:

```python
cursor.execute('''
CREATE TABLE IF NOT EXISTS employees (
    id INTEGER PRIMARY KEY,
    name TEXT NOT NULL,
    salary REAL
)
''')
conn.commit()
```

- [x] Insert Data:

```python
cursor.execute('''
INSERT INTO employees (name, salary) VALUES (?, ?)
''', ("John Doe", 60000))
conn.commit()
```

- [x] Fetch Data:

```python
cursor.execute('SELECT * FROM employees')
rows = cursor.fetchall()
for row in rows:
    print(row)
```

- [x] Close Connection:

```python
    conn.close()
```

--

- [x] mastering these skills
- [ ] mastering these skills not yet


***

| Handbook                             | status                |
|:-------------------------------------|:----------------------|
| [Link to Selenium_Java page]     | Done |
| [Link to Selenium_Python page]   | Done |


* <a href="https://knowledgebase4testers.github.io/" target="_blank" rel="noopener noreferrer">My Glossary</a> 
* <a href="https://trumpfheller.github.io/" target="_blank" rel="noopener noreferrer">My QA Playbook</a> 
