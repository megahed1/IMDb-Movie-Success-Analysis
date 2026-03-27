IMDb Movie Success Analysis 🎬📊
📌 Business Scenario
A major Film Production Studio is looking to overhaul its production strategy for the next 5 years. As a Lead Data Analyst, I was tasked with analyzing a dataset of 10,000+ movies to uncover the secrets behind financial success and audience reception.

The goal is to answer:

Does a higher budget guarantee a better rating?

Which directors are the "Gold Mines" for the studio?

How have market trends shifted over the decades?

🛠️ Data Engineering & Cleaning
The raw data was "noisy" and required significant preprocessing to ensure the integrity of the business insights:

Irrelevant Data Removal: Eliminated redundant columns (e.g., homepage, tagline, keywords) and technical IDs to focus on analytical features.

Financial Normalization: Dropped duplicate inflation columns and prioritized budget_adj and revenue_adj to allow for a fair comparison between movies from different eras (1960s vs 2010s).

Data Integrity: Handled missing values and removed duplicates to prevent biased statistical results.

💡 Key Business Insights
Through rigorous Exploratory Data Analysis (EDA), the following insights were derived:

The Budget Myth: There is a 0.09 correlation between budget and user ratings. This proves that high spending does not buy audience satisfaction; script quality and direction are the true drivers.

Top Performing Talent: Identified the top 10 directors by "Adjusted Revenue" post-1997. Names like James Cameron and Peter Jackson consistently outperform the market average by significant margins.

Revenue Outliers: Isolated "Blockbusters" (Revenue > $3.5B adjusted) to study the common characteristics of extreme financial success.

Rating Distribution: Visualized how audience expectations have evolved, helping the studio set realistic KPIs for future releases.
