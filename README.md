# 315-Bird-Species-Image-Classification
The dataset contained 315 classes for different Bird Species which were classified. The code Implements 2 CNN architectures : </br>
1. VGG16 (16 layers)</br>
2. a Custom designed model (5 layers) </br>

The models are compared in terms of Accuracy and Training Time. </br></br>

The code further includes:</br>
##### 1. Grad CAM
##### 2. Transfer Learning
##### 3. Data Augmentation

The accuracies achieved are as below: </br>
|     Model     | Train Accuracy| Test Accuracy |
| ------------- | ------------- | ------------- |
|     VGG16     |     0.54%     |     0.31%     |
|  Custom Model |     42%       |     48%       |

#### Conclusion
The Custom Model performs better as compared to VGG16 in terms of both accuracy and time, with Custom Model having an
accuracy of 58% and training time of 3201 seconds whereas, VGG16 having an accuracy
of 0.31% and training time of 4838 seconds. VGG16 is over fitted
which was overcome in the Custom Model by adding Dropout Layers and removing the
number of convolution layers, hence improved accuracy and less training time.
