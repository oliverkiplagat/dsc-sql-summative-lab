# 🎬 DSC SQL Summative Lab

An end-to-end SQL and Python data analytics project exploring two real-world business scenarios:

- **Part 1:** Customer and sales analysis using the ClassicModels E-Commerce database.
- **Part 2:** Exploratory Data Analysis (EDA) of IMDb movie data to uncover trends that support production decision-making.

---

##  Project Overview

This project demonstrates practical skills in:

- SQL querying
- Database joins and aggregations
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Business intelligence
- Git & GitHub workflows

---

## 📂 Project Structure

```text
.
├── SQLSummativeLab.ipynb
├── SQL_Summative_Lab_Part2_Slides.pdf
├── README.md
├── requirements.txt
├── data.sqlite
├── im.db.zip
├── credit_thresholds_distribution.png
└── top_revenue_customers.png
```

---

# 🛍️ Part 1: E-Commerce Analysis

**Database:** `data.sqlite`

### Objectives

- Analyze customer payment behavior
- Identify high-value customers
- Evaluate customer credit limits
- Explore revenue by region

### Key Insights

- Generated customer payment summaries (minimum, maximum, average, and total spending).
- Identified top revenue-generating customers.
- Highlighted high-credit customers for potential marketing campaigns.
- Compared customer revenue across countries.

---

# 🎬 Part 2: IMDb Movie Analysis

**Database:** `im.db.zip`

### Objectives

Perform exploratory data analysis to identify trends in:

- Movie ratings
- Runtime
- Genres
- Audience engagement

### Data Quality Findings

- Identified future-dated movie records.
- Approximately **22%** of movies lacked runtime information.
- Over **5,000** movies were missing genre classifications.
- Multi-value genre fields required preprocessing.

### Key Insights

- Movies longer than **120 minutes** achieved higher average audience ratings than movies under **90 minutes**.
- Drama and Biography combinations consistently received the strongest audience ratings among well-reviewed films.

---

# 📊 Visualizations

The notebook includes visualizations such as:

- Credit limit distribution
- Top revenue customers
- Runtime vs. audience ratings
- Genre performance analysis

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/dsc-sql-summative-lab.git
cd dsc-sql-summative-lab
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

**Linux/macOS**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Extract the IMDb database:

```bash
unzip im.db.zip
```

Launch Jupyter Notebook:

```bash
jupyter notebook SQLSummativeLab.ipynb
```

---

# 🛠️ Technologies

- Python
- SQLite
- SQL
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

# 📄 Presentation

The repository also includes an executive presentation summarizing the findings from the movie analysis:

**SQL_Summative_Lab_Part2_Slides.pdf**

---

## 👨‍💻 Author

**Oliver Kiplagat**

Data Science | SQL | Python | Machine Learning