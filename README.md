# Netflix Content & Ratings Analysis

This project explores how a streaming platform’s content strategy varies across **content type, maturity rating, time, genre, and country**.  
The goal is to demonstrate **data storytelling, visualization design, and analytics/engineering thinking** using real-world messy metadata.

## Key Questions
- How does the catalog balance **Movies vs TV Shows**?
- Which **maturity ratings** dominate the platform?
- How have content additions changed **over time**?
- Do ratings differ across **top producing countries**?

## What I Built
- Cleaned and engineered features (`date_added`, `year_added`, multi-valued `countries`, `genres`)
- Created stakeholder-friendly visualizations with clear labeling and layout decisions
- Summarized patterns with “so-what” implications for content strategy

## Visual Highlights

### 1) Movies vs TV Shows
![Content Type](images/01_content_type.png)

**Insight:** TV shows represent a major share of the catalog, supporting retention-driven engagement.

### 2) Distribution of Content Ratings
![Ratings Distribution](images/02_rating_distribution.png)

**Insight:** The catalog is concentrated in TV-MA and TV-14, indicating a strategic focus on teen/adult audiences.

### 3) Ratings by Content Type
![Ratings by Type](images/03_ratings_by_type.png)

**Insight:** TV shows skew more mature than movies, reinforcing serialized content’s role in engagement.

### 4) Content Added Over Time
![Content Over Time](images/04_content_over_time.png)

**Insight:** Content additions accelerate after 2016, aligning with platform expansion and scaling of content investment.

### 5) Ratings by Country (Top Markets)
![Ratings by Country](images/05_ratings_by_country.png)

**Insight:** Rating mixes differ by country, suggesting localization and regional audience differences.

## How to Run
Open the notebook:
- `notebooks/netflix_content_ratings_analysis.ipynb`

## Tech Stack
- Python, Pandas
- Matplotlib / Seaborn (with design-focused labeling and layout)
