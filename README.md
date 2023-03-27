# Image-Classification

About the project: The objective of this project is to identify various human expressions from an image, such as "happy," "sad," "surprise," etc. We have a dataset that comprises of 28829 train images and 7066 validation images of human expression. We use the CNN model, which was constructed using fully connected, convolutional, and pooling layers, for this reason. The convolutional layers extract features from the input image by running it through a succession of filters. The pooling layers reduce the feature maps' computational complexity and size by downsampling them. The completely connected layers use the extracted features to determine the class of the input image, as shown. In a neural network architecture known as a sequential model, data passes through a number of layers or processing units sequentially. This suggests that the output of one layer is sequentially fed as input to the next layer until the desired output is achieved. The CNN is the most popular kind of sequential model, and it was employed in this endeavor. (Convolutional Neural Network). 

Installation guidelines: Since the project is constructed over Colab, no special installations are needed. However, some libraries are necessary for this undertaking and must be included. The majority of them are fundamental tools like "numpy" and "pandas," which are essential components of any project involving machine learning.

Running the project:
1. Log in to Google Colab with your Google account by opening the website in a computer browser.
2. Download the code to your colab from the source. You must make a copy of this view-only notebook in your local drive so that you can modify it.
3. Click "Runtime" in the top menu to choose a runtime type, then select "GPU" to execute more quickly.
4. Download the dataset and submit it to the drive using this link: https://www.kaggle.com/datasets/samaneheslamifar/facial-emotion-expressions.
5. Mount the drive so you can access the information from there.
6. The remaining directions ask you to run each code fragment and collect the results.

Features of the project: This project focuses on a CNN model for recognizing facial emotions. The effectiveness of the freshly created model and the built-in "EfficientNetB2" model are compared. Additionally, it offers suggestions for potential future projects, like the normalization of pictures.

Additional Details: This involves a sizable dataset with around 32,000 pictures. Therefore, it is advised that one employs fast runtime hardware and large RAM when computing.
