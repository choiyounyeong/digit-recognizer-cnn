#### CSCA 5642 Introduction to Deep Learning
# Digit Recognizer (CNN)

***

# Description

The MNIST(Modified National Institute of Standards and Technology database) Digit Recognition competition is a **classic computer vision challenge** centered around a dataset of handwritten digits. Participants are tasked with **developing models to accurately classify images of digits from 0 to 9**. This dataset, released in 1999, has become a standard for benchmarking classification algorithms and serves as an ideal introduction to **deep learning, particularly convolutional neural networks (CNNs), due to its pixel-based image data.**

The competition provides a practical platform for exploring a wide range of machine learning algorithms, from traditional methods to advanced deep learning techniques. This competition is an excellent opportunity for both beginners and experienced practitioners to deepen their understanding of machine learning and gain hands-on experience with real-world data.

# Data Source

The data is sourced from the [Digit Recognizer Dataset](https://www.kaggle.com/competitions/digit-recognizer/data). (Size: 128.13 MB)

The dataset consists of **grayscale images of hand-drawn digits, ranging from zero to nine.** Each image is **28x28 pixels, totaling 784 pixels**, with pixel values indicating the brightness on a scale from 0 (white) to 255 (black). 

- Training dataset (train.csv): It includes **785 columns**, where the first column is the "label" denoting the digit, and the remaining columns contain the pixel values. These pixel columns are labeled as pixelx, where x represents the position in the **28x28 matrix, calculated as x = i * 28 + j, with i and j indicating the row and column, respectively.**

- Test dataset (test.csv): It has the **same structure as the training dataset but lacks the "label" column**.

For more details, please see the notebook in this repository.