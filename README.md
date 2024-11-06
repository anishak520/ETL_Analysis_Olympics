# Olympic Games ETL Analysis with SparkSQL

## Project Overview
This project involved an ETL (Extract, Transform, Load) analysis of Olympic Games data, showcasing data wrangling, SQL querying, and SparkSQL proficiency. Using a dataset of Olympic athlete records, this analysis explored key trends and patterns, highlighting advanced data analyst skills in data exploration, querying, and data visualization. The final results have been saved as CSV files and provide insights into various aspects of Olympic history, including medal counts, athlete participation, and trends over time.

## Skills Demonstrated
### 1. **Data Wrangling and ETL**
   - Successfully ingested a large dataset from a cloud source (S3 bucket).
   - Cleaned and structured data for analysis using Spark DataFrames and SQL.
   - Demonstrated data extraction and loading processes in a scalable and efficient manner.

### 2. **Data Exploration with SQL**
   - Created complex SQL queries within SparkSQL to explore Olympic medal trends, top-performing athletes, and popular sports.
   - Used subqueries, aggregations, and sorting to extract meaningful insights, including:
     - Top countries by total and gold medals.
     - Most participating athletes across all Olympic years.
     - Age analysis of gold medalists over the years.

### 3. **Data Transformation and Insight Generation**
   - Generated new insights by applying transformations, such as grouping and aggregation, which were saved in individual CSV files for further reporting.
   - Showcased the ability to work with temporal data by identifying trends over time (e.g., changes in athlete age and sports popularity).

## Key Findings and Results

The analysis revealed the following insights, available in the attached CSV files:

### Medal Winners
- **Top 5 Gold, Silver, and Bronze Medalists**:
   - Identified the athletes with the highest counts of each medal type.
   - Provided a view of the most successful Olympians in terms of medal accumulation.

### Country Performance
- **Top 5 Countries by Total Medals** (`top5CountriesByTotalMedals.csv`):
   - Highlighted the countries that consistently excel across all Olympic Games, reflecting a strong sports infrastructure and talent pool.
- **Top 5 Countries by Gold Medals** (`top5CountriesByGoldMedals.csv`):
   - Focused on the countries with the highest achievements in winning gold medals, a sign of top-tier athletic performance.

### Participation and Athlete Trends
- **Top 5 Sports by Participation** (`top5SportsByParticipation.csv`):
   - Ranked the sports with the most athletes, shedding light on the popularity and accessibility of specific sports.
- **Most Olympic Appearances by an Athlete** (`mostAppearancesByAthlete.csv`):
   - Recognized the athlete with the most consistent participation in the Olympics, showcasing remarkable endurance and skill.
- **Average Age of Gold Medalists** (`avgAgeGoldMedalists.csv`):
   - Tracked the average age of gold medal winners over the years, illustrating trends in athlete age and the youthfulness or experience needed for gold medal success.

## Concluding Remarks
This project not only demonstrates proficiency in SparkSQL and ETL processing but also provides valuable insights into Olympic history and trends. The analysis reflects the potential of large-scale data processing in uncovering patterns across vast datasets. This project exemplifies core data analyst competencies, such as data cleaning, querying, and transforming data into actionable insights. 

Each result is saved in individual CSV files, serving as a comprehensive data resource for further exploration of Olympic Games history.
