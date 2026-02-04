# DMQL-project


## 📊 Olympic Games Relational Database & Analytics Project

This project focuses on **designing, normalizing, and querying a relational database** for the Olympic Games dataset to analyze historical trends in athlete participation, events, host cities, and medal distributions across countries and years.

The dataset was decomposed from a large CSV into **well-structured relational tables**, ensuring **data integrity, reduced redundancy, and efficient querying** using SQL. The project also includes a **web-based interface** to display query results.

---

### 🔍 Project Objectives

* Analyze **Olympic Games history** and country-wise performance
* Track **athlete participation** across events, sports, and years
* Identify **medal trends**, popular sports, and participation patterns
* Apply **database normalization (BCNF)** for optimal schema design
* Improve query performance using **indexing**

---

### 🗂️ Database Design

* Designed detailed **ER diagrams**
* Identified **primary keys and foreign keys**
* Normalized tables to **Boyce–Codd Normal Form (BCNF)**
* Final schema includes:

  * Athletes Profile
  * Participation
  * Events
  * Sports
  * Hosts
  * Medals
  * Country / NOC regions

---

### 🛠️ Technologies Used

* **SQL** (schema creation, joins, aggregation, indexing)
* **PostgreSQL / Relational DB concepts**
* **Python** (data handling & backend logic)
* **Flask** (web application)
* **HTML** (frontend display)
* **CSV datasets**
* **Jupyter Notebook** (SQL experimentation)

---

### 📈 Key Analyses & Queries

* Medal count by country and year
* Athlete participation across **Summer & Winter Olympics**
* Most popular sports by number of participants
* Average age of medalists per Olympic Games
* Events with highest athlete participation
* Performance comparison before and after **indexing**

---

### 👥 Target Users

* Sports Analysts
* National Olympic Committees
* Coaches & Trainers
* Sports Enthusiasts & Researchers

---

### 📁 Repository Contents

* Normalized CSV tables (`athletes_profile`, `participation`, `events`, `sports`, `hosts`, `medals`)
* SQL queries and indexing examples
* ER diagrams and IEEE-format project report
* Flask-based web application (`app.py`)
* HTML frontend (`index.html`)

---

### 👩‍💻 Team Contributions

* **Pallavi Thupakula**: ER design, key relationships, web application, result visualization
* **Kavya Elemati**: Schema creation, normalization, SQL queries, indexing, report
* **Ruchitha Kota**: Dataset research, cleaning, SQL query development

