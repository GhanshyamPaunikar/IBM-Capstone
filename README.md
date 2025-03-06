:rocket: Applied Data Science Capstone
This capstone project marks the culmination of the IBM Data Science Professional Certificate, the 10th and final course in the specialization. It integrates and applies the knowledge and skills acquired throughout the program into a comprehensive, real-world project.

:page_facing_up: Project Background
SpaceX stands as a pioneer in the commercial space era, revolutionizing space travel by offering affordable launches. The company promotes its Falcon 9 rocket at a cost of $62 million per launch—significantly lower than the $165 million charged by competitors. This cost advantage stems largely from SpaceX’s ability to reuse the Falcon 9’s first stage. By predicting whether the first stage will successfully land, we can estimate launch costs more accurately. This project leverages public data and machine learning to forecast first-stage reuse.

:page_facing_up: Key Questions
How do factors like payload mass, launch site, flight frequency, and orbit type influence first-stage landing success?
Has the success rate of landings improved over time?
Which algorithm is most effective for binary classification in this scenario?
:page_facing_up: Methodology
1. Data Collection
SpaceX REST API: Gathered structured launch data directly from SpaceX’s public API.
Wikipedia Web Scraping: Extracted supplementary launch details from Wikipedia tables.
2. Data Wrangling
Filtered dataset to focus on Falcon 9 launches.
Addressed missing values (e.g., imputed payload mass with averages).
Applied One-Hot Encoding to transform categorical variables for binary classification.
3. Exploratory Data Analysis (EDA)
Conducted EDA using visualizations (e.g., scatter plots, bar charts) and SQL queries to uncover patterns and relationships.
4. Interactive Visual Analytics
Built an interactive map with Folium to visualize launch sites and outcomes.
Developed a Plotly Dash dashboard for dynamic exploration of success metrics.
5. Predictive Analysis
Designed and tuned classification models (e.g., Logistic Regression, Decision Tree) to predict landing success.
Evaluated model performance using accuracy, F1-score, and cross-validation to identify the best approach.
