# 📜 Next-Word Prediction Using Word-Level LSTM on Shakespearean Text

An AI model that predicts the **next word** in a sentence using a word-level LSTM, trained on Shakespearean plays.

---

# ✨ Features

* 🔠 **Word-level tokenization** for deeper semantic understanding.
* 🤖 **LSTM-based Sequential model** trained on rich Shakespearean language.
* 📊 **Model comparison** across different LSTM layers and architectures in `Model_Comparisons.csv`.
* 📉 **Loss graphs** included for visualizing training performance.
* 📆 **Saved the most efficient model** as "model.keras" for reuse.
* 🧪 **Demo notebook** that predicts the next word based on custom input.

⚠️ **Restrictions**:

* Works best with **Old English** or Shakespearean-style input.
* Requires **at least 13 words** in the input sentence for accurate prediction.

> *(Images and visualizations will be added soon)*

---

# 🛠 Installation and Setup

1. **Clone the repository**:

```bash
git clone https://github.com/RJ601/Next-Word-Prediction-Using-Word-Level-LSTM-on-Shakespearean-Text.git
cd Next-Word-Prediction-Using-Word-Level-LSTM-on-Shakespearean-Text
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

---

# 🚀 Usage

To **run predictions on custom input**:
👉 Open and run the `demo.ipynb` Jupyter notebook.

To **train the model from scratch**:
👉 Open `training.ipynb`, optionally modify the hyperparameters, and run all cells.

*(Sample output screenshot will be added here)*

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

**Dataset**: [Shakespeare Plays Dataset (Kaggle)](https://www.kaggle.com/datasets)

---

# 📝 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, or share it with attribution.
