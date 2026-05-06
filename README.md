# 🌲 Forest Fire Prediction

This project predicts the likelihood of forest fires using machine learning techniques. It involves data preprocessing, model training, evaluation, and saving the trained model for future use.

---

## 📌 Features

* Data preprocessing and cleaning
* Train-test split
* Machine learning model training
* Accuracy evaluation
* Model saving using pickle
* Model loading for predictions

---

## 🧠 Tech Stack

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Pickle

---

## 📂 Project Structure

```
ForestFirePrediction.ipynb   # Main notebook
model.pkl                    # Saved trained model (generated after training)
README.md                    # Project documentation
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/forest-fire-prediction.git
```

2. Navigate to the project folder:

```
cd forest-fire-prediction
```

3. Install dependencies:

```
pip install -r requirements.txt
```

*(If you don’t have requirements.txt, install manually: pandas, numpy, scikit-learn)*

---

## ▶️ How to Run

1. Open Jupyter Notebook:

```
jupyter notebook
```

2. Open:

```
ForestFirePrediction.ipynb
```

3. Run all cells step by step

---

## 📊 Workflow

* Data Processing
* Train-Test Split
* Model Training
* Accuracy Evaluation
* Model Saving
* Model Loading & Prediction

---

## 💾 Model Saving

The trained model is saved using pickle:

```
pickle.dump(model, open('model.pkl', 'wb'))
```

---

## 🔄 Model Loading

```
model = pickle.load(open('model.pkl', 'rb'))
```

---

## 📈 Results

The model is evaluated using accuracy score on training and test data.yes

---

## 🚀 Future Improvements

* Improve model accuracy
* Add more features
* Deploy as a web app
* Add visualization dashboard

---

## 👤 Author

gajendra0008


---

## ⭐ If you like this project, give it a star!
