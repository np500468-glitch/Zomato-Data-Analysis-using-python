# 🍽️ Zomato Data Analysis


## 📌 Project Overview

This project focuses on analyzing the Zomato restaurant dataset using Python to explore restaurant ratings, restaurant types, customer votes, online ordering, and approximate costs for two people.

The analysis uses data manipulation, statistical exploration, and data visualization techniques to understand patterns and gain insights from restaurant data.

## 🎯 Objectives

- Explore and understand the Zomato dataset.
- Load and inspect restaurant data using Pandas.
- Clean and preprocess restaurant ratings.
- Analyze restaurant types and customer votes.
- Visualize restaurant rating distributions.
- Compare ratings of restaurants based on online ordering.
- Analyze approximate costs for two people.
- Explore restaurant types and online order availability using a heatmap.

## 🛠️ Technologies Used

- **Python** – Programming language for data analysis.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.

## 📂 Dataset

The project uses a CSV file named `Zomato data .csv`.

Key columns used in the analysis include:

- `rate` – Restaurant rating.
- `votes` – Number of customer votes.
- `listed_in(type)` – Restaurant type or category.
- `online_order` – Online ordering availability.
- `approx_cost(for two people)` – Approximate cost for two people.

## 📊 Analysis Performed

### 1. Data Loading and Inspection

- Loaded the CSV dataset using Pandas.
- Displayed dataset records using `df.head()`.
- Examined dataset structure and column information using `df.info()`.

### 2. Restaurant Rating Analysis

- Converted restaurant ratings into numeric values.
- Visualized rating distribution using a histogram.
- Compared ratings for restaurants with and without online ordering using a box plot.

### 3. Restaurant Type Analysis

- Counted restaurants across different types using a count plot.
- Calculated total customer votes for each restaurant type.
- Visualized restaurant type-wise votes using a line graph.

### 4. Cost Analysis

- Examined the approximate cost for two people.
- Used a count plot to visualize the frequency of different cost values.

### 5. Online Ordering Analysis

- Created a pivot table to count restaurants by type and online order availability.
- Used a heatmap to visualize the relationship between restaurant types and online ordering.

## 📈 Visualizations

The project includes the following visualizations:

- Restaurant type count plot
- Restaurant type vs. total votes line graph
- Restaurant rating distribution histogram
- Online ordering vs. rating box plot
- Approximate cost count plot
- Restaurant type and online ordering heatmap

## 💻 Installation and Usage

**Step 1:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

**Step 3:** Open the Jupyter Notebook in Google Colab or Jupyter Notebook.

**Step 4:** Place the CSV dataset in the appropriate location and update the file path if necessary.

**Step 5:** Run the notebook cells to perform the analysis and generate visualizations.

## 📁 Project Structure

```text
Zomato-Data-Analysis/
│
├── Zomato data .csv
├── Zomato_Data_Analysis.ipynb
└── README.md
```

*Note: Update the filenames above to match the actual files in your GitHub repository.*

## 🚀 Skills Demonstrated

- Data loading and inspection
- Data cleaning and preprocessing
- Data grouping and aggregation
- Pivot table creation
- Exploratory Data Analysis (EDA)
- Data visualization
- Python data analysis libraries

## 👩‍💻 Author

**Neha Paswan**

Aspiring AI and Data Science Professional

GitHub: Add your GitHub profile link here

LinkedIn: Add your LinkedIn profile link here

## 📄 License

This project is intended for educational and learning purposes.
