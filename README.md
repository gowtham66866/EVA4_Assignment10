CIFAR - ResNet18

Objective

To use CutOut as Image augmentation technique

To use LR finder to find best LR range suitable for the model

To achieve 88% accuracy

To use SDG with Momentum

GradCam on 25 misclassified images

Result Accuracy Achieved - 87.37%

Best LR range for the model - 0.5 to 0.005

Data transformation used - ToTensor, Normalize, HorizontalFlip, CutOut

No. of Epochs - 50

Loss/Regularization - L2

Train and Test Accuracy

![image](https://user-images.githubusercontent.com/36323558/83954186-9ba99680-a864-11ea-9342-4b5ebd8bf354.png)

GradCam Output on 25 Misclassified Images

![image](https://user-images.githubusercontent.com/36323558/83954204-cd226200-a864-11ea-9bb2-32aa1b4ac38c.png)

