<div align="center">
<h1>Text-Based Gender Prediction</h1>
<p>Utilizing machine learning algorithms to infer gender from textual data.</p>
</div>


<h3>Overview</h3>
This endeavor aims to ascertain the gender of authors based on the content of their text. The central task revolves around training machine learning algorithms to discern whether a given text originates from a male or female author. Evaluation of model performance primarily hinges on the F1-score, a metric that balances precision and recall.

<h3>Tools and Techniques</h3>

This initiative is constructed using the subsequent tools and techniques:

<ul>
  <li>Programming Language: Python</li>
  <li>Libraries: NumPy, Pandas, scikit-learn, and re (utilized for regular expressions)</li>
  <li>Integration of text analysis methodologies with machine learning algorithms</li>
  <li>Conversion of text into tokenized vectors</li>
  <li>Implementation of a structured machine learning workflow </li>
</ul>

Certain constraints govern the project:

<ul>
  <li>Limited utilization of specified libraries; external modules are prohibited</li>
  <li>Exclusion of external files or word lists</li>
  <li>Data provided in CSV format for both training and testing purposes</li>
</ul>

<h3>Outcomes</h3>
Model performance is assessed via the F1-score.
F1-scores are calculated for male and female classes independently, and an average F1-score is derived to offer a comprehensive evaluation of model efficacy.

<h3>Commencing the Project</h3>
To commence the project, adhere to the subsequent steps:
<ul>
  <li>Clone the repository onto your local machine.
  <li>Navigate to the designated project directory.
  <li>Access the provided Jupyter Notebook (Assignment3-text-analysis.ipynb) to examine the code and accompanying explanations.
</ul>
<h3>Utilization</h3>
Initiate the following steps for utilization:
<ul>
  <li>Load training data from annotated_corpus_for_train.csv.</li>
  <li>Preprocess text data utilizing assorted techniques.</li>
  <li>Train machine learning models (e.g., Perceptron, LinearSVC, DecisionTreeClassifier, etc.).</li>
  <li>Assess models via cross-validation and compute average F1-scores.</li>
  <li>Employ the trained model to predict genders of test examples sourced from corpus_for_test.csv.</li>
</ul>
