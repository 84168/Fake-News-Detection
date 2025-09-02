# 📰 Fake News Detection with LSTM

This project uses deep learning to detect fake news articles. By training an LSTM model on labeled news data, it classifies articles as real or fake based on their textual content.

## 🚀 Features

- Combines real and fake news datasets
- Cleans and tokenizes text for modeling
- Visualizes word frequency using WordClouds
- Trains an LSTM model for binary classification
- Predicts authenticity of custom news samples

## 🧠 Tech Stack

- Python (Pandas, NumPy, Matplotlib)
- TensorFlow / Keras
- Scikit-learn
- WordCloud
- Jupyter / Google Colab

## 📦 Dataset

- `True.csv`: Real news articles
- `Fake.csv`: Fake news articles
- Each labeled with `1` (real) or `0` (fake)

## 🛠️ How It Works

1. **Preprocessing**: Cleans text, merges title & body, removes noise.
2. **Tokenization**: Converts words to sequences.
3. **Modeling**: Builds an LSTM model with embedding and dropout layers.
4. **Training**: Trains on 80% of the data, validates on 20%.
5. **Evaluation**: Measures accuracy and visualizes performance.
6. **Prediction**: Tests custom news samples for classification.

## 📊 Results

- Achieved high accuracy on test data
- Visualized word clouds for real vs fake news
- Predicts new articles with confidence scores

## 🧪 Sample Prediction

```python
sample_news = ["Your custom news article here"]

