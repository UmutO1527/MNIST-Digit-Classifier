# MNIST-Digit-Classifier
A simple handwritten digit classification project built using TensorFlow and Keras.  This project trains a neural network on the MNIST dataset to recognize handwritten digits from 0–9.

```markdown
## Features
* **Built with TensorFlow/Keras**
* **Uses the MNIST handwritten digit dataset**
* **Fully connected neural network**
* **Image normalization**
* **Prediction visualization with Matplotlib**
* **Achieves ~98% test accuracy**

## Technologies Used
* Python
* TensorFlow
* Keras
* Matplotlib

## Project Structure
```text
MNIST-Digit-Classifier/
│
├── mnist_classifier.py
├── requirements.txt
└── README.md

```

## Installation

1. Clone the repository:

```bash
   git clone https://github.com/UmutO1527/MNIST-Digit-Classifier.git
   cd MNIST-Digit-Classifier

```

2. Install dependencies:

```bash
   pip install -r requirements.txt

```

### Requirements

```text
tensorflow
matplotlib

```

## Model Architecture

The neural network consists of:

> **Input Layer** (28x28)
> ↓
> **Flatten Layer**
> ↓
> **Dense Layer** (512 neurons, ReLU)
> ↓
> **Output Layer** (10 neurons, Softmax)

## Training

The model is trained using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Epochs:** 20

## Example Output

```text
Accuracy: 0.98

Prediction: 7
Actual Label: 7

```

## Sample Prediction Visualization

The project displays the tested handwritten digit using Matplotlib and prints:

* Predicted label
* Actual label

## Learning Goals

This project was created to understand:

* Neural networks
* Dense layers
* Activation functions
* Forward propagation
* Image classification
* Deep learning workflows

## Future Improvements

* [ ] Add Convolutional Neural Networks (CNNs)
* [ ] Build a web interface
* [ ] Train on custom handwriting
* [ ] Add confusion matrix visualization
* [ ] Export trained model
* [ ] Real-time digit recognition

## License

[MIT License](https://www.google.com/search?q=LICENSE)

## Author

**Developed by Umut

AI & Engineering Student passionate about building intelligent systems from first principles.**

```

```
