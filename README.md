# 🧠 Project Phase Classification (Synthetic Data)

This project demonstrates a simple machine learning pipeline to classify project activities into four key project management phases using synthetic data. It is ideal for prototyping intelligent project tracking systems, educational tools, or automation platforms.

---

## 📁 Dataset

The dataset consists of **200 synthetic samples** (50 per phase) across the following project lifecycle stages:

1. **Initiation**
2. **Planning**
3. **Execution**
4. **Closure**

Each sample includes:
- `description`: A brief text simulating a project-related task or activity
- `phase`: The corresponding project management phase

The dataset is saved in Excel format:

📄 `project_phase_classification_data.xlsx`

---

## 🛠️ How It Works

- **Text Features**: TF-IDF vectorization
- **Model**: Logistic Regression (multi-class)
- **Accuracy**: >90% on clean synthetic data

### Code Overview

1. **Data Generation**: Synthetic project activity data is randomly generated
2. **Model Pipeline**: TF-IDF + Logistic Regression using `sklearn`
3. **Evaluation**: Accuracy and classification report
4. **Prediction**: Model predicts phase of a new input description

---

## 🔧 Requirements

- Python 3.7+
- pandas
- scikit-learn
- openpyxl

Install via pip:

```bash
pip install pandas scikit-learn openpyxl

🚀 Quick Start

# Train and test the classifier
python project_phase_classifier.py

📊 Example Prediction

new_description = ["Team is closing out the project and collecting feedback"]
# Output: Closure

📜 License

This project is open-source and free to use for educational and research purposes.


---

Would you like me to save this as a downloadable `README.md` file too?

