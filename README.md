README.md
# 🏷️ Consumer Complaint Classification

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify consumer complaints into product categories based on their text narratives.  

The model applies text cleaning (lowercasing, punctuation removal, stopword removal, stemming), transforms text into numerical features using **CountVectorizer**, and trains a **Stochastic Gradient Descent (SGD) Classifier** to predict complaint categories.

---

## 📌 Features
- Preprocesses raw complaint narratives (cleaning, stopword removal, stemming)
- Converts text to numerical features using **Bag-of-Words (CountVectorizer)**
- Trains a **linear classifier (SGDClassifier)** for classification
- Achieves good accuracy on real-world data
- Easily scalable to other text classification problems

---

## 📊 Dataset
Dataset used: **Consumer Complaint Database**  
📥 Download here: [Consumer Complaint Database - CFPB](https://www.consumerfinance.gov/data-research/consumer-complaints/)  

Place the dataset in your working directory as `consumercomplaints.csv`.

---

## 🛠️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/consumer-complaint-classification.git
cd consumer-complaint-classification

2️⃣ Install Dependencies
pip install pandas numpy scikit-learn nltk

3️⃣ Run the Script
python consumer_complaint_classification.py

📈 Model Training

Text Preprocessing: Clean text, remove stopwords, apply stemming

Feature Extraction: CountVectorizer

Model: SGDClassifier from sklearn.linear_model

Evaluation: Accuracy score on training and testing data

📷 Sample Workflow

Load dataset

Clean and preprocess complaint narratives

Vectorize text into numerical form

Train SGDClassifier

Evaluate model performance

🔮 Future Improvements

Experiment with TF-IDF Vectorizer for better feature representation

Use advanced models like Logistic Regression, Random Forest, or BERT

Build a simple Flask API or Streamlit Web App for live complaint classification

🤝 Contributing

Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License

This project is open-source and available under the MIT License.
