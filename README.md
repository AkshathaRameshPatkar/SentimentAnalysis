### Sentiment Analysis on Twitter Data

This project demonstrates a complete machine learning pipeline for sentiment analysis on Twitter data. It involves text preprocessing, feature extraction, model training, and evaluation. The primary goal is to classify the sentiments of tweets into categories such as positive, negative, neutral, and irrelevant.

#### Key Features
- **Text Preprocessing**: Utilizes SpaCy for tokenization, lemmatization, and removal of stop words and punctuation to clean and standardize text data.
- **Feature Extraction**: Employs TF-IDF Vectorizer to convert text data into numerical features suitable for machine learning models.
- **Label Encoding**: Encodes categorical sentiment labels into numerical form for model training.
- **Machine Learning Model**: Implements RandomForestClassifier within a scikit-learn pipeline to predict tweet sentiments, achieving an accuracy of 90%.
- **Data Cleaning and Preparation**: Handles null and duplicate values to ensure the integrity and quality of the dataset.
- **Data Visualization**: Uses Matplotlib to create visualizations that illustrate class distributions, sentiment content, and reactions across different entities.

#### Data
- The project uses two datasets: a training dataset (`twitter_training.csv`) and a validation dataset (`twitter_validation.csv`), which are merged and preprocessed to form a combined dataset.

#### Visualizations
- **Class Balance**: A pie chart showing the percentage distribution of different sentiment classes.
- **Entity Distribution**: A pie chart displaying the distribution of entities in the tweets.
- **Sentiment Distribution**: A bar chart representing the count of different sentiment classes.
- **Reactions by Entity**: A bar chart comparing the reactions (sentiments) across different entities.

#### Installation
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Download and place the datasets (`twitter_training.csv` and `twitter_validation.csv`) in the project directory.

#### Usage
1. Run the preprocessing script to clean and prepare the data.
2. Execute the model training script to train and evaluate the sentiment classifier.
3. Generate visualizations to analyze the sentiment distribution and reactions.

#### Contributions
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.
