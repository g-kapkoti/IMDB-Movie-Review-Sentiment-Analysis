# IMDB Movie Review Sentiment Analysis

Live Demo: https://imdb-movie-review-sentiment-analysis-main.streamlit.app/

This project is a Streamlit web application that classifies IMDB movie reviews as positive or negative using a pre-trained Simple RNN model.

## Features
- User-friendly Streamlit interface
- Enter any movie review and get instant sentiment prediction
- Uses IMDB dataset word index for preprocessing
- Loads a pre-trained Keras RNN model for inference

## How It Works
1. User enters a movie review in the text area.
2. The review is preprocessed and converted to a padded sequence using the IMDB word index.
3. The model predicts the sentiment (positive/negative) and displays the probability score.

## Files
- `main.py`: Streamlit app for sentiment analysis
- `simple_rnn_model_imdb.h5`: Pre-trained Keras RNN model

## Getting Started
1. Clone the repository or copy the project folder.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run main.py
   ```

## Requirements
- Python 3.7+
- Streamlit
- TensorFlow
- Numpy

## Usage
- Enter a movie review in the app and click "Classify" to see the sentiment prediction.

## License
This project is for educational purposes.
