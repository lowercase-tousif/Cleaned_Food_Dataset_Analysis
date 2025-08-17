# Food Data Analysis Projects 🍲

A collection of beginner-friendly data analysis projects exploring a global food dataset. This repository is for practicing and showcasing basic data analysis and visualization skills using Python.


## 📊 About the Dataset

This repository uses the `cleaned_food_data.csv` dataset, which contains information about 100+ dishes from around the world. The key columns in the dataset include:

* **Food Name:** The name of the dish.
* **Country/Region:** The origin country of the dish.
* **Calories:** Calorie count per serving.
* **Category:** The category of the dish (e.g., Main Course, Snack, Dessert).
* **Preparation Time:** Time required to prepare the dish (in minutes).
* **Popularity Rank:** A rank indicating the popularity of the dish.


## 🚀 Projects

Here are the projects included in this repository:

### 1. Basic Statistical Analysis (প্রাথমিক ডেটা বিশ্লেষণ)
* **Goal:** To understand the basic statistics and distribution of the data.
* **Techniques:** Used descriptive statistics (`.describe()`) and created histograms and bar charts to visualize the distribution of calories, preparation time, and the number of dishes per country and category.

### 2. Global Cuisine Calorie Analysis (গড় ক্যালোরি অনুযায়ী দেশ র‍্যাঙ্কিং)
* **Goal:** To find out which countries have the highest average calorie count in their dishes.
* **Techniques:** Grouped the data by country (`.groupby()`), calculated the mean calories, sorted the results, and visualized the top 10 countries using a bar chart.

### 3. Preparation Time vs. Popularity (প্রস্তুতির সময় বনাম জনপ্রিয়তা)
* **Goal:** To investigate if there is a relationship between how long a dish takes to prepare and how popular it is.
* **Techniques:** Used a scatter plot (`scatterplot()`) to visualize the correlation between `Preparation Time` and `Popularity Rank`.



## 🛠️ Tools and Libraries Used

* **Language:** Python
* **Libraries:**
    * [Pandas](https://pandas.pydata.org/): For data manipulation and analysis.
    * [Matplotlib](https://matplotlib.org/): For creating static, animated, and interactive visualizations.
    * [Seaborn](https://seaborn.pydata.org/): For making statistical graphics more attractive and informative.


## 💻 How to Run the Projects

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/lowercase-tousif/Cleaned_Food_Dataset_Analysis
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Cleaned_Food_Dataset_Analysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run any project's Python script:**
    ```bash
    python project--name.py
    ```

---
