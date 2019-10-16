# Computer-vision-for-multi-class-image-classification.

```
 IDE:  Jupyter Notebook 
 Language: Python 3 
 Libraries: - Open CV 4.1.1
            - Tensorflow 1.10
            - Keras 2.1.6
            
 Models: - Baseline Model
         - ResNet50 Model
         - Inception V3 Model
 
```

### Overview
The Raw image data which represents the real world image data has been downloaded from the kaggle, which contains the images of 5 different class of animals and their corresponsing labels. The main objective of this project is to initially train the model with the convolution neural network using three models and then testing the accuracy, precison and recall of three models.

Initially, the neural network model is trained with the sequential baseline model which consists of 5 layers. Later, in order to optimize increase the precision of the classifier, the neural network is trained with ResNet50 and Inception V3.

It is found that the Inception model outperformed the other models demonstrating a training accuracy of 95% and validation accuracy of 74%.


### Sample images used for training the model

<img src="https://github.com/manojhuilgol/Computer-vision-for-multi-class-image-classification/blob/master/images/raw_data.png" alt="alt text">

### Model Evaluation

The below image represents the comparison of the Training and Validation accuracy with respect to the 3 models:

- Baseline model
- ResNet50 model
- Inception V3 model

<img src="https://github.com/manojhuilgol/Computer-vision-for-multi-class-image-classification/blob/master/images/evaluation.PNG" alt="alt text" width="700" height="400">
