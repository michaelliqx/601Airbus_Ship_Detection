# 601Airbus_Ship_Detection
### This is the project of ECE EC601,2018 FALL 
#### Group member: Qingxing Li  Yuhang Miao Sichun Hao

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
#### we could classify the ship by its size, color(RGB), edge detect
#### Using Opencv to abstract the imformation from picture 
#### then after we get the training data, we evaluate the distribution of the data to use choose a classification module
#### possible classification module: RNN, CNN, Random Forest, Decision Tree...
#### after that, we could use the testing data to calculate the loss function to confirm the result of our work. 

### Second step: Application Development
#### Based on html

