#  Spam SMS Detection using Deep Learning and NLP

A machine learning project that classifies SMS messages as **spam** or **ham (not spam)** using **Natural Language Processing (NLP)** and a **Deep Neural Network (TensorFlow/Keras)**.  
The model combines **TF-IDF vectorization** with **deep learning** to achieve reliable spam detection with confidence scoring.

---

## ⚡ Features
- ✅ Preprocesses SMS messages (cleaning, stopword removal, stemming).  
- ✅ Extracts features with **TF-IDF (unigrams + bigrams, max 5000 features)**.  
- ✅ Implements a **Neural Network with TensorFlow/Keras**.  
- ✅ Trains with **dropout regularization** for robustness.  
- ✅ Provides a **prediction function** that outputs labels and confidence levels.  

---

## 📂 Project Structure
- `model.ipynb` → Jupyter Notebook with full implementation.  
- `requirements.txt` → Python dependencies.  
- `README.md` → Project documentation.  

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spam-sms-detector.git
cd spam-sms-detector

# Create a virtual environment :
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


▶️ Usage
Run the notebook:
jupyter notebook model.ipynb
Or use the predict_message function inside the notebook:
predict_message("Congratulations! You’ve won a free ticket to Bahamas!")

Example output:
Prediction: spam (confidence: 0.9821)

📊 Dataset
The project uses the SMS Spam Collection dataset available at:
SMS Spam Dataset

📌 Requirements
Python 3.8+
TensorFlow / Keras
Scikit-learn
Pandas, NumPy
NLTK
Matplotlib


🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.

📜 License
MIT
