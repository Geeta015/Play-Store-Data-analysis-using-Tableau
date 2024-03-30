# **Transforming (Play Store app Review Analysis) EDA Projects to Dashboards**
**Problem Statement:** To improve the general quality and performance of the app in the marketplace and to facilitate data-driven decision-making, exploratory data analysis (EDA) is crucial for comprehending, analyzing, and drawing insights from Play Store data.
The aim of this experiment is to leverage Tableau's visual analytics capabilities to uncover and enhance the understanding of client wants and aid product developers in popularizing their product.

Dataset Selection:
For my analysis, I'll utilize the following two datasets: Play Store data and User Reviews. 

**Dataset Details:**
1. Play store data:
The dataset comprises 13 columns, which are denoted as follows:
App - Name of the application.
Category - Category of the application.
Rating - Rating given by the users.
Reviews - Reviews given by the users.
Size - The size of the application.
Installs - How many installation are done.
Type - The application is free or paid.
Price - The price of the app.
Content Rating - Which age group finds it suitable?
Genres - the different additional categories.
Last Updated - When the application was last updated.
Current Ver - Current version of the application.
Android Ver - suitable Android version for the Application.

2. User Review Data:
The dataset has 5 columns described below:
App: Name of the application.
Translated_Review: English translation of the review.
Sentiment: Emotion like ‘Positive’, ‘Negative’, or ‘Neutral’.
Sentiment_Polarity: Polarity of the review (ranges [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’).
Sentiment_Subjectivity: How close a reviewers opinion is to the opinion of the general public. Its range is[0,1].

**Problem Areas to Explore:**
Enhancing user happiness, promoting business growth, and optimizing the app's overall performance in the marketplace are the ultimate objectives of investigating, evaluating and Visualising app engagement data.


**Here's a concise summary of the data analysis and dashboard creation process:**
1. Data Cleaning: I have to clean the data to remove missing value and duplicate values such as duplicate reviews.
2. Data Preprocessing: I have to convert all variables into appropriate datatypes and exclude any undesired values from the numerical columns, such as "$" from the price and "+" and "," from the installs. I have to convert all the numbers in MB because the size column contains both KB and MB values.
3. Exploratory Data Analysis: After data cleaning and preprocessing i have to perform the EDA to find out any relation between variables and pattern or trend. For that purpose, i have to calculate summary statistics (mean, median, standard deviation, etc.) for numerical features and use density plots, box plots, or histograms to display the distributions of the characteristics. Use frequency counts and visual aids like bar graphs to investigate categorical variables, such as app categories. Use heatmaps, correlation matrices, or scatter plots to analyze relationships between variables.
4Visualization with Tableau: Tableau's interactive dashboards were used to bring the cleaned data to life. After EDA is completed, I have to list the main conclusions and takeaways from the EDA process. Based on the analysis's findings, offer developers, marketers, and other stakeholders concrete suggestions. Draw attention to noteworthy correlations, trends, or user feelings that may have an effect on choices.

**Tableau Dashboard:**
Dashboard provides information about app popularity and user interactions.It examines the feelings and thoughts that users have concerning the apps and draws attention to the revenue trends and financial performance of apps.

**Tableau Story**
This effort culminates with a coherent Tableau narrative that facilitates easy navigation between the many data viewpoints of interaction, sentiment, and revenue for users in a seamless and user-friendly manner.

**Conclusion**
The final Tableau narrative style provides a thorough grasp of the complex nature of the Play Store data, enabling more thoughtful deliberation.



