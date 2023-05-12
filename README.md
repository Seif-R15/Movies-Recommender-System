# Movies-Recommender-System
# Sentiment Analysis using BERT on IMDB Dataset

This repository contains code for training a sentiment analysis model using BERT on the IMDB dataset. The code is written in Python and uses the ktrain library, which provides a simple and intuitive interface for training deep learning models.

# Requirements
To run this code, you will need the following:

- Python 3.6 or higher
- TensorFlow 2.0 or higher
- Keras 2.2 or higher
- ktrain 0.27 or higher
- NumPy 1.16 or higher

You can install the required packages using the following command:

pip install -r requirements.txt

# Usage

To train the model, simply run the train.py script:

To run the script, type `python train.py` in the command line.

The script will download the IMDB dataset, preprocess the data using BERT, and train the sentiment analysis model using one-cycle learning rate policy. The trained model will be saved in the model directory.

To test the model, you can run the predict.py script and provide a sample text:

python predict.py "This movie was great!"

The script will load the trained model and predict the sentiment of the given text.

# License
This code is licensed under the MIT License. You are free to use, modify, and distribute this code for any purpose, as long as you include the original copyright notice and the license terms.

# Acknowledgements
The code in this repository is based on the ktrain tutorial by Arun S. Maiya. The IMDB dataset is provided by Andrew Maas.
