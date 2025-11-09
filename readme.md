# 🧠 Automatic Text Classifier

This project automatically classifies text into categories (for example, Positive or Negative) using **Machine Learning (ML)**.  
It is a simple but effective demonstration of **text preprocessing, feature extraction, and model prediction**.

---

## 🚀 Features
- Converts text into numerical form using **TF-IDF Vectorizer**
- Uses **Naïve Bayes Classifier** for prediction
- Takes user input and predicts sentiment in real-time
- Lightweight and beginner-friendly project for ML students

---

## 🧩 How It Works
1. Collects small sample data (positive & negative sentences)  
2. Vectorizes the text using TF-IDF  
3. Trains a Naïve Bayes model  
4. Accepts a new sentence from the user  
5. Predicts and prints the result (Positive / Negative)

---

## 💻 Installation & Usage
```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/Automatic-Text-Classifier.git

# 2. Go inside the folder
cd Automatic-Text-Classifier

# 3. Install required package
pip install scikit-learn

# 4. Run the program
python text_classifier_demo.py