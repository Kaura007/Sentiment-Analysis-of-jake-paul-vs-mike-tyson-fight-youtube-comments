 Sentiment Analysis of Jake Paul vs. Mike Tyson Trailer Comments
At a Glance
Learn sentiment analysis with Python and data visualization techniques to evaluate YouTube comments on the Jake Paul vs. Mike Tyson trailer. This hands-on project guides you through data processing methods to classify sentiments and extract actionable insights using libraries like pandas, numpy, and nltk. Ideal for beginners in data science or marketing professionals, complete this engaging introduction to sentiment analysis in just 30 minutes and enhance your analytical skill set.

Project Overview
Explore text sentiment analysis with python and unlock valuable insights from text data! This guided project focuses on evaluating sentiments in YouTube comments related to the Jake Paul vs. Mike Tyson trailer, using powerful Python libraries such as pandas, numpy, and nltk. Gain hands-on experience with essential data processing techniques to classify sentiments and extract actionable insights from textual data. Designed for beginners in data science and marketing professionals seeking to enhance analytical capabilities, this project equips you with valuable skills in just 30 minutes.

Learning Objectives
Upon completion of this project, you will be proficient in:

Grasping the fundamental concepts of sentiment analysis and its practical applications.

Employing Python libraries to effectively process text data for sentiment evaluation.

Deriving significant insights from sentiment data to support decision-making across various scenarios.

📝 Overview
This project presents a comprehensive sentiment analysis solution, designed to automatically classify text data from YouTube comments about the Jake Paul vs. Mike Tyson fight trailer. Utilizing a robust machine learning pipeline, this project demonstrates proficiency in data preprocessing, model selection, training, and evaluation. The analysis provides actionable insights into public opinion and feedback, which can inform marketing strategies and audience engagement.

🚀 Key Features
Automated Text Classification: Classifies raw text into predefined sentiment categories (Positive, Negative, or Neutral).

Data Cleaning & Preprocessing: Handles common NLP tasks, including tokenization, stop word removal, and lemmatization.

Vectorization Techniques: Employs TF-IDF or Word Embeddings to transform text into numerical data.

Machine Learning Model: Utilizes a supervised learning algorithm to train and predict sentiment.

Performance Evaluation: Provides a detailed report on model accuracy, precision, recall, and F1-score.

Visualizations: Includes key plots to illustrate data distribution and model performance.

💻 Technologies & Libraries
Programming Language: Python 3.x

Core Libraries:

pandas: For data manipulation and analysis.

numpy: For mathematical operations.

Natural Language Processing (NLP):

nltk: For text preprocessing and tokenization.

wordcloud: For generating word clouds.

scikit-learn: For machine learning models and evaluation metrics.

Visualization:

matplotlib

seaborn

📊 Data Source
The project utilized a dataset of YouTube comments about the Jake Paul vs. Mike Tyson trailer, taken from Kaggle. The data was pre-labeled for supervised learning, containing text and corresponding sentiment labels, as well as emotion-based scores.

A sample of the dataset showing the columns and data types.

🛠️ Methodology
Data Acquisition & Loading: The dataset was loaded and explored to understand its structure and content, including 17 different columns.

Exploratory Data Analysis (EDA): Performed initial analysis to identify class distribution, text length, and common words.

Text Preprocessing: The text data was cleaned by removing duplicates and unnecessary columns (published_at, author).

Feature Engineering: Text data was transformed into numerical features using word counts.

Model Training: A supervised learning model was trained to classify the sentiment.

Model Evaluation: The trained model was evaluated on a held-out test set using a confusion matrix and classification report.

📈 Results & Visualizations
The sentiment analysis revealed a high level of neutral and positive comments, with a lower percentage of negative comments. This suggests a generally positive or indifferent reaction to the trailer.

The distribution of sentiment across all comments.

Key Insights
Dominant Emotions: The most prominent emotions detected in the comments were negative, anger, positive, and fear.

Engagement: Comments with a positive sentiment received a significantly higher average number of likes compared to neutral and negative comments, indicating that positive opinions are more engaging.

A bar chart showing the average scores for different emotions, ranked from highest to lowest.

A bar chart comparing the average number of likes for each sentiment category.

Word Cloud
A word cloud was generated from the comments to visualize the most common words. The prominence of names like "Jake Paul" and "Tyson" highlights the primary focus of the discussion. Words like "fight" and "win" also appear frequently.

A visual representation of the most frequent words in the dataset.

⚙️ How to Run the Project
To run this project, you'll need Python 3.x and the required libraries.

Clone the repository:

git clone [https://github.com/your-username/your-project-name.git](https://github.com/your-username/your-project-name.git)
cd your-project-name

Create a virtual environment (recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run the main script:

python your_main_script.py

📧 Contact
Feel free to reach out for questions or collaborations!

Your Name: [Your Full Name]

Email: [Your Email Address]

LinkedIn: [Your LinkedIn Profile URL]

GitHub: [Your GitHub Profile URL]
