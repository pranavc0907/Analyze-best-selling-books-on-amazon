# 📚 Amazon Best-Selling Books Analysis

## 🎯 Project Overview
This project analyzes Amazon's Top 50 Best-Selling Books dataset (2009–2019) to uncover trends in book popularity, author performance, genre preferences, pricing patterns, and reader ratings. 

Using Python and Pandas, the dataset was cleaned, transformed, and explored through exploratory data analysis (EDA) to generate meaningful insights about consumer reading behavior.

---

## 📂 Dataset Information
The dataset contains Amazon's annual Top 50 Best-Selling Books from 2009 to 2019.

### Features Included
| Column | Description |
| :--- | :--- |
| **Name** | Title of the book |
| **Author** | Author name |
| **User Rating** | Average reader rating |
| **Reviews** | Number of reviews |
| **Price** | Book price (USD) |
| **Year** | Year of appearance on bestseller list |
| **Genre** | Fiction or Non-Fiction |

---

## 🛠️ Tech Stack
* **Programming Language:** Python 3
* **Libraries Used:** Pandas, NumPy
* **Environment:** Jupyter Notebook

---

## 🧹 Data Cleaning Process
Several preprocessing steps were performed to improve data quality and prepare the dataset for evaluation:
* Removed duplicate records to prevent skewed data distributions[cite: 1].
* Standardized column names for cleaner syntax and ease of use[cite: 1].
  * *Renamed:* `Name` → `Title`, `Year` → `publication year`, `User Rating` → `rating`[cite: 1].
* Converted the `Price` column explicitly into a float data type for numerical consistency[cite: 1].
* Verified missing values and checked overall dataset integrity.

---

## 📊 Exploratory Data Analysis (EDA)
The following foundational analyses were performed within the notebook:
* **Author Analysis:** Identifying the most frequently appearing authors and calculating the number of bestseller entries per author[cite: 1].
* **Genre Analysis:** Investigating the distribution between Fiction and Non-Fiction, alongside average ratings across both genres[cite: 1].
* **Price & Rating Distribution:** Reviewing data metrics (min, max, mean) across numerical constraints to evaluate dataset dispersion[cite: 1].

---

## 📈 Key Insights

### 🏆 Top Authors
| Rank | Author | Bestseller Entries |
| :--- | :--- | :---: |
| 1 | Jeff Kinney | 12 |
| 2 | Suzanne Collins | 11 |
| 3 | Rick Riordan | 11 |
| 4 | Gary Chapman | 11 |
| 5 | American Psychological Association | 10 |

### ⭐ Average Rating by Genre
| Genre | Average Rating |
| :--- | :--- |
| **Fiction** | 4.65 / 5.0 |
| **Non-Fiction** | 4.60 / 5.0 |

> **Observation:** Fiction books received a slightly higher average customer satisfaction rating compared to Non-Fiction options over the 11-year span.

---

## 📁 Project Structure
```text
Amazon-Best-Selling-Books-Analysis/
│
├── Analyze-best-selling-books-on-amazon.ipynb   # Main Jupyter notebook containing clean EDA code
├── README.md                                     # Project presentation page
├── avgrating-by-genre.csv                        # Exported average ratings by genre data
├── bestsellers.csv                               # Original raw dataset
└── top_authors.csv                               # Exported top authors dataset

```

---

## 🚀 Installation & Usage

### 1. Clone the Repository

```bash
git clone <https://github.com/pranavc0907/Analyze-best-selling-books-on-amazon.git>
cd Amazon-Best-Selling-Books-Analysis

```

### 2. Install Dependencies

```bash
pip install pandas numpy jupyter

```

### 3. Run the Notebook

```bash
jupyter notebook

```

Open **`Analyze-best-selling-books-on-amazon.ipynb`** inside the interface to inspect the step-by-step code executions.

---

## 📌 Results Generated

The execution of the final pipeline dynamically generates two summaries exported directly into the directory:

* `top_authors.csv` (Aggregated insights regarding top writing talent)


* `avgrating-by-genre.csv` (Aggregated overview of reader feedback distributions)



---

## 🎓 Skills Demonstrated

* **Data Cleaning & Wrangling:** Removing duplicates and data type standardization.
* **Exploratory Data Analysis (EDA):** Statistical summary exploration (`describe`, `shape`).
* **Data Transformation:** Groupby operations, data aggregation, and frequency mapping.
* **Analytical Thinking:** Deriving human-readable data summaries from raw spreadsheets.

---

## 🔮 Future Improvements

* Add interactive data visualizations utilizing `Matplotlib` and `Seaborn`.
* Run a correlation evaluation mapping relationship trends between price changes, reviews, and ratings.
* Build out a dashboard utilizing Power BI or Tableau to map interactive consumer trends.

---

## 👨‍💻 Author

**Pranav Chavan**
*B.Sc. Data Science Student | Aspiring Data Scientist*
