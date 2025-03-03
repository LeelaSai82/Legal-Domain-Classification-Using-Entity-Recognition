# Legal-Domain-Classification-Using-Entity-Recognition

📌 Project Overview
This project focuses on classifying legal documents into different domains (e.g., civil, criminal, income tax, and constitutional rights) using Named Entity Recognition (NER) and Machine Learning techniques. We collected and labeled 900 legal judgments from Indian Kanoon, extracted embeddings using the T5 model, and applied various ML algorithms for classification. The system aids legal professionals in streamlining document categorization and analysis.

🚀 Features
✅ Legal Document Classification – Categorizes judgments into distinct legal domains.
✅ Named Entity Recognition (NER) – Identifies key legal entities for classification.
✅ Machine Learning Models – Uses Random Forest, SVM, Logistic Regression, and more for classification.
✅ Data Preprocessing – Includes tokenization, lemmatization, and min-max normalization.
✅ Hyperparameter Tuning – Improves model accuracy using GridSearchCV.

🛠 Tech Stack
Machine Learning Models: Random Forest, SVM, Logistic Regression, Decision Tree, KNN, Naïve Bayes, Bagging Classifier, AdaBoost
Embeddings: T5 Model
Libraries: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib

📂 Dataset
Source: 900 legal judgments from Indian Kanoon
Features: 768-dimensional embeddings + labeled legal categories (11 classes)
Processing: Tokenization, Lemmatization, Feature Scaling, Encoding

📊 Methodology
Data Collection – Gathered legal judgments and labeled them into 11 categories.
Preprocessing – Applied tokenization, lemmatization, and min-max scaling.
Data Splitting – Used 80% data for training and 20% for testing.
Model Training – Evaluated multiple ML models for classification.
Hyperparameter Tuning – Used GridSearchCV to optimize model performance.
Evaluation – Compared models using accuracy, precision, recall, and F1-score.

📈 Results
Best Model: SVM (Support Vector Machine) with 58.89% accuracy.
Random Forest Accuracy: 57.78%, with the highest F1-score of 46.80%.
Logistic Regression Performance: 57.22% accuracy after tuning.
