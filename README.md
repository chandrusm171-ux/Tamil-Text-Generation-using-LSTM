# 📝 Tamil Text Generation using LSTM

This project demonstrates how to build and train a **Recurrent Neural Network (RNN)** using **LSTM layers** to generate **Tamil text**.  
The model is trained on a corpus of Tamil text (such as movie scripts, lyrics, or books) to learn language patterns and predict the next word in a sequence.

---

## 🧠 Project Overview

This notebook covers the following steps:

1. **Data Loading** – Load a Tamil text file (e.g., `tamil_movie_scripts.txt`).
2. **Text Preprocessing** – Clean and tokenize Tamil text, convert to numerical sequences.
3. **Model Creation** – Build an LSTM-based model with *Embedding, LSTM, Dense,* and *Dropout* layers.
4. **Training** – Train the model to predict the next word given a sequence of previous words.
5. **Text Generation** – Generate new Tamil sentences word-by-word using the trained model.
6. **Visualization** – Plot loss curves and monitor model performance.

---

## ⚙️ Requirements

Ensure you have **Python 3.8+** and the required libraries installed.

Install dependencies using:

```bash
pip install numpy tensorflow matplotlib
```

---

## 🚀 How to Use

### 1️⃣ Clone this repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2️⃣ Prepare your dataset

Place your Tamil text file (e.g., `tamil_movie_scripts.txt`) in the same directory as the notebook.

### 3️⃣ Open the notebook

```bash
jupyter notebook f7087043-6d3b-4e2f-b665-44bc2e89397d.ipynb
```

### 4️⃣ Run all cells to:

- Load and preprocess your Tamil text.
- Train an LSTM model.
- Generate sample Tamil text.

Modify settings inside the notebook:

```python
file_name = "tamil_movie_scripts.txt"
```

Replace it with your own text file if needed.

---

## 📊 Output

After training, the notebook will:

- Display the training loss over epochs.
- Generate sample Tamil text sequences.
- Optionally save the trained model for reuse.

### Example project structure:

```
.
├── Tamil Text Generation using LSTM.ipynb   # Main notebook
├── tamil_movie_scripts.txt                      # Tamil text dataset
└── README.md                                    # Project documentation
```

---

## 🔧 Customization Ideas

- Train on larger Tamil datasets for improved fluency.  
- Experiment with different sequence lengths or embedding dimensions.  
- Add GRU or Transformer layers for advanced generation.  
- Fine-tune on specific domains (e.g., literature, news, or social media text).  

---

## 🧩 Future Enhancements

- Build a web app using **Streamlit** or **Gradio** for interactive Tamil text generation.  
- Integrate **beam search** or **temperature sampling** for better text diversity.  
- Add support for **multilingual text generation**.  

---

## 🙏 Acknowledgements

- [TensorFlow & Keras](https://www.tensorflow.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- Tamil language resources and open datasets
