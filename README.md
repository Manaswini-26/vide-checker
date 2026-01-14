# 🧠 The Vibe Checker

The **Vibe Checker** is a beginner-friendly AI-powered web application built using **Streamlit** and **Hugging Face Transformers**. It analyzes user-input text and predicts whether the sentiment (or *vibe*) of the text is **Positive** or **Negative**.

This project is ideal for students starting with **AI/ML**, **NLP**, and **Streamlit app development**.

---

## 🚀 Features

* 🧠 AI-based sentiment analysis using a pre-trained Transformer model
* ⚡ Fast and efficient model loading with caching
* 🎨 Clean and interactive Streamlit UI
* 🎈 Fun animations for positive sentiment
* 🟢 Handles empty input safely

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – for building the web interface
* **Transformers (Hugging Face)** – for sentiment analysis
* **DistilBERT model** (used internally by the pipeline)

---

## 📂 Project Structure

```
vibe-checker/
│
├── app.py          # Main Streamlit application
├── README.md       # Project documentation
└── requirements.txt
```

---

## 📦 Requirements

Create a `requirements.txt` file with the following content:

```
streamlit
transformers
torch
```

---

## ▶️ How to Run the Project

1. **Clone the repository** (or download the code)

   ```bash
   git clone <your-repo-link>
   cd vibe-checker
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```

4. Open the browser link shown in the terminal (usually `http://localhost:8501`)

---

## 🧪 How It Works

1. User enters text into the input box
2. The text is passed to a **sentiment-analysis pipeline**
3. The model returns:

   * `label`: POSITIVE or NEGATIVE
   * `score`: confidence value (0 to 1)
4. The result is displayed with visual feedback

---

## 🧠 Model Used

* Hugging Face **sentiment-analysis** pipeline
* Default lightweight model: **distilbert-base-uncased-finetuned-sst-2-english**
* Chosen for speed and accuracy

---

## 📊 Example Input & Output

**Input:**

```
I love coding with Python!
```

**Output:**

```
Positive Vibe Detected! (Confidence: 0.99)
```

---

## 📈 Time & Space Complexity

* **Inference Time:** O(n) where n = number of tokens in input text
* **Space:** Model loaded once and cached in memory

---

## 👩‍🎓 Ideal For

* Beginners in AI/ML
* NLP starters
* Streamlit learning projects
* Resume / LinkedIn / Internship showcase

---

## 🌟 Future Enhancements

* Add Neutral sentiment
* Support multi-language input
* Emotion detection (happy, sad, angry, etc.)
* Deploy on Streamlit Cloud

---

## 📌 Author

**Manaswini (Manu)**
Computer Science Student – Data Science Specialization

---

## 📜 License

This project is for educational purposes and open for learning and experimentation.
