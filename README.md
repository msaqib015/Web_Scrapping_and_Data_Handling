# Web_Scrapping_and_Data_Handling

```markdown
# 🎬 Web Scraping & Data Handling — JustWatch India Movie Listings (2000+)

This project involves **web scraping**, **data extraction**, and **cleaning** of movie listings from [JustWatch India](https://www.justwatch.com/in/movies?release_year_from=2000). The goal is to collect structured information about movies released after 2000 and prepare it for exploratory analysis, recommendation engines, or visualization.

---

## 🎯 Objective

- Scrape metadata of movies released in India from the year 2000 onward.
- Structure and clean the data for use in analytics projects.
- Understand streaming availability, genres, release trends, etc.

---

## 🌐 Source

🔗 [JustWatch India Movie Listings (from 2000)](https://www.justwatch.com/in/movies?release_year_from=2000)

⚠️ *This project is for educational purposes only. JustWatch content is copyrighted by its respective owners.*

---

## 🧰 Tools & Libraries Used

- `Python`
- `requests`, `BeautifulSoup` — for web scraping
- `pandas` — for data handling and cleaning
- `re`, `json`, `time` — for parsing and delays
- `matplotlib`, `seaborn` — for optional visualizations

---

## 📁 Data Fields Extracted

- Movie Title  
- Release Year  
- Genre(s)  
- IMDb/JustWatch Rating (if available)  
- Streaming Provider(s)  
- Runtime (where available)  
- Language  
- URL for more details  

---

## 🧼 Data Handling

- Cleaned nulls, duplicates, and inconsistent types
- Extracted genre and streaming platform from HTML tags
- Parsed pagination and scrolled results
- Saved to `.csv` and `.json` formats for further use

---

## 📂 Project Structure

```

justwatch\_scraper/
│
├── data/                     # Cleaned movie data (.csv, .json)
├── notebooks/                # Jupyter notebooks for scraping and EDA
├── scripts/                  # Python scripts for scraping automation
├── visuals/                  # Charts and summaries (optional)
├── LICENSE                   # CC BY-NC 4.0 License
└── README.md                 # Project documentation

```

---

## 🔍 Future Enhancements

- Add support for TV Shows scraping
- Enhance provider-specific filtering (Netflix, Prime, etc.)
- Enable live scraping with user input (via Streamlit or CLI)


## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License.

> You are free to **share** and **adapt** the material for non-commercial purposes with appropriate attribution. This project is for educational use only. All content scraped from JustWatch is owned by its respective publishers and platforms.

🔗 License: https://creativecommons.org/licenses/by-nc/4.0/
