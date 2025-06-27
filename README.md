
# 🏠 House Price Prediction System using Machine Learning

This project predicts house prices based on various features like area, number of rooms, garage area, and overall quality using a machine learning model trained on the Kaggle House Prices dataset.

---

## 🚀 Features
- Cleaned and preprocessed dataset from Kaggle
- Trained using Regression Models (Linear, Ridge, Lasso, etc.)
- Feature importance analysis
- Predict house prices using custom input
- Well-organized codebase for training and prediction

---

## 📁 Project Structure

```

House-Price-Prediction-ML/
│
├── Config/
│   └── kaggle.json
│
├── Data/
│   ├── data\_description.txt
│   ├── sample\_submission.csv
│   ├── test.csv
│   └── train.csv
│
├── Models/
│   ├── model.pkl
│   ├── models.pkl
│   └── features.pkl
│
├── main.py            # Training and model saving
├── predict.py         # Prediction based on user input
├── requirements.txt
└── README.md

````

---

## 📦 Dependencies

Install all required libraries:

```bash
pip install -r requirements.txt
````

---

## 🧠 Model Training

To train the model:

```bash
python main.py
```

---

## 🔮 Predict House Price

To predict a price based on manual inputs:

```bash
python predict.py
```

---

## 📊 Dataset

This project uses the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset from Kaggle.

---

## 📌 Author

**Vaibhav Waghalkar**
🔗 [LinkedIn](https://www.linkedin.com/in/vaibhav-waghalkar-848885343/)
💻 [GitHub](https://github.com/Vaibhav-Waghalkar)

---

## ⭐️ Show Your Support

If you like this project, give it a ⭐️ and share it with others!

---

## ✅ Before pushing to GitHub

Add a `.gitignore` file:

```
__pycache__/
*.pkl
*.csv
*.json
```

> ⚠️ **Note:** Do **NOT** upload your `kaggle.json` if it contains private API keys. Either delete it or include it in `.gitignore`.

```

---

You're all set to publish it now, bro! Want me to help you create a GitHub project banner or badge icons?
```
