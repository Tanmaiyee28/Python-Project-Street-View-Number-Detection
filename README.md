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

Geolocation and tracking services are much needed in the present world to make life easier and safer for humans where it involves a wide range of situations such as locating an address for postal services or crime case where tracking is an essential task to help the victims. 

OCR can be used to track locations by extracting the information from the images in certain situations. Every day we see so many cases where it involves people missing. If by any chance there are any photos related to the crime, the OCR application can extract text from the images and helps to track their locations and find them in time if possible. Often these kinds of situations involve images from the wild, that is the information in the images is in the form of unstructured data, and it is hard to extract the text. 

The main aim of this project is to build a robust OCR application to extract information from the digital pictures where the text is called “text in the wild”.

Furthermore, this system can be performed in a real-world environment as well. OCR has various applications such as Passport recognition, automatic number plate recognition, Invoices recognition, credit card recognition, converting handwritten texts to digital text, and many more.



### Dataset:

SVHN – Street View Housing Numbers. The dataset consists of real-word images of house numbers which were collected from Google Street View images. This is dataset is considered as an unformatted dataset since the numbers in the dataset are from natural scene images and this is real-world problem because it is hard to recognize the numbers.
Features:
Number of classes: 10 classes (0-10).
Training Set: 73257 digits
Testing Set: 26032 digits
Extra Set: 531131 digits (less complicated samples).

### Outputs:

## Preprocessing
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o1.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o2.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o3.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o4.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o5.png)
## Model
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o6.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o7.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o8.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o9.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o10.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o11.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o12.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o13.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o14.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o15.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o16.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o17.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o18.png)
![alt text](https://github.com/Tanmaiyee28/Python-Project-Street-View-Number-Detection/blob/main/outputs/o19.png)

### Conclusion:
OCR has been implemented on the SVHN dataset using CNN and RNN models. The accuracy for OCR using CNN is much higher than the RNN model. RNN models are time-consuming compared to CNN and much complex. With better OCR tools, the world becomes a much safer and better place. 

### Future scope:
Scaling up the performance by trying various models and using various data augmentation techniques when noise is involved. AI is a fast-growing field and it will be a very important tool for future generations. OCR can be applied to the SVT dataset which is a much complex dataset. OCR can be used to provide location tracking services. 

### Blockages:
1.	We tried to implement OCR on Street View Text dataset which is unformatted data. 
2.	Preprocessing was done successfully on the data but, we couldn’t complete the model fitting on the data. The execution process was really time-consuming, and we couldn’t display the results since detection and recognizing the text was complex.
3.	We performed the OCR on the SVHN dataset, although the CNN model was performed reasonably well, we couldn’t improve the RNN model’s performance because of the time limit. 


### Work Sharing between Teammates:

Chaitanya Jakka: Data Pre-processing and Video Presentation

Naga Tanmaiyee Nagalla: Implementation of Model 1 and Power point Presentation

Venkata Sreesudha Madabhushi: Implementation of Model 2 and Report 

All the members are contributing equally to every aspect of the project.



### References:

1.https://towardsdatascience.com/a-gentle-introduction-to-ocr-ee1469a201aa

2.https://ieeexplore.ieee.org/document/6836618

3.https://en.wikipedia.org/wiki/Optical_character_recognition

4.https://searchcontentmanagement.techtarget.com/definition/OCR-optical-character-recognition

5.https://arxiv.org/abs/1704.03155v2

6.https://github.com/JaidedAI/EasyOCR





