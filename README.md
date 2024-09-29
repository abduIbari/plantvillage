# PlantVillage Classification with Convolutional Neural Networks (CNN)
This project is part of a machine learning effort to classify images of plant leaves into different categories using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. The images are taken from the PlantVillage dataset, which contains various plant species and disease categories.

### Dataset
The PlantVillage dataset consists of thousands of leaf images that belong to various plant species, with some images labeled as healthy and others categorized as diseased.

- Source: [PlantVillage Dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)
- Classes: Healthy, diseased (various diseases like bacterial spot, late blight, leaf mold, etc.)
  
In this project, images are resized to 256x256 pixels to match the input size of the model.

### Model Architecture
The model used is a Convolutional Neural Network (CNN) built using TensorFlow/Keras. The architecture includes multiple convolutional layers, pooling layers, and dense layers, followed by a softmax output layer.

Key layers:

- Conv2D layers for feature extraction.
- MaxPooling2D layers for down-sampling.
- Flatten and Dense layers for classification.
- 
The final output layer uses softmax activation to predict one of the 10 classes.
