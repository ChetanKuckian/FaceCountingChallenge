# Face Counting Challenge

#### The dataset is taken from https://datahack.analyticsvidhya.com/contest/vista-codefest-computer-vision-1/.

- The aim of this problem is to detect the number of faces in an given image.
- The dataset contains 5733 training images and 2464 images for the final testing of the model.
- Using the create training dataset function the images in the training data gets loaded into a numpy array along with the number of faces present as the label column.
- This solution uses the transfer learning feature and train on the pre trained object detection models ResNet152V2,InceptionResNetV2,VGG19,InceptionV3 and MobileNetV2 using TensorFlow.
- The individual models give an RMSE of around 1.85 on the submission board, when we use the getFinalAvgPredictions function to average the outputs from all the model we get an RMSE of 1.683 which give a rank in the top 100 of the analytics vidhya leaderboard.
