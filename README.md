# 🎬 **Watch Now – Excel Movie Analytics Dashboard**

## 💭 Why I Chose This Project
With the explosion of OTT platforms like Netflix, Prime Video, and Disney+, I became curious about **how the movie industry performs globally** across different genres and years.  
I wanted to explore questions like:  
- Which **genres** dominate global collections?  
- How do **critic ratings** and **ROI** vary over decades?  
- Which **quarters** contribute the most to box office success?  

The goal was not just to analyze data — but to **build a visually appealing Excel dashboard** that tells a clear story about movie performance trends.

---
## ⚔️ Challenges Faced
The major challenge in this project was **managing slicer interactions**:  
- I wanted some charts (like overall summaries) to **stay static** while others change with slicer filters.  
- When I grouped years in the Pivot Table, it also grouped the slicer — which disrupted interactivity.  
To solve this, I used the **“External Data Source” option** when inserting Pivot Tables, so certain visuals stayed **independent of slicer filters**.  

Designing a bold and readable layout on a **red-and-black theme** was another creative challenge — balancing contrast and maintaining readability across all visuals.

---

## Business Problem ❗
In the film industry, it’s often difficult for production houses and analysts to:
- Identify which **genres** deliver the highest ROI.  
- Understand **critic rating trends** over decades.  
- Track **quarterly or yearly** performance globally.  
- Compare **budget vs. revenue** to evaluate investment efficiency.
---

## Objective 🎯
To develop an **interactive Excel-based Movie Analytics Dashboard** that studies and analyzes **global movie performance trends** across genres, ratings, and decades — enabling **data-driven insights** into the entertainment industry.  
The project helps visualize **quarterly revenues, critic ratings, budgets, and ROI** to understand what drives success in the movie business.

---

**Explore Full Project:** [Download Excel Dashboard](https://docs.google.com/spreadsheets/d/1QdbsWNE_9Z_EhzeYhluLgO1eusPZCBwY/edit?usp=drive_link&ouid=107730141714120952377&rtpof=true&sd=true)

---

## 1) Dashboard Overview (Preview)
![Dashboard Screenshot](https://github.com/lubhanigola/Excel-Projects/raw/main/Watch%20Now/Watch%20Now%20Dashboard.png)

---

## ⚙️ Techniques & Features Used

### 🧮 Excel Formulas
| Purpose | Formula |
|----------|----------|
| **Extract Month Name** | `=TEXT(G2,"mmm")` |
| **Create Quarter Number** | `=ROUNDUP(MONTH(G2)/3,0)` |
| **Calculate ROI** | `=(Revenue - Budget)/Budget` |

### 📊 Pivot Tables & Charts
- **Revenue, ROI, IMDb Ratings, Country, and Genre Analysis**
- Used:
  - Column charts for *Quarterly Collections* and *Top Shows*
  - Line charts for *Critic Ratings* and *Yearly ROI*
  - Bar charts for *Budget by Genre*
  - Donut chart for *Top 5 Genres by IMDb Rating*

---
## Data Source 🔗
**Source:** [Movie Dataset for Analytics & Visualization (Kaggle)](https://www.kaggle.com/datasets/mjshubham21/movie-dataset-for-analytics-and-visualization)

The dataset consists of **999,999 records** capturing comprehensive details about movies released across different countries and years.  
It includes **financial, rating, and production-related attributes** that together provide a 360° view of movie performance worldwide.

---

## Key Features & Visuals ✨

📅 **Quarterly Global Collection (Column Chart):**
- Displays total revenue by quarter to identify seasonal patterns.

🎞️ **Top Shows by Global Collection (Bar Chart):**
- Highlights the highest-grossing movies worldwide.

⭐ **Critic Rating Impact by Year (Line Chart):**
- Tracks critic ratings over decades to understand audience evolution.

💸 **Budget by Genre (Horizontal Bar Chart):**
- Compares average budgets across genres to reveal spending patterns.

🎥 **Top 5 Genres by IMDb Rating (Donut Chart):**
- Visualizes genres with the best audience ratings.

📈 **Yearly ROI (Line Chart):**
- Demonstrates return on investment trends over time.

🎛️ **Slicers:**
- Enables interactive filtering by *Release Year*, *Country*, *Genre*, and *IMDb Rating*.

## Key Insights 🔎
- 🎬 **Q4** recorded the highest **global collection**, showing strong year-end performance.  
- 💸 **Documentary** and **Thriller** genres showed the **highest average budgets**.  
- 🎥 **“Air Company”** emerged as the **top show by global collection**.  
- ⭐ Average IMDb rating across top 5 genres: **~6.5 to 6.6**, showing stable audience satisfaction.  
- 📈 ROI trends were steady but showed dips in certain decades — likely due to higher budget risks.  
- 💬 Critic ratings fluctuated decade-wise, reflecting changes in cinematic preferences.

---

## 🧠 Learnings & Takeaways
- Improved understanding of **Pivot Table data connections** and **slicer behavior**.  
- Learned how to design **independent visuals** unaffected by slicer filters.  
- Enhanced skills in **data storytelling and dashboard composition**.  
- Strengthened formula logic for ROI and error handling in missing data.  
- Developed a sharper eye for **color consistency and layout balance** in Excel dashboards.

---
