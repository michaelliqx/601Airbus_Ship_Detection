# 601Airbus_Ship_Detection
### This is the project of ECE EC601,2018 FALL 
#### Group member: Qingxing Li  Yuhang Miao  Sichun Hao
### trello link:https://trello.com/b/V1oiuFlo/sprint1
# Notice: all the work of this project are in :https://github.com/Junoth/AirbusShipDetection

## Our Target:
### 1.to build a module that could detect the ship in a picture with high speed and precision, even to enumerate the number and to predict the route of the ship. 
### 2.build a application that can detect the ship more convenient.

## Our Challenge
#### a) the effect of cloud 
#### b) the influence of the resolution or haze 
#### c) the effect of other landmark
#### d) the size of ship various 
#### e) how to recognize the head of the ship

## High Level Diagram:

### First step: Machine learning
#### preprocess the picture, using, for example, grayscale
#### then we could classify the ship by its size, color(RGB), edge detection
#### Using Opencv to abstract the imformation mentioned above from picture 
#### after getting the training data, we calculate the distribution of the data to choose a classification module
#### possible classification module: RNN, CNN, Random Forest, Decision Tree...
#### after that, we could use the testing data to calculate the loss function to evaluate the result of our work. 

### Second step: Application Development
#### Based on html
#### Use google developer
##### required: Python, html, CSS





