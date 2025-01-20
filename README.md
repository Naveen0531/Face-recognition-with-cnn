# Face-recognition-with-cnn

## Face Recognition using ResNet and Decision Tree
This project implements a face recognition system using a combination of ResNet for feature extraction and a Decision Tree for classification. Additionally, it explores the use of a Convolutional Neural Network (CNN) for comparison.

**Features**
- Dataset: Utilizes the Labeled Faces in the Wild (LFW) dataset.
- ResNet:
   - Custom implementation with a series of basic residual blocks.
   -  Extracts features from the dataset images.
- Decision Tree:
-- Custom-built decision tree for classifying the extracted features.
-- Uses Gini impurity for determining the best splits.
- CNN:
-- Implements a Keras-based convolutional neural network for direct classification.
**Results**
- ResNet + Decision Tree:

-- Accuracy: 39.15%
-- Classification report provided for detailed performance analysis.
- CNN:

-- Accuracy: 46.12%
-- Classification report highlights the strengths and weaknesses of the model.


**Key Files**
- resnet_decision_tree.py: Contains the implementation of ResNet and Decision Tree.
- cnn_model.py: Defines the CNN architecture and training process.
- requirements.txt: Lists the required dependencies.

**Performance Analysis**
Both the ResNet-Decision Tree combination and the CNN achieved moderate accuracy levels. While the CNN outperformed the custom ResNet + Decision Tree, further optimization and hyperparameter tuning could improve results.
