# Image-Classification-Using-Transfer-Learning
Image understanding and classification using transfer Learning with Pre-trained model

**************************************************
# MobileNet V2:
 MobileNetV2 is a convolutional neural network architecture designed for efficient and lightweight deep learning tasks. It's particularly useful for mobile and embedded applications due to its compact design while maintaining respectable accuracy. The architecture contains multiple layers, including depthwise separable convolutions, that allow it to achieve a good trade-off between model size and performance.
       
For more details, please refer: https://github.com/keras-team/keras/blob/v2.13.1/keras/applications/mobilenet_v2.py#L96
*****************************************************
# 1. Feature extraction using MobileNet V2 model

-> model architecture on top of MobileNet V2 model:
**********
![](https://github.com/joshir199/Image-Classification-Using-Transfer-Learning/blob/main/Image_classification_transfer_learning_model_graph.png)

***************
-> training loss graph:
**********
![](https://github.com/joshir199/Image-Classification-Using-Transfer-Learning/blob/main/loss_graph_image_classification_using_transfer_learning.png)

******************
# 2. Fine tuning MobileNet V2 model (top 50 layers)

-> model architecture after fine tuning:
***************
![](https://github.com/joshir199/Image-Classification-Using-Transfer-Learning/blob/main/Fine%20tuned%20model%20graph.png)
**********************
-> training loss graph after fine tuning
****************
![](https://github.com/joshir199/Image-Classification-Using-Transfer-Learning/blob/main/loss_graph_image_classification_after_fine_tuning.png)

# Conclusion:
This technique is usually recommended when the training dataset is large and very similar to the original dataset that the pre-trained model was trained on.
For more detailed knowledge, please refer : https://www.tensorflow.org/guide/keras/transfer_learning
