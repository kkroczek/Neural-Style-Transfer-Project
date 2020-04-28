# Neural-Style-Transfer-Project

## <b>Introduction</b>

The main goal of this project was to exchange the VGG19 model from the original code with the model of our own creation. 

## Few words about Neural Style Transfer 

"Neural Style Transfer (NST) refers to a class of software algorithms that manipulate digital images, or videos, to adopt the appearance or visual style of another image. NST algorithms are characterized by their use of deep neural networks in order to perform the image transformation. Common uses for NST are the creation of artificial artwork from photographs, for example by transferring the appearance of famous paintings to user supplied photographs. Several notable mobile apps use NST techniques for this purpose, including DeepArt and Prisma."

## Algorithm takes style from "Style Image" given by us and applies it to the "Content Image".
![image](https://sandipanweb.files.wordpress.com/2018/01/louvre_generated.png?w=676)

![image](https://cdn-images-1.medium.com/max/1600/0*F3xvwBKFhaQ3Mh_k)

## Examples of use NST
- fashion design
- architecture
- for fun :)

## Our Model
Layer: Conv2D 
Output Shape: (None, 48, 48, 16)  
Param: 448

Layer: Conv2D       
Output Shape: (None, 46, 46, 16)  
Param: 2320

Layer: MaxPooling2  
Output Shape: (None, 15, 15, 16)  
Param: 0

Layer: Conv2D       
Output Shape: (None, 13, 13, 32)  
Param: 4640

Layer: Conv2D       
Output Shape: (None, 11, 11, 32)  
Param: 9248

Layer: MaxPooling2  
Output Shape: (None, 5, 5, 32)    
Param: 0

Layer: Flatten      
Output Shape: (None, 800)         
Param: 0 

Layer: Dense        
Output Shape: (None, 64)          
Param: 51264

Layer: Dense        
Output Shape: (None, 1)           
Param: 65

Total params: 67,985

Trainable params: 67,985

Non-Trainable params: 0

## How to use our project?
First of all you have to download NST_model.h5 file and save it in your computer.
Then obviously you need to copy code from Neural_Style_Transfer_Project.ipynb file and run it with the use of our model.

