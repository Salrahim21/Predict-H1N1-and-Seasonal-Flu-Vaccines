# 💉 Predict H1N1 and Seasonal Flu Vaccines

This project uses machine learning techniques to predict whether individuals are likely to receive the **H1N1** and **seasonal flu** vaccines based on various health and demographic features.

## 🧠 Project Overview

- **Goal**: Predict the likelihood of individuals getting vaccinated.
- **Dataset**: H1N1 Flu Vaccine Prediction dataset (commonly from the DrivenData competition).
- **Features**: Includes demographics, behavioral responses, health background, and opinion features.
- **Modeling**: Binary classification using models like Logistic Regression, Random Forest, XGBoost, etc.

## 📂 Project Structure

```
Predict-H1N1-and-Seasonal-Flu-Vaccines/
├── Notebook.ipynb              # Main analysis and modeling notebook
├── data/                       # Contains training and test datasets
├── models/                     # Trained models (optional)
├── src/                        # Python scripts for modular code (optional)
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Salrahim21/Predict-H1N1-and-Seasonal-Flu-Vaccines.git
   cd Predict-H1N1-and-Seasonal-Flu-Vaccines
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook**
   Open `Notebook.ipynb` in Jupyter Notebook or JupyterLab and execute the cells step-by-step.

## 📊 Evaluation Metrics

- Accuracy
- Precision & Recall
- F1-Score
- ROC-AUC

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Future Enhancements

- Hyperparameter tuning and model ensembling
- Deployment via Flask or Streamlit
- Handling class imbalance using advanced techniques

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Salrahim21**  
GitHub: [@Salrahim21](https://github.com/Salrahim21)
