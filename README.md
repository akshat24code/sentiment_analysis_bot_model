# 🤖 AI Sentiment Analysis Web App

A Machine Learning-powered web application that performs real-time sentiment analysis using Hugging Face Transformers and Gradio. Users can enter any sentence and instantly receive a sentiment prediction (Positive or Negative) along with the model's confidence score.

---

## 📚 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine the emotional tone behind a piece of text. This project leverages a pre-trained Transformer model from Hugging Face and provides an interactive web interface using Gradio.

This project was built as a hands-on learning exercise to understand:

- Natural Language Processing (NLP)
- Pre-trained Transformer Models
- Hugging Face Pipelines
- Machine Learning Deployment
- Gradio Web Applications

---

## 🚀 Features

✅ Real-time sentiment prediction

✅ User-friendly web interface

✅ Positive and Negative sentiment classification

✅ Confidence score visualization

✅ Powered by Hugging Face Transformers

✅ Interactive Gradio deployment

---

## 📸 Application Demo

<p align="center">
  <img src="images/sentiment-analysis-demo.png" alt="Sentiment Analysis Bot" width="100%">
</p>

The application analyzes user input text and predicts whether the sentiment expressed is **Positive** or **Negative** using a pre-trained Transformer model.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core Programming Language |
| Hugging Face Transformers | Sentiment Analysis Model |
| Gradio | Interactive Web Interface |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Structure

```bash
Sentiment-Analysis-Bot/
│
├── Sentimental_Analysis_bot.ipynb
├── README.md
│
└── images/
    └── sentiment-analysis-demo.png
```

---

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/sentiment-analysis-bot.git
```

```bash
cd sentiment-analysis-bot
```

### Install Required Libraries

```bash
pip install transformers gradio
```

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook
```

Run all cells in:

```bash
Sentimental_Analysis_bot.ipynb
```

The Gradio application will launch automatically and generate a local/public URL.

Enter any sentence and click **Submit** to get sentiment predictions.

---

## 💡 Example

### Input

```text
I love this product!
```

### Output

```text
POSITIVE
Confidence: 99%
```

---

### Input

```text
This is the worst experience ever.
```

### Output

```text
NEGATIVE
Confidence: 99%
```

---

## 🧠 Machine Learning Model

This project uses Hugging Face's sentiment analysis pipeline:

```python
from transformers import pipeline

classifier = pipeline("sentiment-analysis")
```

The model is pre-trained and capable of classifying text into:

- Positive Sentiment
- Negative Sentiment

without requiring additional training.

---

## 🎯 Learning Outcomes

By building this project, I learned:

- Fundamentals of Sentiment Analysis
- Working with Hugging Face Transformers
- Using Pre-trained NLP Models
- Creating Interactive Apps with Gradio
- Deploying Machine Learning Models
- Rapid AI Prototyping

---

## 🔮 Future Improvements

- Add Neutral Sentiment Detection
- Multi-language Support
- Emotion Detection (Happy, Sad, Angry, Fear, etc.)
- Batch Text Analysis
- Dashboard for Sentiment Trends
- Deploy on Hugging Face Spaces
- Deploy on Streamlit Cloud
- Integrate with Social Media APIs

---

## 🙏 Acknowledgements

This project was inspired by the tutorial:

**"Build a Live Machine Learning App in 5 Minutes"**
by Aman Kharwal.

The tutorial provided guidance on building a sentiment analysis application using Hugging Face Transformers and Gradio. This implementation was developed as a learning project to understand Machine Learning deployment and NLP applications.

Special thanks to Aman Kharwal for creating educational content that helps beginners learn Artificial Intelligence and Machine Learning.

---

## 👨‍💻 Author

### Akshat Sharma

Computer Science Engineering (Data Science)

Passionate about:
- Data Science
- Machine Learning
- Artificial Intelligence
- Product Analytics
- Software Development

---

⭐ If you found this project helpful, consider giving it a Star on GitHub!
