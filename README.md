# Optical Character Recoginition 

## Increment-3


## Team Memebers:

Chaitanya Jakka - 16281850.

Venkata Sreesudha Madhabhushi - 16285247.

Naga Tanmaiyee Nagalla - 16286145.


### Introduction:

In this era of digitization, computers are becoming much smarter and getting better at performing human tasks. One such simple yet most important task of a human is 
to perceive everything that he sees using his eyes. But even humans have their limitations. What if humans have a bad sight or what they see is far away or if the 
picture is blurry? As a solution to solve these problems, here comes AI which is an ever-growing field to make life much easier and safer. Extracting information 
from a digital picture has become much easier nowadays. This is where OCR – Optical Character Recognition comes in. OCR converts text from images and scanned 
documents into machine-readable formats. Word spotting is an essential component of a vision-based text extraction system. 

### Problem Statement:

Crimes are also part of the progression of modernization of the world. Solving these crimes is essential to save many lives. OCR can be useful in solving certain 
crimes like kidnapping cases or missing cases for example. OCR can be used to track locations by extracting the information from the images in certain situations. Every day we see so many cases where it involves people missing. If by any chance there are any photos related to the crime, the OCR application can extract text from the images and helps to track their locations and find them in time if possible. Often these kinds of situations involve images from the wild, that is the information in the images is in the form of unstructured data, and it is hard to extract the text. 

The main aim of this project is to build a robust OCR application to extract information from the digital pictures where the text is called “text in the wild”.

Furthermore, this system can be performed in a real-world environment as well. Extracting texts from images has found numerous applications. Some of the applications are Passport recognition, automatic number plate recognition, converting handwritten texts to digital text, converting typed text to digital text, etc.


### Dataset:

SVT: Street View Text Dataset

1.The dataset consists of images collected from Google Street View

2.Total no of images: 350 from 20 different cities. 

3.Total no of labelled words: 725 words. 

4.Training set: 100 images: 211 words. 

5.Testing set: 250 images: 514 words. 

### Working Screens from the Project:

1.First we have to load the dataset and read the first image using imread() and print the shape and type of the image .

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/1.PNG)

2.Scale the images to right size (300) dots per inch if the image size is less it will be unclear to predict. 

3.Then we have to binarize the image, it converts the image to black and white.

4.Blur the image for smoothing the image .

5.Then we perform thresholding using cv2.threashold ().

6.First we have performed global threshold then applied gaussian filtering for removing the noise. 

7.Then applied the adaptive threshold.

8.Finally filtered the image with 5*5 gaussian kernel to remove the noise.

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/2.PNG)

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/3.PNG)

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/4.PNG)


9.Detected the edges of the image using cv2.Canny() and then plotted the both the images the original and the images with only edges.

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/5.PNG)

### OUTPUTS:

10.Printed the images after pre-processing the image.

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/output.PNG)

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/output2.PNG)

![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-text-detection/blob/main/Documentation/output3.PNG)

### Work Sharing between Teammates:

Chaitanya Jakka: Data Pre-processing and Implementation of Model 1.

Naga Tanmaiyee Nagalla: Implementation of Model 1 and Model 2.

Venkata Sreesudha Madabhushi: Implementation of Model 2 and Model 3. 

All the members are contributing equally to every aspect of the project.



### References:

1.https://towardsdatascience.com/a-gentle-introduction-to-ocr-ee1469a201aa

2.https://ieeexplore.ieee.org/document/6836618

3.https://en.wikipedia.org/wiki/Optical_character_recognition

4.https://searchcontentmanagement.techtarget.com/definition/OCR-optical-character-recognition

5.https://arxiv.org/abs/1704.03155v2

6.https://github.com/JaidedAI/EasyOCR





