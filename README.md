# mnist-recognition BUILDING INNOVATIVE SYSTEMS-UCS757
THE LIVE WORKING PROJECT IS AVAILABLE AT: https://kritika-alpha-num-recognition.herokuapp.com/
<br>

<h3>About:</h3>
<br>
This project is implementing EMNIST image dataset, where machine has been trained to predict which alphabet or number has been given as input by the user. Just write any letter or number and hit the predict button to see if machine understands what u have written.
<br>

UI is using Bootstrap + HTML
backend APIs have been designed using Flask.
ML model is using Keras Sequential Model for Convolutional Neural Networks.
neural net ha 8 layers:
2 Conv2d, 1 max pooling layer, 1 flattening layer, 2 dense layers and 2 droupout layers.
ACTIVATION FUNCTIONS USED RELU, SOFTMAX
TRAINING SET HAS on 112800 samples, VALIDATION HAS 18800 samples
<BR>
  ![image](https://user-images.githubusercontent.com/43928250/133225293-938f5924-b78d-4712-8d88-a73c9e0127e1.png)


  <h3>INSTALL ON YOUR MACHINE:</h3><br>
1) clone this repository 
2) install the requirements using: pip install -r requirements.txt 
3) flask run # to run the project on localhost
if u want to remake ML model u can use the data from the link given below.
<br>
  
<h3>ABOUT DATASET:,/h3>
<br>
The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset.
DATASET CAN BE FOUND AT: https://www.kaggle.com/crawford/emnist 

<b>,h3>FLOW CHART FOR METHODOLOGY:,/h3></b><br>

![flow1](https://user-images.githubusercontent.com/43928250/133068951-024c6bd0-6dd3-47db-a2b9-be5bfee568d4.png)



  <h3>IMAGES SHOWING OUTPUT </h3>
<br>
![image](https://user-images.githubusercontent.com/43928250/133066384-93ed5b6d-1318-46c7-a7c8-1fd49bcb0d5b.png)

<h3>output image 2,/h3>
<br>
![image](https://user-images.githubusercontent.com/43928250/133066568-078f469f-0c9d-429c-b819-db9e5998a0c9.png)


