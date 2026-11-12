# Student-Performance-Factors-Analysis-Predictive-Insights
This notebook walks through a comprehensive analysis of various factors affecting student exam performance—including data cleaning, behavioral metrics exploration, data visualization, and descriptive statistical analysis.
Handling Missing Values
Impute missing values:
For categorical columns (object), I filled missing entries with the column's mode (most frequent value).
For numerical columns, I filled missing entries with the column's median.
Check and Remove Duplicates
Checked if any identical records exist and drop them to prevent skewed analyses.
Dataset Manipulation (Filtering, Grouping, and Sorting)
I filtered the students with an attendance rate of greater than 85% and group them by their parental involvement level to see how average hours studied and final exam scores compare.
(Distribution of Exam Scores by Gender)
This plot displays how the final exam scores are distributed between male and female students in the dataset using an overlaid histogram with Kernel Density Estimation (KDE) curves.
(Exam Scores across Parental Involvement Levels)
This plot displays the distribution and median of final exam scores across the three parental involvement tiers: Low, Medium, and High.
(Correlation Heatmap)
This visualization demonstrates the relationships and correlation strengths between all numerical parameters in the dataset.
