# Binary Classification on Movie Reviews (IMDB Sentiment Analysis)

This project implements a binary sentiment analysis model on the IMDB movie reviews dataset using deep learning (Keras). The notebook is compatible with Google Colab and demonstrates all steps from data loading and preprocessing to model building, training, and evaluation.

## Features
- Loads and preprocesses the IMDB movie review dataset
- Vectorizes text data for neural network input
- Builds a simple feedforward neural network with Keras
- Trains and validates the model
- Plots training and validation loss

## Technologies Used
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib

## How to Run
1. Open the notebook (`BinaryClassificationOnMovieReviews.ipynb`) in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Run all cells in order. The IMDB dataset is automatically downloaded via Keras.
3. (Optional) If running locally, make sure to install the dependencies listed in `requirements.txt`:

    ```
    pip install -r requirements.txt
    ```

## Results
- Achieved high validation accuracy on the IMDB dataset (see notebook for details).
- Training and validation loss/accuracy plots are included.

## Dataset
- [IMDB Movie Reviews Dataset](https://keras.io/api/datasets/imdb/)

## Author
- Amirfarhad
