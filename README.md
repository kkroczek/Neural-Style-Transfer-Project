## Neural-Style-Transfer-Project

Introduction
The main goal of this project was to exchange the VGG19 model from the original code with the model of our own creation. 

Few words about Neural Style Tranfer 

Examples of use NST

Our Model
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

Our Achievements 
