# 🎬 Movie Dataset Analysis – Python Project

## 📊 Overview  
This data analysis project explores a movie dataset using Python. The goal is to extract meaningful insights about **movie genres**, **directors**, **popularity**, and **production trends**. Through data cleaning, transformation, and visual storytelling, the project highlights patterns in the film industry using visual tools like `matplotlib` and `plotly`.

---

## 🎯 Project Objective  
To perform exploratory data analysis (EDA) on a real-world movie dataset in order to:

- Identify trends in movie genres and popularity  
- Analyze top directors and production companies  
- Explore correlations between revenue, popularity, and runtime  
- Present findings using clear and engaging visualizations

---

## 🔄 Process

### 1. Data Import & Setup  
- Loaded the dataset using `pandas`  
- Imported libraries: `numpy`, `matplotlib`, `plotly.express`

### 2. Data Cleaning  
- Dropped unnecessary columns: `imdb_id`, `homepage`, `cast`, `tagline`, `overview`, `budget_adj`, `revenue_adj`  
- Removed rows with missing values in `genres` or `director`  
- Replaced missing values in `keywords` and `production_companies` with 0  
- Rounded `popularity` values to 2 decimal places for readability

### 3. Feature Exploration  
- Grouped and analyzed:
  - Most popular genres  
  - Average revenue by director  
  - Most productive production companies  
- Performed correlation checks between numeric features

### 4. Data Visualization  
- Created plots using `matplotlib` and `plotly`:
  - Genre distribution  
  - Popularity trends  
  - Revenue vs. runtime scatterplots  
  - Director comparisons

---

## 🗃️ Data Details

### Fields Used  
- `genres` – Primary genre(s) of each film  
- `director` – Director(s) of the film  
- `popularity` – Popularity score  
- `production_companies` – Associated production companies  
- `revenue`, `budget`, `runtime`, `vote_average`, `release_year`

---

## 📈 Analysis Highlights

### 🎭 Genres  
- Certain genres consistently receive higher popularity scores  
- Genre diversity often leads to better reception and revenue

### 🎬 Directors  
- Top directors with highest average revenue and production volume identified  
- Visualization of director success and impact over time

### 🏢 Production Companies  
- Production houses with the most films produced were ranked  
- Relationships between company output and average success measured

---

## 💡 Key Insights

- Action and Adventure genres dominate in popularity  
- A small number of directors are responsible for high-revenue films  
- Runtime and popularity show weak correlation; longer does not always mean better  
- Companies producing fewer films can still yield high-performing results

---

## 📌 Recommendations

1. **Focus on Popular Genres**  
   Studios may invest more in genres that maintain high average popularity.

2. **Track Top Directors**  
   Filmmakers with consistently high success rates can be prioritized for large-budget projects.

3. **Balance Production Volume and Quality**  
   More films ≠ more success; strategic selection and promotion matter.

4. **Utilize Popularity Metrics**  
   Popularity scores offer a useful early indicator of potential success.

---

## ✅ Conclusion  
This project showcases practical skills in:

- ✅ Data wrangling and cleaning with `pandas`  
- ✅ Exploratory analysis and grouping by categorical features  
- ✅ Interactive and static visualizations using `plotly` and `matplotlib`  
- ✅ Deriving insights and communicating them with clarity

---

## 🛠️ Tools Used  
- Python 3.x  
- Jupyter Notebook  
- `pandas`, `numpy`  
- `matplotlib`, `plotly.express`  

---

## 📎 Files Included  
- `movies.ipynb` – Jupyter notebook with full analysis and visualizations  
- `movies.csv` – Dataset used *(optional in repo)*

---
