# EMNIST Letter Classification

Classifies handwritten English letters (A–Z) using Deep Learning.

## Dataset
- EMNIST Letters (28x28 grayscale images, 26 classes)  
- Automatically downloaded in the notebook

## Model
- Fully connected neural network (1 hidden layer, 128 neurons)  
- ReLU activation  
- Output: 26 classes (A–Z)

## Training
- Optimizer: Adam  
- Loss: CrossEntropyLoss  
- Batch size: 64  
- Epochs: 5  
- Test Accuracy: ~87%

## How to Use
1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. The model will download the dataset, train, and evaluate automatically  
4. Optionally, test your own letters by converting images to 28x28 grayscale

## Libraries
- torch  
- torchvision  
- matplotlib
