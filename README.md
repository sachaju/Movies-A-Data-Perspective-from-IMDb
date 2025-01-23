#  🎬 Movies-A-Data-Perspective-from-IMDb
## 📌 Objective  
The goal of this project is to analyze IMDb movie data to uncover trends, insights, and patterns in the film industry. Using data scraping and visualization, we explored various aspects of movies, including directors, genres, ratings, runtimes, and box office performance. The project combines data scraping, cleaning, and visualization into an interactive Power BI dashboard, enriched with additional features like movie posters and tooltips for enhanced user experience.  

---

## 📁 Project Structure  

- **`scraping_movies.ipynb`**  
  - Jupyter Notebook for scraping IMDb data, including details such as:  
    - Movie title, director(s), genre, release date.  
    - Runtime, IMDb rating, language.  
    - Box office earnings, budget, and poster images.  

- **`MoviesDashboard.pbix`**  
  - Power BI file containing our interactive dashboard, which features

- **`power_Bi ProjectSummary.pptx`**  
  - PowerPoint presentation summarizing the project’s objectives and methodology

- **Datasets**:  
  - **`merged_movies_data.csv`**  
    - Contains comprehensive information about movies, including title, directors, genres, runtime, box office performance, budget, IMDb rating, parental guidance, release date, etc
  - **`movie_images.csv`**  
    - A dataset of links to movie posters scraped from IMDb, allowing users to visualize the movies directly.  

---

## 📊 Dataset  

The dataset scraped from IMDb includes the following details for each movie:  
- **Title**: The name of the movie.  
- **Director(s)**: Who directed the movie.
- **Writer(s)**: Who wrote the movie.  
- **Genre**: The primary and secondary genres.  
- **Rating**: IMDb user rating.
- **Parental Guide**: Age ratings or content warnings for viewers..  
- **Runtime**: The movie's duration.  
- **Box Office & Budget**: Financial performance metrics.  
- **Language**: The movie's primary language.  
- **Poster**: A link to the movie poster for visual reference.


## 🛠️ Libraries and Tools Used  

### **Python Libraries**  
- **`BeautifulSoup`**: For parsing HTML and scraping data.  
- **`Selenium`**: For automating browser actions.  
- **`Pandas`** & **`NumPy`**: For data manipulation and cleaning.
  
### **Cleaning & Visualization Tools**  
- **Power BI**:  
  - Used to clean, merge datasets, and establish relationships between tables.  
  - Created interactive and visually appealing dashboards for insights. 
