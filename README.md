# Machine-Learning-HR-Dataset
A project exploring data science and machine learning tools to analyze a human resource dataset, examining different attributes of employees from Kaggle.
#**Part A: Basic EDA (Exploratory Data Analysis)**

This section focuses on understanding the structure and quality of the HR dataset. It involves checking dataset dimensions, data types, and missing values and generating descriptive statistics. Key insights such as employee demographics, salary distributions, and departmental sizes are explored. Tools used here include Pandas for data manipulation, NumPy for numerical support, and Matplotlib/Seaborn for visual exploration.

**#Part B: Business Analysis**

In this part, the dataset is analyzed to address HR-related business questions. The analysis explores salary differences by gender, marital status, and race, identifies the departments with higher engagement and satisfaction scores, and examines recruitment sources and employee turnover trends. Techniques such as groupby operations, value counts, and comparative visualizations are applied. Visualization libraries Seaborn and Matplotlib are used to highlight patterns, while Pandas enables aggregations and statistical summaries.

#**Part C: Data Visualization**

Here, the emphasis is on creating meaningful visual insights to communicate patterns in the data effectively. Visualizations include histograms, barplots, heatmaps, scatterplots, and stacked bar charts to represent salaries, employee satisfaction, performance, absences, and departmental trends. Seaborn is primarily used for advanced plots, while Matplotlib provides customization. This part translates complex HR data into accessible visuals for decision-making.

#**Part D: PCA (Dimensionality Reduction)**

This section applies Principal Component Analysis (PCA) to reduce dimensionality and uncover latent structures in the HR dataset. Numerical features are standardized with StandardScaler before transformation. PCA is used to identify the most influential features, visualize employees in reduced dimensions, and support clustering analysis with KMeans. The explained variance ratios, scree plots, and biplots help interpret the components. This part leverages Scikit-learn’s PCA module along with visualization support from Seaborn and Matplotlib.
