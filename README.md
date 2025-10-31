#Submission Overview:

This analysis imported and inspected the Superstore data, checked types and missingness, and confirmed that no rows required removal for missing Postal Codes.​

Descriptive statistics highlighted typical central tendency (mean, median, mode), spread, and distribution characteristics for Sales, Profit, and Discount variables.​

Outliers were identified using IQR methodology (Sales: 1,167, Profit: 1,881 outliers) and handled via Winsorization to mitigate their impact on subsequent analyses.​

Data Cleaning and Processing
All columns were reviewed for missing data; none were found, ensuring analysis integrity.​

Winsorization (5th/95th percentile) on Sales and Profit columns reduced distortion—mean and standard deviation dropped significantly, indicating improved distribution normality.​

Key EDA Insights
The dataset contained 9,994 records and 11 features, including critical sales and profit details by category, region, segment, and date.​

Category frequency identified Office Supplies as the most common (6,026), followed by Furniture and Technology.​

Statistical and visual exploration (histograms, boxplots) demonstrated right-skewed distributions with substantial outliers in both Sales and Profit, especially before Winsorization.​

The final state of data post-cleaning was free of missingness, with variables ready for further predictive analytics or business intelligence application.​

Conclusion
This submission demonstrates a robust EDA workflow using the Superstore dataset, applying best practices in data import, cleaning, outlier handling, and core statistical/visual analysis.​

The process ensures data reliability and prepares the dataset for deeper modeling, while transparently documenting each major step and transformation.
