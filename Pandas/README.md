# 🐼 Pandas Data Analysis Projects

A collection of two beginner-to-intermediate **Pandas** projects exploring real-world datasets — anime rankings and global country statistics.

---

## 📁 Repository Structure

```
├── anime.csv                          # Anime dataset (Top 50 anime with rank, title, score)
├── Animedataset-pandas-project.ipynb  # Notebook: Anime data analysis
├── Countries.csv                      # World countries dataset (194 countries, 64 features)
└── pandas_capstone_project.ipynb      # Notebook: Countries data analysis (Capstone)
```

---

## 📊 Projects

### 1. 🎌 Anime Dataset Analysis
**Notebook:** `Animedataset-pandas-project.ipynb`  
**Dataset:** `anime.csv`

Explores the **Top 50 Anime** by score and extracts hidden information from the title strings.

**Key operations covered:**
- Loading and exploring a CSV with `pd.read_csv()`
- **Custom string parsing** — extracting episode count and air duration from title text using Python functions
- Creating new columns with `.apply()`
- Datetime parsing and calculating total air duration in months
- Filtering with `.loc[]` and boolean indexing
- Finding the highest-rated anime, anime with most episodes, and longest-running series

**Dataset columns:**

| Column | Description |
|--------|-------------|
| `Rank` | Anime ranking (1–50) |
| `Title` | Full title including episode count and air dates |
| `Score` | Community rating score |

---

### 2. 🌍 Countries Capstone Project
**Notebook:** `pandas_capstone_project.ipynb`  
**Dataset:** `Countries.csv`

A comprehensive analysis of **194 countries** across 64 demographic, economic, energy, and health indicators.

**Key operations covered:**
- Dataset exploration with `.shape`, `.info()`, `.describe()`
- Null value detection with `.isnull()` and `.isna().sum()`
- Sorting by democracy score and analyzing top democratic countries
- Population analysis — finding most/least populated countries and their capitals
- Region-wise breakdown using `.value_counts()`
- Custom function to count countries with "Republic" in their name
- Continent-level filtering (e.g., Africa subset analysis)

**Dataset highlights (64 columns):**

| Category | Example Columns |
|----------|----------------|
| Geography | `country`, `capital_city`, `region`, `continent`, `latitude`, `longitude` |
| Economy | `gdp`, `inflation`, `unemployment_pct`, `tax_revenue_pct_gdp` |
| Energy | `electricty_production_coal_pct`, `renewable_energy_consumption_pct` |
| Health | `life_expectancy`, `health_expenditure_pct_gdp`, `suicide_rate` |
| Demographics | `population`, `birth_rate`, `fertility_rate`, `median_age` |
| Politics | `democracy_score`, `democracy_type`, `political_leader` |

---

## 🛠️ Requirements

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/) *(used in capstone project)*
- Jupyter Notebook or JupyterLab

Install dependencies:
```bash
pip install pandas numpy jupyter
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open a notebook**
   - For anime analysis → open `Animedataset-pandas-project.ipynb`
   - For countries analysis → open `pandas_capstone_project.ipynb`

> ⚠️ Make sure the CSV files are in the **same directory** as the notebooks before running.

---

## 💡 What You'll Learn

- Reading and exploring datasets with Pandas
- Writing custom functions and using `.apply()` for feature engineering
- String manipulation and parsing with Python
- Filtering, sorting, and aggregating data
- Handling missing values
- Working with datetime data

---

## 📬 Author

**Manas**  
Made with ❤️ as a Pandas learning project.  
Feel free to fork, star ⭐, and build on top of it!
