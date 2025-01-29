Analyzing Marketing Strategies to Boost Sales of a New Product

Project Overview
This project evaluates the impact of three different marketing strategies (promotions) on the sales of a new menu item for a fast-food chain. By analyzing the sales data, the goal is to determine the most effective promotion to maximize revenue.
The analysis involves statistical techniques such as ANOVA and Tukey's post-hoc test to identify significant differences among promotions and provide actionable recommendations for decision-making.

Objective
The primary objective is:
To assess the effectiveness of three different promotions on weekly sales of a new menu item.
To identify the best-performing marketing strategy for maximizing sales.

Dataset Overview
The dataset includes sales data for multiple locations, promotions, and weeks. It contains the following columns:

MarketID: Unique identifier for each market.
MarketSize: Size of the market (e.g., small, medium, large).
LocationID: Unique identifier for each store location.
AgeOfStore: Age of the store in years.
Promotion: One of the three promotions tested.
Week: Week of the promotional campaign (1-4).
SalesInThousands: Weekly sales in thousands for a specific location and promotion.

Tools and Libraries
The project uses the following Python libraries for data analysis and visualization:
pandas: For data manipulation and cleaning.
seaborn: For data visualization.
matplotlib: For plotting.
scipy.stats: For conducting ANOVA tests.
statsmodels: For Tukey’s HSD post-hoc analysis.

Steps in Analysis
Exploratory Data Analysis (EDA):
Analyzed sales trends across market sizes, store ages, and promotions.
Visualized the data using scatter plots, density plots, and histograms.

ANOVA Assumptions:
Checked for normality using density plots.
Tested for homogeneity of variances using Levene’s test.

ANOVA Testing:
Performed one-way ANOVA to determine if there are statistically significant differences in sales among the three promotions.
Post-Hoc Analysis:
Conducted Tukey’s HSD test to identify which specific promotions differ significantly from each other.

Recommendations:
Determined the best promotion based on statistical results.

Conclusion & Recommendations
Conclusion: The second marketing strategy (Promotion 2) is the most effective in driving sales of the new menu item.
Recommendation: It is advised to implement Promotion 2 for maximizing revenue.
