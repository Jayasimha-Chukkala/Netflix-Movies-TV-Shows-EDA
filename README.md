# 🎬 Netflix Movies & TV Shows Data Analysis using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies & TV Shows** dataset sourced from Kaggle. The primary objective is to clean the dataset, handle missing values, explore content trends, and generate meaningful insights through data visualization using Python.

The analysis focuses on understanding the distribution of Netflix content based on content type, release year, ratings, duration, actors, and countries.

---

## 📂 Dataset Information

* **Dataset:** Netflix Movies & TV Shows Dataset
* **Source:** Kaggle
* **Category:** Exploratory Data Analysis (EDA)

### Features Used

* `show_id` – Unique identifier
* `type` – Movie or TV Show
* `title` – Content title
* `director` – Director
* `cast` – Cast members
* `country` – Country of production
* `date_added` – Date added to Netflix
* `release_year` – Release year
* `rating` – Content rating
* `duration` – Movie runtime or TV Show seasons
* `listed_in` – Genre
* `description` – Brief description

---

## 🎯 Project Objectives

* Understand the structure of the Netflix dataset.
* Perform data cleaning and preprocessing.
* Handle missing values and duplicate records.
* Conduct Exploratory Data Analysis (EDA).
* Analyze Netflix content using various visualizations.
* Generate meaningful insights from the dataset.

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📋 Project Workflow

1. Import required libraries.
2. Load the Netflix dataset.
3. Inspect dataset structure and identify missing values.
4. Perform data cleaning and preprocessing.
5. Handle duplicate records.
6. Create duration-related features.
7. Perform Exploratory Data Analysis (EDA).
8. Generate visualizations.
9. Interpret results and summarize insights.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Filled missing values in **director**, **cast**, and **country** columns.
* Filled missing values in **date_added** using Forward Fill (`ffill()`).
* Filled missing duration values separately for Movies and TV Shows using the mode.
* Checked for duplicate records.
* Created separate numerical columns for Movie duration and TV Show seasons.

---

## 📊 Exploratory Data Analysis

The notebook includes analysis of:

* Rating distribution
* Content released by year
* Movie duration distribution
* TV Show season distribution
* Movies vs TV Shows distribution
* Top 10 actors appearing in Netflix content
* Top 10 countries producing Netflix content
* Inspection of specific ratings
* Inspection of specific titles (e.g., *Sacred Games*)

---

## 📈 Visualizations

The following visualizations were created:

* Count Plot for Rating Distribution
* Line Plot for Content Released by Year
* KDE Plot for Movie Duration
* KDE Plot for TV Show Seasons
* Pie Chart for Movies vs TV Shows
* Bar Chart for Top 10 Actors
* Bar Chart for Top 10 Countries

---

## 💡 Key Insights

* Movies constitute a larger portion of Netflix's catalog than TV Shows.
* Netflix content production has increased significantly over the years.
* Movie durations are concentrated within common runtime ranges.
* Most TV Shows have relatively fewer seasons.
* Certain content ratings occur more frequently than others.
* Some actors appear in a large number of Netflix titles.
* A few countries contribute a significant portion of Netflix's available content.

---

## 📁 Project Structure

```text
Netflix-EDA/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── Netflix_EDA.ipynb
│
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Netflix-EDA.git
```

2. Navigate to the project directory.

```bash
cd Netflix-EDA
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open **Netflix_EDA.ipynb** and run all the cells sequentially.

---

## 🎯 Conclusion

This project demonstrates the complete workflow of **Exploratory Data Analysis (EDA)** using Python. It covers data cleaning, preprocessing, feature engineering, visualization, and insight generation to better understand Netflix's content library. The project is suitable for beginners who want to strengthen their Python and data analysis skills using a real-world dataset.

---

## 👨‍💻 Author

**Jayasimha**

B.Tech – Computer Science Engineering (Artificial Intelligence & Machine Learning)

---

⭐ **If you found this project useful, consider giving it a star.**
