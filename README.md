


📊 IPL Power BI Analytics Dashboard (2008–2024)

 📌 Overview  
This project presents a comprehensive, interactive analytics solution for the Indian Premier League (IPL), built entirely in Power BI. It leverages match-level and ball-by-ball datasets from 17 seasons (2008–2024), analyzing over 100,000 deliveries from 1,100+ matches played by 10 franchises. The project includes a clean data pipeline, advanced DAX measures, visually rich dashboards, and a responsive user experience, all deployed via Power BI Service.

---

🛠 Tools & Technologies
- **Power BI Desktop & Service**
- **DAX (Data Analysis Expressions)**
- **Power Query (M language)**
- **Excel / CSV-based Dataset Handling**
- **Data Modeling & Relationship Design**

---

 🧱 Data Sources
The data was sourced from [ESPN Cricinfo](https://www.espncricinfo.com/), cleaned and structured into:
- `all_season_summary.csv` – Match-level summaries  
- `all_season_details.csv` – Ball-by-ball delivery data  
- `all_season_batting_card.csv` – Player-level batting stats  
- `all_season_bowling_card.csv` – Player-level bowling stats  
- `points_table.csv` – Team standings per season

---

 🔍 Key Objectives
- Build a scalable IPL analytics suite with advanced filtering and drilldown features.
- Enable dynamic exploration of team and player performance across seasons.
- Highlight key metrics such as strike rates, win/loss trends, powerplay performance, and match impact.

---

 🧠 Features Implemented
 ✅ Dashboard Pages:
1. **Landing Page / Navigation Hub**  
   - Redirects to other pages via button-based navigation  
   - Gives a high-level summary of IPL seasons and total stats  

2. **Overall IPL Performance**  
   - Team-wise comparison of wins, losses, toss outcomes  
   - Visualization of venue distribution, season-wise champions, and team rankings  

3. **Team Profile Page**  
   - Selectable filters for any team across any season  
   - Metrics include win %, total runs, top players, bowling economy  

4. **Player Profile Page**  
   - Searchable, slicer-enabled views for individual player performance  
   - Batting and bowling splits, strike rate vs average, and season-based evolution

---

📈 Metrics & DAX Highlights
- Created over **25+ custom DAX measures** including:
  - Win %, Toss Win %, Bat/Field First Performance  
  - Bowling Economy, Strike Rate, Wicket Tally  
  - Top Run Scorers and Wicket Takers by Team  
  - Season Filters, Team Filters, Match Result Conditions

---

⚙️ Technical Architecture
- Used Power Query to clean and transform raw CSVs into structured models
- Defined **1-to-many** relationships across fact tables and dimensions (Teams, Players, Matches)
- Applied **Row Context vs Filter Context** concepts for correct DAX logic
- Optimized report performance using slicer syncing and page-level filters

---

🧭 Navigation & UX
- Implemented a **multi-level drilldown flow (League → Team → Player)**
- Designed a homepage redirect experience using **buttons and bookmarks**
- Responsive layout tested across Power BI Web and Mobile Service views

---

🚀 Deployment
- Report was published to **Power BI Service** for web access
- Sharing and collaboration enabled through secured report links
- Filtered views allowed stakeholders to slice data by season, team, player


 Impact & Insights
- Over **100K deliveries and 1,100+ matches** analyzed
- Identified trends in team dominance, underperforming seasons, and match-defining player contributions
- Enhanced accessibility and interactivity by **80%+** using clean UI and dynamic navigation



🎯 Takeaways
- Solidified end-to-end skills in Power BI from data modeling to publishing
- Gained deep understanding of cricket analytics, T20 format dynamics, and data storytelling
- Demonstrated strong command of DAX and performance-optimized visual design



📎 Future Enhancements
- Integrate predictive modeling for match outcomes using Python (via Power BI Python integration)
- Add player comparison tool using parameter tables
- Create dynamic story-based highlights for top matches of each season
