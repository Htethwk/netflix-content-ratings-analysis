# Netflix Content & Ratings Analysis

This project explores how a streaming platform’s content strategy varies across **content type, maturity rating, time, genre, and country**.  
The goal is to demonstrate **data storytelling, visualization design, and analytics/engineering thinking** using real-world messy metadata.

## Key Questions
- How does Netflix balance **Movies vs TV Shows** in its content catalog?
- Which **maturity ratings** dominate the platform, and what does that suggest about target audiences?
- How has Netflix’s **content strategy evolved over time**, particularly during periods of rapid growth?
- How do **ratings and genres** vary across different types of content?
- How does Netflix adapt **content maturity across top international markets**?
- What role do **genres and ratings** play in audience segmentation and engagement?

## What I Built
- Cleaned and engineered features (`date_added`, `year_added`, multi-valued `countries`, `genres`)
- Created stakeholder-friendly visualizations with clear labeling and layout decisions
- Summarized patterns with “so-what” implications for content strategy

## Visual Highlights

### 1) Movies vs TV Shows (Link : https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/01_Content_Type_Distribution.PNG )


**Insight:** Netflix’s catalog is movie-heavy in volume, but maintains a significant share of TV shows to support long-term viewer engagement and retention.

### 2) Distribution of Content Ratings ( Link: https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/02_Rating_Distribution.PNG )

**Insight:** Netflix’s content strategy is strongly oriented toward mature and teen audiences, with TV-MA and TV-14 titles accounting for the majority of the catalog.

### 3) Ratings by Content Type ( Link: [https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/03_Rating_Breakdown_Movies_vs_TV%20shows.PNG )

**Insight:** The sharper skew toward mature ratings in TV shows reinforces Netflix’s emphasis on serialized content that encourages repeat viewing and long-term subscriber retention.

### 4) Top Genres by Rating (Link : https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/04_Top_Genres_By_Rating.PNG )

**Insight:** Netflix uses genre-specific rating distributions to intentionally segment audiences, with mature ratings dominating Drama and International content and family ratings concentrated in Children & Family titles.

### 5) Content Added Over Time ( Link : https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/05_Content_Added_Overtime_by_Rating.PNG )

**Insight:** The sustained dominance of TV-MA and TV-14 during peak growth years indicates Netflix’s deliberate focus on mature, retention-driven content as it scaled globally.

### 6) Ratings by Country (Top Markets) (Link : https://github.com/Htethwk/netflix-content-ratings-analysis/blob/main/06_Rating_by_Country.PNG )

**Insight:** Netflix tailors content maturity by region, balancing a mature U.S.-led catalog with localized rating distributions across international markets.

## How to Run
Open the notebook:
  1. Clone or download this repository.
  2. Unzip the dataset file
  3. Ensure the unzipped CSV file is placed in the appropriate directory
  4. Open the Jupyter notebook
  5.  Run the notebook cells from top to bottom to reproduce the analysis and visualizations.
**Note:**  
The dataset is provided in compressed format to keep the repository lightweight and to reflect real-world data handling practices.

## Tech Stack
- Python, Pandas
- Matplotlib / Seaborn (with design-focused labeling and layout)
