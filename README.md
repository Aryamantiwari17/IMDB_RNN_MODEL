# IMDB_RNN_MODEL
## Movie Review Sentiment Analysis with RNN

This project revisits **Recurrent Neural Networks (RNN)** through a sentiment analysis task on movie reviews. Using the IMDB dataset, a simple RNN model is trained to classify reviews as **positive** or **negative**. The project demonstrates the use of TensorFlow/Keras for deep learning, and it integrates with **Streamlit** to deploy a simple web app that predicts the sentiment of a movie review entered by the user.

## Overview

The goal of this project is to classify the sentiment of movie reviews as either positive or negative. The model uses a pre-trained RNN (SimpleRNN layer) loaded from a `.h5` file, and the web interface for this model is built using **Streamlit**. Users can input movie reviews and receive real-time sentiment predictions.

## Features
- **Sentiment Classification**: Classifies user-submitted movie reviews as positive or negative.
- **Streamlit Web Interface**: An easy-to-use web interface where users can enter a movie review and get predictions.
- **Text Preprocessing**: Automatically processes and tokenizes the input text to fit the model's requirements.
- **Review Decoding**: Optionally displays the tokenized version of the user review for better understanding.

## Tech Stack
- **TensorFlow / Keras**: For building and training the RNN model.
- **IMDB Dataset**: Used for training the sentiment analysis model.
- **Streamlit**: For building a user-friendly web app interface.
- **Python**: Main programming language used throughout the project.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/rnn-sentiment-analysis.git
    cd rnn-sentiment-analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    The dependencies include:
    - TensorFlow
    - Numpy
    - Pandas
    - Streamlit

3. Download the pre-trained model and place it in the project directory. The model file should be named `simple_rnn.h5`.

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

Once the app is running, you can open your browser and input any movie review in the provided text area. Click the **Analyze Sentiment** button, and the app will predict whether the review has a positive or negative sentiment, along with the model's prediction score.

### Sample Input/Output:
![Screenshot from 2024-09-25 01-24-02](https://github.com/user-attachments/assets/5d163050-40be-4026-a5ca-f356ba5c9f9e)
![Screenshot from 2024-09-25 01-25-16](https://github.com/user-attachments/assets/44de7541-1098-40d8-b79a-62a2279fd382)


