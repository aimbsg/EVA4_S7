# EVA4_S7
CIFAR 10 - Functions are defined in separate module and invoked in main file

Epochs : 25
Model parameters : 604K
Validation accuracy : 80.2%

Model summary :
cuda
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 16, 32, 32]             448
       BatchNorm2d-2           [-1, 16, 32, 32]              32
              ReLU-3           [-1, 16, 32, 32]               0
           Dropout-4           [-1, 16, 32, 32]               0
            Conv2d-5           [-1, 32, 32, 32]           4,640
              ReLU-6           [-1, 32, 32, 32]               0
       BatchNorm2d-7           [-1, 32, 32, 32]              64
           Dropout-8           [-1, 32, 32, 32]               0
         MaxPool2d-9           [-1, 32, 16, 16]               0
           Conv2d-10           [-1, 64, 16, 16]          18,496
      BatchNorm2d-11           [-1, 64, 16, 16]             128
             ReLU-12           [-1, 64, 16, 16]               0
          Dropout-13           [-1, 64, 16, 16]               0
           Conv2d-14          [-1, 128, 14, 14]          73,856
      BatchNorm2d-15          [-1, 128, 14, 14]             256
             ReLU-16          [-1, 128, 14, 14]               0
          Dropout-17          [-1, 128, 14, 14]               0
        MaxPool2d-18            [-1, 128, 7, 7]               0
           Conv2d-19             [-1, 64, 7, 7]           8,256
      BatchNorm2d-20             [-1, 64, 7, 7]             128
             ReLU-21             [-1, 64, 7, 7]               0
           Conv2d-22            [-1, 128, 7, 7]          73,856
      BatchNorm2d-23            [-1, 128, 7, 7]             256
             ReLU-24            [-1, 128, 7, 7]               0
          Dropout-25            [-1, 128, 7, 7]               0
           Conv2d-26            [-1, 256, 7, 7]         295,168
      BatchNorm2d-27            [-1, 256, 7, 7]             512
             ReLU-28            [-1, 256, 7, 7]               0
          Dropout-29            [-1, 256, 7, 7]               0
        MaxPool2d-30            [-1, 256, 3, 3]               0
           Conv2d-31             [-1, 64, 3, 3]          16,448
      BatchNorm2d-32             [-1, 64, 3, 3]             128
             ReLU-33             [-1, 64, 3, 3]               0
           Conv2d-34            [-1, 128, 3, 3]          73,856
      BatchNorm2d-35            [-1, 128, 3, 3]             256
             ReLU-36            [-1, 128, 3, 3]               0
          Dropout-37            [-1, 128, 3, 3]               0
           Conv2d-38            [-1, 128, 3, 3]           1,280
           Conv2d-39            [-1, 256, 3, 3]          33,024
      BatchNorm2d-40            [-1, 256, 3, 3]             512
          Dropout-41            [-1, 256, 3, 3]               0
             ReLU-42            [-1, 256, 3, 3]               0
           Conv2d-43             [-1, 10, 3, 3]           2,570
      BatchNorm2d-44             [-1, 10, 3, 3]              20
             ReLU-45             [-1, 10, 3, 3]               0
        AvgPool2d-46             [-1, 10, 1, 1]               0
================================================================
Total params: 604,190
Trainable params: 604,190
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 3.67
Params size (MB): 2.30
Estimated Total Size (MB): 5.99
----------------------------------------------------------------

Supplementary :
Individual classes accuracy :
Accuracy of plane : 87 %
Accuracy of   car : 90 %
Accuracy of  bird : 67 %
Accuracy of   cat : 61 %
Accuracy of  deer : 81 %
Accuracy of   dog : 78 %
Accuracy of  frog : 83 %
Accuracy of horse : 82 %
Accuracy of  ship : 85 %
Accuracy of truck : 87 %
