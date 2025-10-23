<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" width="250" alt="Netflix Logo">
</p>

<h1 align="center">🎬 Netflix Data Analysis & Visualization (SQL + Python)</h1>

<p align="center">
  <b>End-to-end Data Analysis Project using MySQL, Pandas, and Seaborn</b><br>
  Clean • Transform • Visualize Netflix Data 📊
</p>

---

## 🧠 Project Overview
This project explores and analyzes the **Netflix Movies and TV Shows Dataset** using **MySQL** for data cleaning (ELT) and **Python** for visualization.  

The goal is to uncover insights about Netflix’s content — such as trends over time, type distribution, top genres, and country contributions.

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| 🐬 **MySQL** | Data cleaning & transformation |
| 🐍 **Python** | Data analysis & visualization |
| 🧾 **Pandas** | Data manipulation |
| 🎨 **Matplotlib / Seaborn** | Charts & plots |
| ⚙️ **SQLAlchemy** | MySQL-Python connection |
| 💻 **Jupyter Notebook** | Interactive environment |

---

## 📁 Project Structure
```

📦 netflix-sql-project/
├── data/
│   ├── netflix_raw.csv
│   └── netflix_cleaned.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── visuals/
│   ├── movies_vs_tvshows.png
│   ├── titles_over_years.png
│   ├── top_countries.png
│   ├── genre_distribution.png
│   └── ratings_distribution.png
├── README.md
└── requirements.txt

````

---

## 📊 Data Analysis & Key Insights

| # | Question | Visualization | Insight |
|---|-----------|----------------|----------|
| 1️⃣ | Movies vs TV Shows | 📊 Bar Chart | Netflix has more Movies than TV Shows |
| 2️⃣ | Top Producing Countries | 🌍 Horizontal Bar Chart | USA, India, UK lead |
| 3️⃣ | Titles Added Over Time | 📈 Line Chart | Rapid growth after 2015 |
| 4️⃣ | Ratings Distribution | 🟢 Bar Chart | TV-MA and TV-14 dominate |
| 5️⃣ | Top Genres | 🎭 Bar Chart | Dramas, Comedies, and Documentaries |
| 6️⃣ | Average Movie Duration | ⏳ Metric | Around 90 minutes |

---

## 🧮 Summary of Insights
✅ Netflix’s catalog grew **exponentially after 2015**  
✅ **Movies dominate** (~70% of content)  
✅ **USA, India, and UK** are top content producers  
✅ Most shows rated **TV-MA** (mature audiences)  
✅ **Drama & Comedy** are most frequent genres  
✅ **Average movie duration:** ~90 minutes  

---

## 🧰 How to Run the Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/netflix-sql-project.git
cd netflix-sql-project
````

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Import Data to MySQL

```sql
CREATE DATABASE netflix_db;
USE netflix_db;
LOAD DATA INFILE 'data/netflix_cleaned.csv'
INTO TABLE netflix_cleaned
FIELDS TERMINATED BY ','
IGNORE 1 LINES;
```

### 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook notebooks/netflix_analysis.ipynb
```

---

## 🗂️ Dataset Source

📊 [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/shivamb/netflix-shows)

---

## 👨‍💻 Author

**Your Name**
📧 [adhavanbtech2004@gmail.com](mailto:your.email@example.com)
💼 [LinkedIn]([https://www.linkedin.com/in/adhavan-parasuraman]) | 🐙 [GitHub](https://github.com/AdhavAdhavan)

---

## 🌟 Future Improvements

* 🔗 Integrate IMDb ratings for richer insights
* 📈 Build an interactive **Streamlit dashboard**
* 🤖 Use ML to predict popular genres

---

<p align="center">
  Made with ❤️ using SQL & Python  
  <br>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" width="100" alt="Netflix Logo">
</p>
