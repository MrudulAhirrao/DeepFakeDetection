Topic name: Deepfake or Identity theft Detection using Image processing



Algorithms/ Techniques: Multi-Scale Retinex, Gaussian blur.





Multi-Scale Retinex (MSR)
Multi-Scale Retinex is a technique used in image processing to enhance the dynamic
range and color fidelity of an image. It works by decomposing the image into a base layer (representing the overall illumination) and a detail layer (representing the local variations in color and intensity). By adjusting the contrast of these layers independently, MSR can improve the appearance of images with uneven lighting or low contrast.
Gaussian Blur
Gaussian blur is a type of image smoothing technique that blurs an image using a
Gaussian kernel. The Gaussian kernel is a bell-shaped curve that weights pixels based on their distance from the center. By convolving the image with the Gaussian kernel,
Gaussian blur reduces noise, softens edges, and creates a more visually appealing image. It is often used as a preprocessing step for other image processing tasks.
Code:

 
Scale-Invariant Feature Transform (SIFT)
SIFT is a feature detection algorithm that finds keypoints in images and assigns them descriptors that are invariant to scale, rotation, and illumination changes.



 VGG-16 CNN Model
VGG16 is a popular CNN architecture known for its simplicity and depth. It's composed of 16 layers (13 convolutional layers and 3 fully connected layers).

•	Loading CNN model

vgg_model = VGG16(weights='imagenet', include_top=False, input_tensor=Input(shape=(224, 224, 3)))

•	weights='imagenet': This loads the weights pre-trained on the ImageNet dataset.
•	include_top=False: This excludes the fully connected layers on top of the model, which are used for classification in the original VGG16.
•	input_tensor=Input(shape=(224, 224, 3)): This defines the input shape for the model, which is 224x224 with 3 color channels (RGB).
Results:


![image](https://github.com/user-attachments/assets/67d5c26b-97e6-47b4-9dee-2dc85c439310)


Figure 1CNN Convolution

 ![image](https://github.com/user-attachments/assets/2e0663e9-4be7-45b1-aca2-d47a78c08d84)

Figure 2 Prediction & Accuracy












 


