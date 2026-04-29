# MS 22 — Theory Assignment 1  
## Multi-Output Time-Series Forecasting using LSTM & GRU

### Department of Computer Science, Faculty of Sciences  
### Jamia Millia Islamia

---

## 📌 Assignment Details

| Detail | Information |
|---|---|
| Roll No | 26 |mohd faizy
| Dataset | IOC.csv (Indian Oil Corporation) |
| Source | NIFTY-50 Stock Market Data (2000–2021), Kaggle |
| Task | Multi-Output Time-Series Forecasting |
| Framework | PyTorch (LSTM & GRU) |

---

## 📂 Dataset Information

**Dataset Used:** `IOC.csv`

The dataset contains stock market information for Indian Oil Corporation collected from the NIFTY-50 Stock Market Dataset.

### Features Used (11)

- Prev Close
- Open
- High
- Low
- Last
- Close
- VWAP
- Volume
- Turnover
- Trades
- Deliverable Volume

---

## 🎯 Objective

The objective of this assignment is to perform **multi-output time-series forecasting** using deep learning models:

- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

The models are trained to learn temporal dependencies in stock market data and predict multiple output features simultaneously.

---

## 🛠️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## ⚙️ Installation

Install required libraries using:

```bash
pip install torch numpy pandas scikit-learn matplotlib