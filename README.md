# Machine Learning Labs

Supervised learning and deep learning work from **Intro to AI (DDSC201)** and **Applied Machine Learning (DDSC405)**.

| Notebook | Task | Methods |
|---|---|---|
| [`01_multiple_linear_regression_startups`](notebooks/01_multiple_linear_regression_startups.ipynb) | Predict startup profit from R&D, admin and marketing spend | Multiple linear regression, EDA |
| [`02_logistic_regression_titanic`](notebooks/02_logistic_regression_titanic.ipynb) | Predict Titanic survival | Logistic regression, encoding, scaling, confusion matrix, F1 |
| [`03_neural_network_classifier_keras`](notebooks/03_neural_network_classifier_keras.ipynb) | Binary classification on the Breast Cancer Wisconsin dataset | Keras `Sequential` dense network, Adam |
| [`04_transfer_learning_resnet_mobilenet`](notebooks/04_transfer_learning_resnet_mobilenet.ipynb) | Compare pretrained CNNs on CIFAR-10 | Transfer learning with ResNet50, ResNet101 and MobileNetV3Large (accuracy vs. training time) |

Datasets for notebooks 01 and 02 are in [`data/`](data). For 03, download `breast-cancer.csv` from Kaggle into `data/`. CIFAR-10 loads automatically through Keras.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```
**Stack:** Python · scikit-learn · TensorFlow/Keras
