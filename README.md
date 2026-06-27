# ✈️ Flight Price Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on a Flight Price dataset to understand the factors affecting airline ticket prices. The notebook includes data cleaning, feature engineering, handling missing values, and preparing the dataset for machine learning.

---

## 📌 Project Objective

The objective of this project is to:

- Understand the structure of flight booking data
- Clean and preprocess the dataset
- Extract useful features from date and time columns
- Handle missing values
- Encode categorical variables
- Prepare the dataset for predictive modeling

---

## 📂 Dataset Features

The dataset contains information such as:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Checked dataset shape and preview

### 2. Data Exploration
- Dataset information
- Summary statistics
- Data types
- Missing value inspection

### 3. Feature Engineering

#### Date Column
Extracted:
- Day
- Month
- Year

Dropped the original `Date_of_Journey` column.

#### Arrival Time
Extracted:
- Arrival Hour
- Arrival Minute

Dropped the original `Arrival_Time` column.

#### Departure Time
Extracted:
- Departure Hour
- Departure Minute

Dropped the original `Dep_Time` column.

#### Duration
Extracted:
- Duration Hours
- Duration Minutes

Handled missing hour/minute values using regular expressions.

---

### 4. Missing Value Handling

- Identified missing values in `Total_Stops`
- Filled missing values with `1 stop`
- Converted stop categories into numerical values

Example:

| Category | Value |
|----------|------|
| non-stop | 0 |
| 1 stop | 1 |
| 2 stops | 2 |
| 3 stops | 3 |
| 4 stops | 4 |

---

### 5. Data Cleaning

Removed unnecessary columns such as:

- Route
- Date_of_Journey
- Arrival_Time
- Dep_Time

---

### 6. Encoding Categorical Variables

Applied One-Hot Encoding on:

- Airline
- Source
- Destination

using Scikit-learn's `OneHotEncoder`.

---

## 📈 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Missing Value Treatment
- Date & Time Processing
- Categorical Encoding
- Data Preprocessing
- Pandas Operations
- Regular Expressions
- Machine Learning Data Preparation

---

## 📁 Project Structure

```
Flight-Price-EDA/
│
├── EDApractise.ipynb
├── flight_price.xlsx
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Perform detailed data visualization
- Detect and handle outliers
- Correlation analysis
- Feature importance analysis
- Train Machine Learning models for flight price prediction
- Hyperparameter tuning

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Real-world dataset preprocessing
- Feature extraction from date and time columns
- Handling missing values
- Encoding categorical variables
- Preparing structured data for machine learning

---

## 👨‍💻 Author

**Umar Farooq**

B.Tech Computer Science (AI & ML)

Interested in:
- Data Analytics
- Machine Learning
- Python Development
- Data Science

---
