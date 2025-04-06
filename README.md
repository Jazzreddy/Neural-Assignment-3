# Neural-Assignment-3

Student Information
Name: Jaswanth Reddy Donapati Course: CS5720 Neural Networks and Deep Learning
Semester: Spring 2025
University: University of Central Missouri
Student ID : 700757646 Submission Date: 04/06/2025

Assignment Overview
This assignment consists of four tasks involving Autoencoders and Recurrent Neural Networks (RNNs). The tasks include implementing a basic autoencoder, a denoising autoencoder, a character-based text generation model using LSTMs, and a sentiment classification model using an LSTM network.

Q1: Implementing a Basic Autoencoder
Description:
An autoencoder is a neural network used to reconstruct its input. In this task:

The MNIST dataset is used.
The encoder compresses input images into a latent space (dimension = 32).
The decoder reconstructs images from this compressed representation.
Steps:
Load the MNIST dataset.
Define an autoencoder using fully connected Dense layers.
Train the model using binary cross-entropy loss.
Visualize original vs. reconstructed images.
Experiment with different latent space sizes (16, 64) to analyze reconstruction quality.
Q2: Implementing a Denoising Autoencoder
Description:
A denoising autoencoder is trained to remove noise from images. This task modifies the previous autoencoder by:

Adding Gaussian noise to input images.
Training the model to reconstruct clean images.
Comparing results between the standard and denoising autoencoders.
Steps:
Modify the autoencoder to accept noisy input images.
Train the model while keeping the output as clean images.
Compare reconstruction quality of noisy vs. clean images.
Explain a real-world application of denoising autoencoders (e.g., medical imaging).
Q3: Implementing an RNN for Text Generation
Description:
This task involves training an LSTM-based RNN to predict the next character in a text dataset.

Steps:
Load a text dataset (e.g., Shakespeare Sonnets).
Convert text into sequences (one-hot encoding or embeddings).
Define an LSTM-based model.
Train the model to predict the next character.
Generate new text and explain the effect of temperature scaling on randomness.
Q4: Sentiment Classification Using RNN
Description:
An LSTM-based model is used to classify IMDB movie reviews as positive or negative.

Steps:
Load the IMDB dataset.
Preprocess text data (tokenization, padding sequences).
Train an LSTM model for binary classification.
Generate a confusion matrix and classification report.
Discuss the importance of the precision-recall tradeoff in sentiment analysis.
Conclusion
This assignment demonstrated autoencoder-based image reconstruction, denoising techniques, character-based text generation using RNNs, and sentiment analysis using LSTMs. Each model was trained and evaluated based on performance metrics.
