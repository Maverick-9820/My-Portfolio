# My-Portfolio 
# Data Analysis Projects

Content Abuse Detection
Objective:
The objective of this project is to detect and analyze abusive content in
textual data using machine learning techniques and natural language
processing (NLP). The goal is to identify and categorize abusive content
effectively and provide insights into its characteristics.
Dataset:
● File: labeled_data.csv
● Description: The dataset includes text data labeled as either
abusive or non-abusive.
Project Steps:
1. Data Loading and Exploration:
○ Load and inspect the dataset.
○ Check for missing values and data types.
2. Data Cleaning and Preprocessing:
○ Remove missing values and duplicates.
○ Clean text data (lowercase conversion, punctuation removal).
3. Feature Extraction:
○ Convert text data into numerical features using TF-IDF
Vectorization.
4. Model Training:
○ Train a Random Forest Classifier.
○ Evaluate the model's performance.
5. Visualization:
○ Plot the distribution of labels.
○ Analyze text length by label.
○ Generate word clouds for abusive and non-abusive content.

# Policy Impact Assessment
Objective:
This project evaluates the effectiveness of YouTube content policies
through data analysis. It aims to assess how content policies impact video
performance metrics and engagement and provide insights for policy
revisions.
Dataset:
● File: youtube.csv
● Description: The dataset includes various metrics for trending
YouTube videos.
Project Steps:
1. Data Loading and Exploration:
○ Load and inspect the dataset.
○ Check for missing values and validate the dataset.
2. Data Cleaning:
○ Remove missing and duplicate values.
○ Convert date columns to appropriate formats.
3. Basic Analysis:
○ Analyze distributions of views, likes, dislikes, and comment
counts.
○ Explore relationships between metrics.
4. Advanced Analysis:
○ Perform sentiment analysis on video titles.
○ Apply topic modeling to video tags.
5. Interactive Visualization:
○ Use Plotly for interactive scatter plots and explore video
metrics.

# Instructions to Run the Code
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/your-repository.git

cd your-repository
1.
2. Set Up Environment:
○ Ensure you have Python installed.

Install the required libraries:
bash
Copy code
pip install pandas matplotlib seaborn wordcloud textblob scikit-learn
plotly
○
3. Run the Code:
○ Place the dataset files (labeled_data.csv and youtube.csv) in
the same directory as the script.

Execute the scripts using:
bash
Copy code
python content_abuse_detection.py
python policy_impact_assessment.py

○
4. View Results:
○ Check the generated images and HTML files in the directory to
review the visualizations and interactive plots.
