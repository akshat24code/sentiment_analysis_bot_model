# 🤖 Sentiment Analysis Bot

A simple AI-powered Sentiment Analysis Web App built using **Hugging Face Transformers** and **Gradio**. The application analyzes user-entered text and predicts whether the sentiment is **Positive** or **Negative**.

## 🚀 Features

- Real-time sentiment analysis
- User-friendly web interface with Gradio
- Uses a pre-trained Hugging Face Transformer model
- Displays sentiment prediction with confidence score
- Easy to run and customize

## 🛠️ Technologies Used

- Python
- Transformers (Hugging Face)
- Gradio

## 📂 Project Structure

```bash
Sentimental_Analysis_bot.ipynb
```

## 📦 Installation

Install the required dependencies:

```bash
pip install transformers
pip install gradio
```

Or install both together:

```bash
pip install transformers gradio
```

## ▶️ How It Works

1. The user enters a sentence.
2. The Hugging Face sentiment analysis pipeline processes the text.
3. The model predicts the sentiment.
4. The result is displayed through a Gradio web interface.

## 💻 Usage

Run the notebook and execute all cells.

The application will launch a local Gradio interface where users can enter text and receive sentiment predictions.

Example Inputs:

```text
I love this product!
```

Output:

```text
POSITIVE
```

Example:

```text
This is the worst experience ever.
```

Output:

```text
NEGATIVE
```

## 🧠 Model Used

This project uses the default Hugging Face:

```python
pipeline("sentiment-analysis")
```

which automatically loads a pre-trained sentiment classification model.

## 📸 Application Interface

The web application contains:

- Text input box
- Sentiment prediction output
- Confidence score visualization

## 🔮 Future Improvements

- Add Neutral sentiment detection
- Support multiple languages
- Emotion detection (Happy, Sad, Angry, etc.)
- Deploy on Hugging Face Spaces
- Deploy on Streamlit Cloud or Render

## 📖 Learning Outcomes

Through this project, you will learn:

- How to use pre-trained NLP models
- Sentiment analysis fundamentals
- Building web interfaces using Gradio
- Integrating AI models into applications
- Rapid prototyping with Hugging Face Transformers

## 🙏 Acknowledgements

This project was inspired by the tutorial:

**Build a Live Machine Learning App in 5 Minutes**
by Aman Kharwal

The original tutorial provided guidance on building a sentiment analysis application using Hugging Face Transformers and Gradio. This project was developed as a learning exercise to understand Machine Learning model deployment and interactive web applications.

Special thanks to Aman Kharwal for sharing educational content that helps beginners learn AI and Machine Learning concepts.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
