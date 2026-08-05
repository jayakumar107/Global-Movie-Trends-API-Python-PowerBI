 # 🎬 Global Movie Trends
An interactive Power BI dashboard built using movie data extracted from the TMDb API with Python to analyze global movie trends, financial performance, audience ratings, and genre popularity.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#key-insights">Key Insights</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-observations">Final Observations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>
The Global Movie Trends Dashboard provides a comprehensive analysis of movie industry trends by leveraging data from The Movie Database (TMDb) API. Python was used to extract and prepare the data, while Power BI was used to create an interactive dashboard that enables users to explore movie performance through key metrics, charts, and filters. The dashboard helps identify trends in revenue, popularity, ratings, genres, languages, and audience engagement.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>
Movie studios and entertainment analysts require data-driven insights to understand what factors contribute to a movie's success. By analyzing movie performance across multiple dimensions such as revenue, ratings, popularity, genres, and languages, stakeholders can better understand audience preferences and industry trends to support strategic decision-making.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

The dataset was created by extracting movie data from the TMDb (The Movie Database) API using Python. It contains information such as:

- Movie Title
- Release Date
- Original Language
- Popularity Score
- Average Rating
- Vote Count
- Runtime
- Budget
- Revenue
- Production Countries
- Genres
- Movie Status

The data was cleaned, transformed, and exported as CSV files before being imported into Power BI.

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python (Requests, Pandas)
- TMDb API
- Power BI
- Power Query
- DAX

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Global-Movie-Trends-Dashboard/
│
├── Dataset/
│   ├── genres.csv
│   ├── movie_genres.csv
│   └── movie_data.csv
│
├── Notebook/
│   └── tmdb_api_data.ipynb
│
├── Dashboard/
│   └── dashboard_global_movie_trends.pbix
│
├── Image/
│   └── dashboard_photo_global_movie_trends.png
│
├── Report/
│   └── report_global_movie_trends.pdf
|
├── README.md
```
---
<h2><a class="anchor" id="key-insights"></a>Key Insights</h2>

- Blockbuster movies such as Avatar and Avengers: Endgame generated the highest total revenue.
- Spider-Man: Brand New Day recorded the highest popularity score in the dataset.
- English-language movies dominate the dataset, indicating their strong global market presence.
- Action and Adventure are the most common movie genres.
- Movies have an average runtime of approximately 121 minutes.
- The average movie rating is 6.94, indicating generally positive audience reception.
Highly rated movies are not always the highest revenue-generating movies.
- Movies with higher vote counts generally demonstrate stronger audience engagement and long-term popularity.

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

<img width="1224" height="686" alt="image" src="https://github.com/user-attachments/assets/5299b710-5983-45d3-bf30-115989306954" />

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone this repository.
``` bash
git clone https://github.com/yourusername/Global-Movie-Trends-API-Python-PowerBI.git
``` 

2. Install the required Python libraries.

```
pip install requests pandas
```

3. Obtain a TMDb API Bearer Token from TMDb.
4. Replace the Bearer Token in the Python script with your own API key.
5. Run the Python script to extract and export the movie data as CSV files.
6. Open the `.pbix` file in Power BI Desktop.
7. Refresh the data model to load the latest extracted data.
8. Explore the dashboard using the available slicers and interactive visuals.

---
<h2><a class="anchor" id="final-observations"></a>Final Observations</h2>

- The dashboard indicates that blockbuster movies contribute significantly to the overall box office revenue, with titles such as Avatar and Avengers: Endgame leading in revenue generation.
- Spider-Man: Brand New Day emerged as the most popular movie based on the TMDb popularity score, demonstrating high audience interest.
- English-language movies dominate the dataset, reflecting their strong presence and influence in the global film industry.
- Action, Adventure, and Drama are among the most prominent genres, suggesting that these genres continue to attract a large audience worldwide.
- The average movie runtime of 121 minutes indicates a consistent duration for mainstream feature films.
- The overall average rating of 6.94 suggests that most movies in the dataset received generally favorable audience reviews.
- Movies with higher vote counts, such as Interstellar and Inception, show strong audience engagement and sustained popularity over time.
- The comparison between revenue, ratings, and popularity shows that commercial success does not always align with critical or audience ratings, highlighting that multiple factors influence a movie's overall performance.

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Jaya Kumar**  
Aspiring Data Analyst  
📧 Email: jayaxkumar7@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jaya-kumar-a857173a1/)   

