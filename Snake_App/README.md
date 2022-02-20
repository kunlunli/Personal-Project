# Background
This program was made 100% percent by myself including the product design and the coding work. I made a completed APK so that you can install it on your phone. 

I made this APP due to an opportunity given by my first company-OPPO. In the first few months that I joined OPPO, It took me a lot of time to get familiar with the project. In order to help me warm up and strengthen my coding ability, my boss asked me to develop an app. So I made this interesting game app. It's not only a clone from the classic snake game but also carries some exciting innovations.

# Main function description #

## 1.Login procedure ## 

I designed a login system which support logging in or signing up with username and password. As it shows in the below pictures.

<figure class="half">
    <image src="https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/login.jpg?raw=true" width=300>
    <image src="https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/sign-up.jpg?raw=true" width=300>
</figure>

| Function                       | Description                                                  |
| :----------------------------- | ------------------------------------------------------------ |
| **Log in**                     | Use username and password to log in. I don't have any server so I store all the users info in local memory. |
| **Sign up**                   | Use username, password and e-mail to create a new account.   |
| **Remember Username and password** | Remember the username logged in the last time.             |

## 2.Home page ##

<figure>
	<image src="https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/home.jpg?raw=true" width=400>
</figure>

| Function    | Description |
| ----------- | ----------- |
| **Normal mode** | details are as follows |
| Innovation mode | A biggest different part from the classic Snake game.  details are as follows. |
| Setting | Used to adjust some settings for users |


## 3.Normal mode ##

| Function  | UI                                                           | Description                                                  |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| In game   | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/normal-mode.jpg?raw=true) | Use the roulette to control the snake's direction. Other Snakes are all run by algorithms automatically.  User's current score is shown around the top left. |
| Game over | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/normal-over.jpg?raw=true) | The user will lose when touching any snake's body or the edge of the map. |
| Palse     | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/normal-palse.jpg?raw=true) | Double clicking the screen can stop the game. User can save the game or exit the game directly.  The current score is also shown. |


## 4.Innovation mode ##

### How to play ###
The innovation mode requires users to pass three levels to win the game. In every level, the user need to get scores by eating the "food".  Only that the food is different from the classic snake game. The Innovation mode is actually similar to the work flow of a programmer. The details are follows:

- The Snake actually symbolizes a programmer who needs to keep fixing bugs or completing PM's requirements. 
- One kind of the food actually symbolizes the bugs that a programmer may encounter everyday. Besides, this kind of food changes over time. The food's size will keep growing, the color will turn from blue to yellow and eventually become red. This progress actually symbolizes that the urgency of a bug will change over time. In the beginning, maybe it's only a insignificant error. But it will become more and more serious if we ignore it and eventually we need to solve it in a limited time. In the game , if the "food" turns to red and we didn't eat it in a limited time, the user's score will be deducted.
- The other kind of "food" symbolizes the product requirements made by the the PM.  Similarly, the size and color of this food is also  changing all the time. The progress actually symbolizes the urgency of a requirement is also changing all the time.  If a programmer can't arrange all the requirements, he may need to work very hard to consume them before the deadline eventually. Similarly, if  the player doesn't consume the "food" in time, he will lose some points.
- The skeletons wandering in the map symbolize the dangers that may happen to a programmer(Like the heart disease). Touching the skeleton will also deduct the player's points.
- The player use the roulette to change the direction and use the speeding button to speed up.

### Three levels ###

| Level   | UI   | Time limit | Needed Score |
| ------- | ---- | ---------- | ------------ |
| level 1 | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/level1?raw=true) | 30s        | 100          |
| level 2 | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/level2.jpg?raw=true) | 30s        | 120          |
| level 3 | ![](https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/level3.jpg?raw=true) | 30         | 130          |

## 5.History ##

History page is used to store the user's records. The records are sorted by scores.

<figure>
	<image src="https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/history.jpg?raw=true" width=400>
</figure>

## 6.Setting ##

<figure>
	<image src="https://github.com/kunlunli/Personal-Project/blob/main/Snake_App/images/setting.jpg?raw=true" width=400>
</figure>

| Function          | Description                                                  |
| ----------------- | ------------------------------------------------------------ |
| Background music  | There is an interesting music while the player is playing. The player can choose to shut it down. |
| Game music        | There will be some sound effect while playing, such as the sound that the "snake" eats the "food". It can be shut down. |
| Operating habbits | The player can choose the operate  the roulette on the left hand or on the right hand. |

