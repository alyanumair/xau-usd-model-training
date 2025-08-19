# Gold Trading Model

This repository contains a Jupyter Notebook (`xau_usd.ipynb`) for training machine learning models on **XAU/USD (Gold vs. US Dollar)** historical data.  
The focus is on **data preprocessing, feature engineering, model training, and evaluation**.  

⚠️ **Important Notice**  
- The **dataset** is not included.  
- The **trained model weights** are not included.  
- The **inference file for sending trading signals to Telegram** is not included.  

These have been excluded due to ongoing research work and confidentiality agreements.  
This repository only provides the **training pipeline code**.  

---

## 📂 Project Structure

```
├── xau_usd.ipynb     # Jupyter Notebook with the complete training pipeline
└── README.md         # Project documentation
```

---

## 🚀 Features

- Preprocessing pipeline for financial time series (XAU/USD)  
- Feature engineering using technical indicators  
- Machine learning model training and evaluation (classification/regression)  
- **Tailored for 1H (one-hour) candlestick/timestamp data**  
- **Trading strategy focused on short-term scalping**  
- Modular code that can be extended to other assets or datasets  

---

## ⚙️ Requirements

- Python 3.8+  
- Jupyter Notebook  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  

---

## 📊 Usage

1. Clone the repository:  

```bash
git clone https://github.com/alyanumair/gold-trading-model.git
cd gold-trading-model
```

2. Open the notebook:  

```bash
jupyter notebook xau_usd.ipynb
```

3. Load your own dataset (CSV/Parquet) inside the notebook.  

4. Run the notebook to:  
   - Preprocess the data  
   - Engineer features  
   - Train models  
   - Evaluate performance  

---

## 📜 License

This project is licensed under the MIT License.  
