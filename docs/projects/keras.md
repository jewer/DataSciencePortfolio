---
tags:
  - Tensorflow
  - Keras
  - Convolutional Neural Network
---

# Optical Recognition with Tensorflow/Keras

This notebook focuses on building a simple convolutional neural network (CNN) using Keras to classify handwritten digits from the MNIST dataset. It starts by loading and visualizing a few sample images to get a feel for the data, then preprocesses the images by reshaping them into the format expected by a CNN and normalizing the pixel values. The labels are one-hot encoded so they work cleanly with a multiclass neural network setup.

From there, the notebook defines and trains a CNN with convolutional, pooling, and dense layers to learn visual patterns in the digits. After training, the model is evaluated on the test set, and its predictions are analyzed using a confusion matrix to see where it performs well and where it struggles. Overall, the notebook demonstrates a straightforward end-to-end deep learning workflow: loading image data, building a neural network, training it, and interpreting the results visually rather than relying on accuracy alone.

### Working Code
- Notebook here: [opticalkeras.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/keras/opticalkeras.ipynb)