# Objective

The goal of this project was to:
- ✅ Identify key players based on batting and bowling metrics.
- ✅ Categorize players into roles like power hitters, anchors, finishers, all-rounders, and specialist bowlers.
- ✅ Analyze match-wise performance trends to understand consistency and impact.
- ✅ Provide data-driven insights for team selection and strategy formulation.

## Dataset and Data Cleaning

1. Excel for Data Preprocessing

The dataset includes:

- Batting metrics: Runs, balls faced, strike rate, batting average, boundary percentage.
- Bowling metrics: Overs bowled, wickets taken, economy rate, dot ball percentage.
- Player roles: Batting style, bowling style, playing position, and performance classification.

📌 Steps taken in Excel:

1. Checked for missing values & filled gaps using logical approximations.
2. Identified & removed duplicate records to avoid redundancy.
3. Standardized inconsistent data formats (e.g., "150.0" converted to "150").
4. Created new calculated columns such as:
       - Batting Impact Score = (Strike Rate × Boundary %) / 100
       - Bowling Efficiency Score = (Wickets × Dot Ball %) / (Economy Rate × Bowling S/R)
       - Overall Performance Index = Weighted average of batting and bowling performance

## Technologies & Tools Used
- Power BI – For data visualization and interactive dashboards.
- DAX (Data Analysis Expressions) – To create calculated fields and performance metrics.

## Key Insights & Analysis

### 1. Batting Performance Analysis

- 📊 Top-performing batsmen were identified based on strike rate, boundary percentage, and batting average.
- ✅ Power Hitters: Players like Jos Buttler, Alex Hales, and Suryakumar Yadav had high strike rates (150+), boundary percentages (60%+), and strong batting averages.
- ✅ Anchors & Middle Order Stability: Players like Virat Kohli and Glenn Phillips showed consistency with high batting averages (50+), playing the anchor role.

### 2. Bowling Performance Analysis

🎯 Identified top-performing bowlers based on economy rate, strike rate, and dot ball percentage.
- ✅ Best Strike Rate: Anrich Nortje (8.55) and Shaheen Afridi (13.73) showcased efficient wicket-taking abilities.
- ✅ Most Economical: Tim Southee and Sam Curran had economy rates under 6.5, controlling runs effectively.
- ✅ Dot Ball Impact: Shaheen Afridi (46.36%) and Anrich Nortje (55.24%) had high dot ball percentages, creating pressure on batters.

### 3. All-Rounder Impact Analysis

🌟 Players who contributed with both bat and ball were classified as all-rounders.
- ✅ Shadab Khan & Sikandar Raza played key roles, with batting averages of 24+ and bowling economy rates under 7.
- ✅ Rashid Khan’s all-round brilliance: Batting strike rate (178.13) & bowling economy (6.42) made him one of the most valuable players.

### 4. Player Role Classification

🔍 Players were categorized based on performance metrics:

- Power Hitters (High SR, High Boundary %) – Jos Buttler, Alex Hales
- Finishers (High Strike Rate, Low Avg Balls Faced) – Glenn Maxwell, Marcus Stoinis
- Anchors (High Avg, Moderate SR) – Virat Kohli, Lorcan Tucker
- All-Rounders (Balanced Batting & Bowling Contribution) – Shadab Khan, Sikandar Raza
- Specialist Bowlers (High Wicket-Taking Ability, Low Economy Rate) – Anrich Nortje, Shaheen Afridi

### 5. Match-wise Performance Trends

📌 Match-by-match analysis revealed team trends and individual performances in key fixtures.
- ✅ Suryakumar Yadav’s explosive innings (SR 189.68) helped India dominate middle overs.
- ✅ Shaheen Afridi’s breakthrough spells (Economy 6.16) were crucial in tight matches.

## Impact & Learnings

🚀 Key Outcomes:
- ✅ Successfully built an interactive Power BI dashboard that enables real-time player and team performance analysis.
- ✅ Provided data-driven insights to categorize players into strategic roles like power hitters, finishers, and all-rounders.
- ✅ Enhanced decision-making for team selection by analyzing batting strike rates, economy rates, and match performances.
- ✅ Learned advanced data visualization techniques, making complex cricket data more accessible and actionable.

## Challenges & Solutions

- 🔴 Handling large datasets efficiently

   Solution: Used Power BI’s data modeling and DAX functions to improve performance and optimize queries.
  
- 🔴 Categorizing players based on multiple performance metrics

   Solution: Implemented dynamic segmentation logic in Power BI, considering strike rates, averages, and economy rates.
  
- 🔴 Creating an intuitive dashboard design

   Solution: Applied clear visual hierarchies using bar charts, scatter plots, and heatmaps for easy interpretation of insights.

## Conclusion

This Power BI project demonstrated my ability to analyze large datasets, create dynamic dashboards, and extract actionable insights from cricket statistics. It highlights my skills in:

- ✔ Data Visualization – Designed engaging, interactive dashboards to communicate insights effectively.
- ✔ Data Analysis & Reporting – Evaluated key batting, bowling, and all-rounder statistics to classify players based on performance.
- ✔ Business Intelligence (BI) Tools – Used Power BI & DAX functions to generate powerful, data-driven insights.
- ✔ Storytelling with Data – Transformed complex data into meaningful narratives for cricket analysts and enthusiasts.
