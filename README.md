Task 1 — Image Classification using a CNN

A Convolutional Neural Network implemented entirely from first principles in NumPy (Conv2D, ReLU, MaxPool2D, Dense, Softmax + Cross-Entropy, Adam optimizer, full backpropagation), trained on a handwritten-digit image dataset (MNIST-style, 8x8 grayscale, 10 classes).

Files
CNN_Image_Classification.ipynb — full notebook, already executed, with all outputs and plots.
CNN_Report.pdf — full report: objective, architecture, source code, console output, figures, evaluation, observations.
models/cnn_digits_model.pkl, models/cnn_digits_model.npz — the trained model weights, in two formats.

Result :
97.04% test accuracy on a held-out test set.

Running :
Open CNN_Image_Classification.ipynb in Jupyter, VS Code, or Google Colab, and run all cells top-to-bottom. Requires numpy, matplotlib, seaborn, and scikit-learn.
