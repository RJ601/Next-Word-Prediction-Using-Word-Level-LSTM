# 📜 Next-Word Prediction Using Word-Level LSTM on Shakespearean Text

An AI model that predicts the **next word** in a sentence using a word-level LSTM, trained on Shakespearean plays.

---

# ✨ Features

* 🔠 **Word-level tokenization** for deeper semantic understanding.
  ![image](https://github.com/user-attachments/assets/31224c58-d7b2-4917-8f65-91e6ed400676)

* 🤖 **LSTM-based Sequential model** trained on Harry Potter and Percy Jackson books.
  ![image](https://github.com/user-attachments/assets/71a9ef98-2df3-4e87-bf41-b378e4648a34)

* 📊 **Model comparison** across different LSTM layers and architectures in `Model_Comparisons.csv`.
  
* 📉 **Loss graphs** included for visualizing training performance.
  ![image](https://github.com/user-attachments/assets/1e218046-db1d-49f0-afda-acdeda50d580)

* 💾 Manual selection and saving of the most efficient model based on results as "model.keras".

⚠️ **Restrictions**:

* Requires **at least 7 words** in the input sentence for prediction.

> *(Images and visualizations will be added soon)*

---

# 🛠 Installation and Setup

1. **Clone the repository**:

```bash
git clone https://github.com/RJ601/Next-Word-Prediction-Using-Word-Level-LSTM.git
cd Next-Word-Prediction-Using-Word-Level-LSTM
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

---

# 🚀 Usage

To **train the model**:
👉 Open `LSTM_Model_Training.ipynb`, optionally modify the hyperparameters, and run all cells.

In a different file, load the model:
from tensorflow.keras.models import load_model
model = load_model("model.keras")

---

# 🔧 Tools, Libraries, and Dataset

* **Platform**: Jupyter Notebook
* **Language**: Python 3.9.23

**Libraries Used**:

* `tensorflow==2.19.0`
* `keras==3.10.0`
* `scikit-learn==1.6.1`
* `matplotlib==3.9.4`
* `numpy==2.0.2`
* `pandas==2.3.0`
* `nltk==3.9.1`

---

# 📝 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, or share it with attribution.
