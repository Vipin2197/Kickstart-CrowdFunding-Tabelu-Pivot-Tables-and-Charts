 Data Modeling Tables Created
Projects (main): includes project_id, name, category, subcategory, country, launch_date, deadline, goal_usd, pledged_usd, backers, state (successful/failed/canceled).

Currency: maps original funding currency to conversion rates.

Country

Calendar (derived from launch_date + deadline) with columns: Year, MonthNo/Name, Quarter, YearMonth (YYYY-MMM), WeekdayNo/Name, FinancialMonth (Apr=FM1–Mar=FM12), FinancialQuarter.

📈 Key Analyses & SQL Queries
Currency Conversion: normalized goal and pledged into USD.

Project Distribution: counted campaigns by country and category.

Temporal Trends: projects launched per year/quarter/month; success rate by period.

Success Rate Analysis: grouped by state, category, and goal size.

Goal Bucketing: segmented projects into goal ranges and analyzed success ratios.

Backer Insights: average pledge per backer and correlation with success.

Top Projects: identified highest-funded and most-backed campaigns.

Category Insights: extracted and analyzed primary categories and subcategories.

📊 Dashboard Features & Visuals
Geo Map: campaign volume and success rate by country.

Category Treemap: top categories and their funding success.

Time-Series Line Chart: trends in launches and success rates over time.

Goal vs. Success Scatter Plot: visual relationship between goal size and outcome.

Top Campaigns Table: ranked by pledged amount and backers.

Interactive filters (country, category, launch_year), drill-downs (year→month).

📌 Business Insights
Optimal Goal Ranges & Timing: ideal goal (< $10K) and ~30-day duration linked to 40%+ success.

Top-Success Categories: creative and game segments outperform tech and hardware.

Backer Engagement: early momentum (first 48h pledges) strongly predicts success.

Geographic Focus: spotlight countries with high project density but low success—prime for campaign coaching.

Predictive Potential: informed creators on goal setting, campaign scheduling, and pitch structuring based on data trends.
