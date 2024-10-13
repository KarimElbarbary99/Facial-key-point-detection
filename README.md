# Facial Keypoint Detection

In this project, I developed a facial keypoint detection system. The system comprises two main components: a face detector that utilizes Haar Cascades and a Convolutional Neural Network (CNN) for predicting facial keypoints. The purpose of this system is to take an input image containing one or more faces and accurately predict the locations of 68 distinguishing keypoints on each detected face.

The model is trained, validated, and tested using a dataset of 5770 color images sourced from the [YouTube Faces Dataset](https://www.cs.tau.ac.il/~wolf/ytfaces/). This dataset provides a diverse set of faces, enabling the model to generalize well across different facial expressions, orientations, and lighting conditions.

I used transfer learning on a pretrained ResNet-18 model from torchvision. This approach leveraged the powerful feature extraction capabilities of ResNet-18, fine-tuning it for the specific task of facial keypoint detection.

Here are the predicted keypoints for the provided test images using the ResNet model.

<img src="https://github.com/udacity/P1_Facial_Keypoints/blob/master/images/key_pts_example.png?raw=true" width="512">

The project's repository from Udacity is [P1_Facial_Keypoints](https://github.com/udacity/P1_Facial_Keypoints)
