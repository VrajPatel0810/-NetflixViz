# 🎬 NetflixViz: Unveiling Streaming Trends Through Data

This project presents an end-to-end exploratory data analysis of Netflix's content catalog using Python. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows), provides insights into the type, rating, release year, duration, and origin of content on Netflix.  
Visualizations were created using **Matplotlib** and **Pandas**, and the project is structured in a script named `Netflix_Insights.py`.

---

## 📁 Dataset Summary
- **Source**: Kaggle - [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Total entries**: ~8800+
- **Columns used**: `type`, `release_year`, `rating`, `country`, `duration`

---

## 📊 Key Visualizations & Insights

### 1. 📦 Content Type Distribution
**Bar chart comparing the number of Movies and TV Shows** on Netflix.

> 🎥 Netflix hosts significantly more **Movies** than **TV Shows**, with nearly 2.5x the volume.

![Movies vs TV Shows](![movies_vs_tvshows](https://github.com/user-attachments/assets/9ba6c4fd-9695-4f02-880c-a546a28fe6ee)
)

---

### 2. 🧾 Content Rating Breakdown
**Pie chart showing the percentage of each rating category** (TV-MA, TV-14, R, PG, etc.).

> 🔍 The majority of content is rated **TV-MA** (36.8%) and **TV-14** (24.2%), reflecting a strong focus on mature and teen audiences.

![Content Rating Pie](![Content_Rating_pie](https://github.com/user-attachments/assets/56d7a272-8e19-4b6f-b0b2-dfd05b625bf6)
)

---

### 3. ⏱️ Distribution of Movie Durations
**Histogram representing the duration of movies in minutes.**

> ⏰ Most movies fall between **80–120 minutes**, with a peak around **90 minutes** – standard feature-length films.

![Movie Duration Histogram](![movies_duration_histogram](https://github.com/user-attachments/assets/6397bec9-c6ab-4da8-9362-87ca70bdc6f2)
)

---

### 4. 🌍 Top 10 Countries by Number of Shows
**Horizontal bar chart of the countries producing the most Netflix content.**

> 🇺🇸 **United States** dominates, followed by **India**, **UK**, and **Japan** – indicating strong global content sourcing.

![Top Countries](![top10_countries](https://github.com/user-attachments/assets/652f7c92-f2db-42fe-abca-354b624f1fb9)
)

---

### 5. 🗓️ Year-wise Release Trends
**Scatter plot showing number of releases per year** (movies + shows).

> 📈 Netflix saw a **massive spike in content production after 2010**, with peaks around 2018–2020.

![Release Year Scatter](![release_year_Scatter](https://github.com/user-attachments/assets/509a93d0-b6df-48c7-a5cb-1a4f035b6fd5)
)

---

### 6. 📅 Movies vs TV Shows Released Over Years
**Dual-line plot comparing Movies and TV Shows released per year.**

> 🟢 **Movies** have always led in volume, but **TV Shows** show rapid recent growth, especially post-2015.

![Movies vs TV Shows by Year](![movies_tv_shows_comparison](https://github.com/user-attachments/assets/145dfe92-5cde-4669-9d5f-136c736ce6a8)
)

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook / Script**
- **Kaggle Dataset**

---

## 🚀 How to Use the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflixviz.git
   cd netflixviz
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib
   ```

3. Run the analysis:
   ```bash
   python Netflix_Insights.py
   ```

4. The script will generate and save `.png` image files of the visualizations.

---

## 🔍 Summary of Insights

- 🎞 **Movies dominate** Netflix's content library.
- 🧠 Ratings like **TV-MA** and **TV-14** are most common.
- ⏳ Most movies range around **90 minutes**.
- 🌐 **USA, India, UK** are the top content-producing countries.
- 📈 Massive **growth in content releases post-2010**, showing Netflix’s global expansion.

---

## 🤝 Contribute / Collaborate

Open to suggestions and contributions for improving the analysis or extending this into an interactive dashboard using **Plotly** or **Streamlit**.

---

## 🙋‍♂️ Author

**Vraj Patel**  
[LinkedIn]([https://linkedin.com](https://www.linkedin.com/in/vraj-patel-68310b188/))  

