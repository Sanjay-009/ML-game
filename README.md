## ML-GAME

#### _This is a simple Game using ML model developed from **Teachable Machine**_

### Team Members :

#### **YALANGI SANJAY - 19PA1A05J0**
#### **SALADI ANIRUDH - 19PA1A05G0**

### About Game
#### This is a simple snake game controlled with our audio commands
#### Our model responds according to the audio keywords like **Up**, **Down**, **Left** and **Right** and moves the snake in that Direction.

### How it is made?

#### Step-1:
##### we collected a open source snake game in which a snake moves in a 2 dimensional space randomly. A special object is placed randomly in the space so that when the snake passes through that object i.e., when the snake eats the object, The size of the snale grows by 1 unit.

#### Step-2:
##### We train an audio model in my teachable machine using four audio classes namely Up, Down, Left, Right. After training the model we uploaded the model to the cloud.

#### Step-3:
##### Combining the Snake game and Myteachable machine model with Javascript.
##### The output of our code is displayed in the below repl.i link.

![Starting Game](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/ML-Game/Game%20Starting.png)

### How it will work!

#### Step-1:
##### Click on the start button and wait for 5 seconds to start the game. Then it shows loading.....

![Loading](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/ML-Game/Loading.png)

#### step-2:
##### Then wait for a while, Until it shows **Your move is waiting**.

![Waiting for move](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/ML-Game/Waiting%20for%20move.png)

#### step-3:
##### Now you can speakout to move the snake by using the above commands and it will move accordingly....

![Making move](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/ML-Game/Making%20move.png)

#### End game
##### If the snake touches the border line our game ends, It shows a red screen means **GAMEOVER**.

![GameOver](https://raw.githubusercontent.com/Sanjay-009/ML-game/main/ML-Game/GameOver.png)

### Repl link for game
#### https://mlgame.yalangisanjay.repl.co/

### Reference Links :
#### https://github.com/CodingTrain/website/tree/main/CodingChallenges/CC_115_Snake_Game_Redux/Processing
