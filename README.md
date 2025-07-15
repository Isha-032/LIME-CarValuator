# 🚗 CarPriceXplainML

An advanced Car Price Prediction System using Machine Learning and Explainable AI (LIME). This project not only predicts used car prices but also explains the reasoning behind each prediction using XAI techniques.

---

## 📌 Features

- End-to-end ML pipeline with preprocessing, EDA, modeling
- Trained with Random Forest & XGBoost
- Explainable AI: LIME-based feature attribution
- Future price depreciation estimator (planned)
- Live predictions via Streamlit GUI
- Clean visualizations and model insights

---

## 🧠 Models Used

- Random Forest Regressor
- XGBoost Regressor
- LIME (Local Interpretable Model-Agnostic Explanations)

---

## 📂 Project Structure

```
CarPriceXplainML/
├── car_price_prediction.ipynb      # Main notebook
├── streamlit_app/
│   ├── app.py                      # Streamlit GUI
│   └── utils.py                    # Utility functions
├── data/                           # Dataset files
├── images/                         # Plots and screenshots
├── requirements.txt                # Python dependencies
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/CarPriceXplainML.git
cd CarPriceXplainML
pip install -r requirements.txt
jupyter notebook car_price_prediction.ipynb
```

To launch Streamlit GUI:
```bash
cd streamlit_app
streamlit run app.py
```

---

## 🧾 License

MIT License

---

## 🙋‍♀️ Author

**Isha Patel**  
GitHub: [yourusername](https://github.com/yourusername)
