[README.md](https://github.com/user-attachments/files/33418345/README.md)
# Fashion-MNIST Classification

A Python implementation of a **Softmax Linear Classifier** for classifying clothing images from the Fashion-MNIST dataset.

## Dataset

- **Training images:** 60,000
- **Test images:** 10,000
- **Image size:** 28 × 28 pixels
- **Classes:** 10 clothing categories

Dataset: [Fashion-MNIST on GitHub](https://github.com/zalandoresearch/fashion-mnist)

## Experiments

The classifier is trained for 100 epochs using six combinations of batch sizes and learning rates.

| Parameter | Values |
|---|---|
| Batch size | 2048, 1024, 512 |
| Learning rate | 0.001, 0.0001 |
| Loss function | Cross-Entropy Loss |

The dataset is split into 80% training data and 20% validation data.

## Evaluation

The best model is selected based on validation macro F1 score and evaluated on the test set.

Evaluation includes:

- Accuracy and macro F1 score
- Confusion matrix
- Training and validation loss plots
- Visualization of learned weights for each class

## Technologies

Python · NumPy · Matplotlib · scikit-learn · Google Colab
