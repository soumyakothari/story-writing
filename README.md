# story-writing
A character-level deep learning project that generates creative text by predicting the next character in a sequence. This project compares the performance of Simple RNN, GRU, and LSTM models for story writing tasks using TensorFlow/Keras.
# 🧠 AI Story Generation using LSTM, GRU, and RNN

This project explores the use of character-level deep learning models (Simple RNN, GRU, and LSTM) for automatic story generation. Each model learns to predict the next character in a sequence, enabling it to generate creative and fluent narratives from scratch.

---

## 📌 Project Goals

- Implement three recurrent neural network architectures: Simple RNN, GRU, and LSTM.
- Train all models on the same dataset for fair comparison.
- Analyze model performance using accuracy, loss, and story quality.
- Compare the output of each model for creativity and coherence.

---

## 🛠️ Technologies Used

- Python 3.10+
- TensorFlow / Keras
- NumPy, Matplotlib
- Jupyter Notebook / Google Colab

---

## 📂 Directory Structure

- `data/` → Raw text data for training  
- `models/` → LSTM, GRU, and RNN model code notebooks  
- `outputs/` → Sample generated stories  
- `plots/` → Accuracy/loss visualizations  
- `requirements.txt` → Python dependencies

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/StoryGen-AI.git
    cd StoryGen-AI
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run any notebook from the `models/` folder in Jupyter or Colab.

---

## 📈 Comparative Results

| Model      | Accuracy | Final Loss | Story Quality         |
|------------|----------|------------|------------------------|
| Simple RNN | ~85%     | 0.31       | Repetitive             |
| GRU        | ~93%     | 0.19       | Coherent               |
| LSTM       | ~95%     | 0.14       | Fluent, context-aware  |

---

## 📖 Sample Output (LSTM)

> "the man walked slowly into the dark room, unaware of the eyes that followed him. the silence was heavy, broken only by..."

---

## 📌 License

This project is for educational and research purposes.  
Add a LICENSE file if you plan to open source it.

---

## ✨ Author

- soumya kothari (E23BCAU0041)  
- Course: Intelligent Model Design Using AI  
- Supervisor: Dr. Greeta Pinheiro
