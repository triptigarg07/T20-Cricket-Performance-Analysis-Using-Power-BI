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
- 🛠 Excel – Data cleaning, anomaly correction, and creating calculated columns.
- 📊 Power BI – Visualization and interactive dashboards.
- ⚡ DAX (Data Analysis Expressions) – Custom metrics & performance indicators.

## Key Insights & Analysis

### 1. Batting Performance Analysis

- 📊 Top-performing batsmen were identified based on strike rate, boundary percentage, and batting average.
- ✅ Power Hitters: Players like Jos Buttler, Alex Hales had high strike rates, boundary percentages, and strong batting averages.
  
  ![Power Hitters](/Power_Hitters.jpg)
  
- ✅ Anchors & Middle Order Stability: Players like Virat Kohli and Glenn Phillips showed consistency with high batting averages, playing the anchor role.

  ![Anchors](/Anchors.jpg)

- ✅ Finishers: Players like Marcus Stoinis, Glenn Maxwell, and Hardik Pandya played a crucial role in the death overs, maintaining high strike rates (160+), quick acceleration, and effective finishing abilities to maximize runs in the final overs. Their ability to hit boundaries at a high percentage made them key assets in chasing or setting big targets.

  ![Finishers](/Finishers.jpg)

### 2. Bowling Performance Analysis

🎯 Identified top-performing bowlers based on economy rate, strike rate, and dot ball percentage.
- ✅ Best Strike Rate: Anrich Nortje (8.55) and Shaheen Afridi (13.73) showcased efficient wicket-taking abilities.
- ✅ Most Economical: Tim Southee and Sam Curran had economy rates under 6.5, controlling runs effectively.
- ✅ Dot Ball Impact: Shaheen Afridi (46.36%) and Anrich Nortje (55.24%) had high dot ball percentages, creating pressure on batters.

  ![Specialist Fast Bowlers](/Specialist_Fast_Bowlers.jpg)

### 3. All-Rounder Impact Analysis

🌟 Players who contributed with both bat and ball were classified as all-rounders.
- ✅ Shadab Khan & Sikandar Raza played key roles, with batting averages of 24+ and bowling economy rates under 7.
- ✅ Rashid Khan’s all-round brilliance: Batting strike rate (178.13) & bowling economy (6.42) made him one of the most valuable players.

  ![All Rounders](/AllRounders.jpg)

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

### 6. How We Chose the Final 11 Players
🔍 To select the best-performing XI, we followed a data-driven approach based on:

- ✅ 1. Performance-Based Selection
  - Batting Metrics: Players with high strike rates, boundary percentages, and batting averages were prioritized.
  - Bowling Metrics: Bowlers with low economy rates, high dot ball percentages, and strong wicket-taking abilities were shortlisted.
  - All-Rounder Impact: Players contributing in both batting & bowling were given higher weightage.

- ✅ 2. Balanced Team Composition
 
To build a well-rounded XI, we ensured:

 - 2-3 Power Hitters (Explosive openers)
 - 2-3 Middle Order Anchors (Stability in innings)
 - 1-2 Finishers (Strong death-over batters)
 - 3-4 Specialist Bowlers (Fast & spin options)
 - 1-2 All-Rounders (Contributing with bat & ball)

- ✅ 3. Match Conditions & Opponent Analysis
  
   - Players were selected based on recent form & adaptability to match conditions (e.g., pitch type, opposition strengths).
   - Spin-heavy tracks favored all-rounders like Shadab Khan & Sikandar Raza.
   - Pace-friendly conditions gave preference to bowlers like Anrich Nortje & Shaheen Afridi.
 
   ![Final11](/Fina11.jpg)

  ## Enhancing User Experience with Power BI Tooltips & Buttons
🔍 Interactive Tooltips for Player Performance & Images
I integrated custom tooltips in Power BI to display each player’s individual performance, along with their image, when hovering over their name.

✅ Tooltip Features:

Shows player’s batting & bowling stats dynamically (e.g., Strike Rate, Wickets, Economy Rate).
Displays player image for better recognition.
Provides quick comparisons between players without opening another page.
📌 How It Works:
1️⃣ A user hovers over Virat Kohli’s name, and a tooltip pops up showing:

His batting average, strike rate, and role in the team.
A small player image for quick identification.
2️⃣ Similarly, hovering over a bowler’s name shows wickets, economy rate, and performance impact.

![Tooltip](/Tooltip.jpg)

🎛️ Navigating Between Pages Using Buttons

To enhance the user experience, we included buttons to switch between slides in Power BI, making navigation smooth.

✅ Button Features:

One-click navigation to switch between pages such as:
- 📊 Batting Performance Page
- 🎯 Bowling Insights Page
- 🏆 Final 11 Player Selection Page
-Dynamic Filtering: Clicking on a player’s name highlights their stats across different slides.
Drill-through Option: Users can click on a specific player to get a detailed breakdown of their performances across multiple matches.
📌 How It Works:
- 1️⃣ A user clicks on the "Batting Analysis" button, and the dashboard instantly moves to the detailed batting statistics page.
- 2️⃣ Clicking on "Bowling Insights" brings up bowling statistics.
- 3️⃣ Users can go back to the "Final 11 Selection" page at any time.

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

- ✅ Data Visualization – Designed engaging, interactive dashboards to communicate insights effectively.
- ✅ Data Analysis & Reporting – Evaluated key batting, bowling, and all-rounder statistics to classify players based on performance.
- ✅ Business Intelligence (BI) Tools – Used Power BI & DAX functions to generate powerful, data-driven insights.
- ✅ Storytelling with Data – Transformed complex data into meaningful narratives for cricket analysts and enthusiasts.
- ✅ Data-Driven Player Selection – Choosing the best XI based on stats & conditions.
- ✅ Dynamic Tooltips – Displaying individual player performance + images.
- ✅ Interactive Buttons – Allowing users to navigate seamlessly between different insights.
