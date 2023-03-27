# Image-Classification-using-sequential-Model

About the project: In this project, we have a dataset that consists of 28829 train images and 7066 validation images of human expression and our goal is to identify different expressions such as 'happy', 'sad', 'surprise', etc. from the image. For this purpose we make use of CNN model that is build using fully connected layers, convolutional layers and pooling layers. By applying a series of filters to the input picture, the convolutional layers extract features from the image. The feature maps are downsampled by the pooling layers, which lessens their processing complexity and size. The extracted features are then used by the fully connected layers to determine the class of the input image as shown. Data flows sequentially through a number of layers or processing units in a neural network design known as a sequential model. This implies that, until the desired output is obtained, the output of one layer is sequentially feds as input to the next layer. The most common type of sequential model, and the one used in this project is the CNN (Convolutional Neural Network). 

Installation Instructions: This does not require any specifi installations as the project is built over colab. However there are some libraries that need to be included for this project. Most of them are the basic libraries such as 'numpy' and 'pandas' which are a must include in every Machine Learning project.

How to run the project:
1. Open Google Colab in your web browser and sign in using your Google account.
2. Pull the code from the repository to your colab or you can directly click on 'https://colab.research.google.com/drive/1hc5mG-WBKNcI2mm_IFmzPqh78id7YvyG?usp=sharing' link for code. This is a view only notebook and you will have to create a copy of it in your local drive for editing.
3. Select a runtime type by clicking on "Runtime" in the top menu, then change to "GPU" for running faster.
4. Download the dataset from 'https://www.kaggle.com/datasets/samaneheslamifar/facial-emotion-expressions' and upload it the drive.
5. Access the dataset from the drive by mounting it.
6. Rest of the instructions include running every code snippet and get the output.

Project features: This project deals with a CNN model for identifying expressions on the face. It compares the performances of the inbuilt 'EfficientNetB2' model and a newly designed model. It also has guidance of the future work that could be taken up such as the normalization of images.

Additional Information: This deals with a bulky dataset of size approximately 32,000 images. Thus it is recommended that one uses high RAM and faster runtime hardware for computation. 
