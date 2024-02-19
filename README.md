Text-Based Gender Prediction
Utilizing machine learning algorithms to infer gender from textual data.

Overview
This endeavor aims to ascertain the gender of authors based on the content of their text. The central task revolves around training machine learning algorithms to discern whether a given text originates from a male or female author. Evaluation of model performance primarily hinges on the F1-score, a metric that balances precision and recall.

Tools and Techniques
This initiative is constructed using the subsequent tools and techniques:

- Programming Language: Python
- Libraries: NumPy, Pandas, scikit-learn, and re (utilized for regular expressions)
- Integration of text analysis methodologies with machine learning algorithms
- Conversion of text into tokenized vectors
- Implementation of a structured machine learning workflow
Certain constraints govern the project:

- Limited utilization of specified libraries; external modules are prohibited
- Exclusion of external files or word lists
- Data provided in CSV format for both training and testing purposes

Outcomes
Model performance is assessed via the F1-score.
F1-scores are calculated for male and female classes independently, and an average F1-score is derived to offer a comprehensive evaluation of model efficacy.
The Perceptron model emerged as the most effective during testing, yielding an F1 score of 0.73.

Commencing the Project
To commence the project, adhere to the subsequent steps:

- Clone the repository onto your local machine.
- Navigate to the designated project directory.
- Access the provided Jupyter Notebook (Assignment3-text-analysis.ipynb) to examine the code and accompanying explanations.

Utilization
Initiate the following steps for utilization:

- Load training data from annotated_corpus_for_train.csv.
- Preprocess text data utilizing assorted techniques.
- Train machine learning models (e.g., Perceptron, LinearSVC, DecisionTreeClassifier, etc.).
- Assess models via cross-validation and compute average F1-scores.
- Employ the trained model to predict genders of test examples sourced from corpus_for_test.csv.
