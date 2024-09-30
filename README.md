# Fashion MNIST Classification using CNN (TensorFlow/Keras)

This project demonstrates how to classify images of clothing items into 10 categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The dataset used is the Fashion MNIST dataset, which consists of 60,000 28x28 grayscale images of clothing items belonging to 10 categories such as shirts, shoes, bags, and more.

## Dataset

The Fashion MNIST dataset contains:
- **Training set**: 60,000 images
- **Test set**: 10,000 images

Each image is 28x28 pixels and belongs to one of the following categories:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Project Objective

The goal is to build a CNN that can classify these clothing items with high accuracy using the Fashion MNIST dataset.

## Model Architecture

The model consists of:
1. Convolutional Layers (Conv2D)
2. MaxPooling Layers
3. Dense (Fully Connected) Layers

**Optimizer**: Adam  
**Loss Function**: Sparse Categorical Crossentropy

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Fashion-MNIST-Classification.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Fashion_MNIST.ipynb
    ```

### Dependencies
- TensorFlow
- Matplotlib
- Seaborn

## Training Results

The model was trained on the Fashion MNIST dataset, and it achieved the following results:
- **Training Accuracy**: ~93%
- **Test Accuracy**: ~91%

Here are some example outputs from the trained model:

![Output Image 1](images/example_output_1.png)
![Output Image 2](images/example_output_2.png)

![Training Accuracy vs Loss](images/training_accuracy_loss.png)

## Conclusion

This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) in image classification tasks. By using a well-known dataset like Fashion MNIST, we can showcase the power of deep learning in solving real-world problems like clothing item recognition.
