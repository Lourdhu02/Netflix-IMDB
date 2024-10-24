
# 📊 Power BI Netflix IMDB Ratings Dashboard

This project showcases a professional Power BI dashboard that visualizes Netflix's top-rated and most-voted movies based on IMDB ratings. The dashboard is interactive and provides valuable insights into Netflix movies and shows, focusing on IMDB scores and vote counts.

## 🚀 Features

1. **Top Rated Movies Page:**
   - Displays the highest-rated and most-voted movies with their IMDB scores, release year, and total votes.
   - Key metrics are shown using card visuals and line charts for a quick overview.

2. **Top 10 Movies by IMDB Score & Votes:**
   - An interactive slicer allows users to toggle between:
     - Top 10 IMDB-rated movies.
     - Top 10 most voted movies.
   - Bar charts visualize these top 10 movies for easy comparison.

3. **IMDB Score and Votes Trend (Line Graph):**
   - A timeline split by release decade, showing the trend of average IMDB scores and votes over time.
   - Two lines represent the average IMDB rating and the total votes, making it easy to track how these factors have evolved.

## 📈 Visualizations

- **Card Visuals:** Summarize key metrics like the highest-rated movie and the most-voted movie.
- **Line Graph:** Illustrates the trends of IMDB scores and votes across decades.
- **Bar Chart:** Displays top 10 movies based on both IMDB ratings and votes, with the ability to switch between them using a slicer.

## 📊 Dataset

The dataset used in this project includes the following columns:

- `index`: Unique identifier.
- `id`: Netflix movie/show ID.
- `title`: Name of the movie or show.
- `type`: Type (movie or show).
- `description`: Brief description of the title.
- `release_year`: Year of release.
- `age_certification`: Age rating for the title.
- `runtime`: Duration of the movie or show.
- `imdb_id`: IMDB identifier.
- `imdb_score`: IMDB rating score.
- `imdb_votes`: Total votes on IMDB.

## 🔧 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/lourdhu02/Netflix-IMDB-Ratings-Dashboard.git
    ```

2. Open the Power BI file (`Netflix_IMDB_Dashboard.pbix`) in Power BI Desktop.

3. Ensure the dataset (`Netflix_TV_Shows_Movies.csv`) is properly loaded.

4. Explore the dashboard using the interactive visuals and slicers to gain insights.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgements

- Special thanks to [Netflix](https://www.netflix.com/) and [IMDB](https://www.imdb.com/) for the data.
- Thanks to Power BI for providing an amazing platform for data visualization.
