# 🌤️ Weather Data Analysis with Python
We analyze a **Weather Dataset** and answer multiple questions using data exploration and statistical methods.

---

## 📁 Project Files

* **`Weather Dataset.csv`** — The raw weather data used for analysis
* **`Weather_project_Pandas.ipynb`** — The Jupyter Notebook with all the analysis and answers

---

## 📌 Objectives

You will learn how to:

* Explore a dataset using Pandas
* Use common Pandas functions and attributes
* Apply logical conditions to filter data
* Calculate descriptive statistics
* Perform real-world data analysis

---

## 🧠 Commands Used

| Command          | Description                                          |
| ---------------- | ---------------------------------------------------- |
| `head()`         | Shows the first N rows (default N=5)                 |
| `shape`          | Shows number of rows and columns                     |
| `index`          | Gives the index (row labels) of the DataFrame        |
| `columns`        | Shows the names of all columns                       |
| `dtypes`         | Shows data type of each column                       |
| `unique()`       | Shows unique values in a column                      |
| `nunique()`      | Shows count of unique values in each column          |
| `count()`        | Shows total number of non-null values                |
| `value_counts()` | Shows unique values with their counts (for a column) |
| `info()`         | Provides basic information about the DataFrame       |

---

## ❓ Questions Solved

1. Find all the unique **Wind Speed** values in the data.
2. Find the number of times when the **Weather is exactly Clear**.
3. Find the number of times when the **Wind Speed was exactly 4 km/h**.
4. Find out all the **Null Values** in the data.
5. Rename the column **Weather** to **Weather Condition**.
6. What is the **mean Visibility**?
7. What is the **Standard Deviation of Pressure**?
8. What is the **Variance of Relative Humidity**?
9. Find all instances when **Snow** was recorded.
10. Find all instances when **Wind Speed is above 24** and **Visibility is 25**.
11. Find the **Mean value of each column** against each **Weather Condition**.
12. Find the **Minimum & Maximum value of each column** against each **Weather Condition**.
13. Show all the records where **Weather Condition is Fog**.
14. Find all instances when **Weather is Clear or Visibility is above 40**.
15. Find all instances when

    * A. **Weather is Clear and Relative Humidity > 50**
    * OR
    * B. **Visibility is above 40**

---

## 🚀 How to Run the Project

1. Clone this repository

   ```bash
   git clone <https://github.com/ShilpaMehla123/Weather_Analysis_Python.git>
   cd Weather_Analysis_Python
   ```
2. Open the Jupyter Notebook

   ```bash
   jupyter notebook Weather_project_Pandas.ipynb
   ```
3. Run the notebook cells to see the analysis and answers.
---

## 📊 Output

* Descriptive statistics for each weather parameter
* Filtered datasets answering the listed questions
* Insights into weather conditions, wind speed, visibility, humidity, and pressure

---

