#Image Classification with FastAI and PyTorch
This project demonstrates how to perform image classification using the FastAI library with a pre-trained model (ResNet50) on the EuroSat dataset. The model is fine-tuned, and predictions are displayed for random images selected from the test folder in a grid format. The code also includes data preparation, training, model evaluation, and visualizations.

Features
Image Classification: Uses the FastAI library to load and train a convolutional neural network (CNN) on the EuroSat RGB dataset.
Fine-Tuning: A pre-trained ResNet50 model is fine-tuned on the EuroSat dataset.
Random Image Predictions: Random images from the test folder are selected and their predictions are displayed in a grid format.
Grid Visualization: The random test images are displayed along with their predicted class labels using matplotlib for visualization.
Requirements
Before running this code, ensure that you have the following libraries installed:

fastai
torch
torchvision
matplotlib
kagglehub (for dataset download)
