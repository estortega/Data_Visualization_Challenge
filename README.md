# Data Visualization

For this project, I was tasked with analyzing data from a recent animal study involving 249 mice treated for squamous cell carcinoma (SCC), a common form of skin cancer. The study involved several drug regimens over a 45-day period, and my primary focus was to evaluate the performance of our target drug, Capomulin, compared to other treatments.

For this project, I used Matplotlib, Pandas, and Jupyter Notebook to generate all the figures and tables needed for the technical report, as well as a high-level summary of the findings.

# Project Objectives
- Clean and prepare the data by merging two datasets and removing duplicate timepoints.
  
- Generate summary statistics such as mean, median, standard deviation, variance, and SEM for each drug regimen.
  
- Visualize the data using bar charts and pie charts to show drug regimen distribution and gender breakdown.
 
- Analyze tumor volume data using quartiles and box plots to detect outliers among top-performing treatments.

- Explore treatment effects over time with a line plot for a selected mouse on Capomulin.

- Investigate the relationship between mouse weight and tumor size using a scatter plot, correlation coefficient, and linear regression.

# Key Analysis Steps
- Data Cleaning: I merged mouse_metadata and study_results and filtered out any mouse with duplicate timepoints to ensure accuracy.

- Bar & Pie Charts: I visualized the number of observations per drug regimen and the gender distribution of mice using both Pandas and Matplotlib.
- Tumor Volume Analysis: I focused on Capomulin, Ramicane, Infubinol, and Ceftamin, calculating IQR and identifying any outliers, which I highlighted in a multi-boxplot figure.

- Capomulin Deep Dive: I selected a single mouse treated with Capomulin to track tumor reduction over time and plotted the results.

- Correlation Study: For mice treated with Capomulin, I examined the correlation between mouse weight and tumor volume. I computed the Pearson correlation coefficient and overlaid a linear regression line on the scatter plot.

- This project not only helped visualize key insights from the clinical trial but also demonstrated the potential of Capomulin as an effective treatment regimen.
