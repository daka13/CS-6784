# CS-6784
Project done in Class

# CIFAR-10 Classification using CLIP Embeddings

This project demonstrates the use of CLIP (Contrastive Language-Image Pre-Training) embeddings for image classification on the CIFAR-10 dataset.

## Setup Instructions

1. Clone this repository
2. Set up a virtual environment
3. 3. Install the required packages:
4. 4. Download the CIFAR-10 dataset:
- Visit: https://www.cs.toronto.edu/~kriz/cifar.html
- Download the Python version of the CIFAR-10 dataset
- Extract the downloaded file and place the 'cifar-10-batches-py' folder in the project directory

## Running the Code

1. Open and run the Jupyter notebook `CLIP.ipynb` or run the Python script `main.py`

2. The script will:
- Load the CIFAR-10 dataset
- Visualize sample images from the train and test sets
- Load the pre-trained CLIP model
- Generate CLIP embeddings for all images
- Train a simple classifier on these embeddings
- Evaluate the model on both train and test sets

## Reproducing Results

To reproduce the results:

1. Ensure you're using the same versions of the libraries as specified in `requirements.txt`.
2. Use the same hyperparameters as defined in the script:
- CLIP model: "openai/clip-vit-base-patch32"
- Classifier hidden layer size: 256
- Learning rate: 0.001
- Number of epochs: 10
- Batch size: 64

3. Run the entire notebook or script without interruption.

## Results

After running the code, you should see similar output
