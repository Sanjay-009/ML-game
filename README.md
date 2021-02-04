## ML-GAME

#### _This is a simple Game using ML model developed from **Teachable Machine**_

### Team Members :

#### **YALANGI SANJAY - 19PA1A05J0**
#### **SALADI ANIRUDH - 19PA1A05G0**

### About Game
#### This is a simple snake game controlled with our audio commands
#### Our model responds according to the audio keywords like **Up**, **Down**, **Left** and **Right** and moves the snake in that Direction.

### How it's made?

#### Step-1:
we collected a open source snake game in which a snake moves in a 2 dimensional space randomly. A special object is placed randomly in the space so that when the snake passes through that object i.e., when the snake eats the object, The size of the snale grows by 1 unit.

#### Step-2:
We train an audio model in my teachable machine using four audio classes namely Up, Down, Left, Right. After training the model we uploaded the model to the cloud.

#### Step-3:
Combining the Snake game and Myteachable machine model with Javascript.
The output of our code is displayed in the below repl.i link.

![Snake-ML](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/Screenshot%20(40).png)

### Repl link for game
#### https://mlgame.yalangisanjay.repl.co/

### Reference Links :
#### https://github.com/CodingTrain/website/tree/main/CodingChallenges/CC_115_Snake_Game_Redux/Processing
